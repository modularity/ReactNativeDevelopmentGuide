# Debug and upgrade React Native projects

### Quick project reset

  Reset watchman 

      $ watchman watch-del-all

  Delete the node_modules and clean install via package.json

      $ rm -rf node_modules && npm install

  Reset packager cache 

      $ rm -fr $TMPDIR/react-* or npm start -- --reset-cache
      $ rm -rf ~/.yarn-cache/npm-realm-*

### For dependency TARGET_LIB update or breaking the build

  If library was previously linked
  
    $ react native unlink TARGET_LIB 
    
  Whether linked or not, uninstall it
  
    $ npm uninstall TARGET_LIB 
    
  Reset watchman
 
    $ watchman watch-del-all
    
  Reinstall library and potentially specify version
  
    $ npm install --save TARGET_LIB 
    $ npm install --save TARGET_LIB@VERSION
    
  Reset the packager's cache
  
    $ rm -fr $TMPDIR/react-* 
    
  Restart the packager 
  
  *Note this will transform the terminal window in the the packager, so consider running this line in a new window.*

    $ npm start -- --reset-cache

### Hard reset of cache:

  Reset watchman
  
    $ watchman watch-del-all

  Remove node_modules and reinstall via package.json configurations
  
    $ rm -rf node_modules && npm install
 
  Reset packager's cache 
  
    $ rm -rf $TMPDIR/react-*
  
  Reset npm cache
  
    $ rm -rf $TMPDIR/npm-*
    

### For android build errors

    $ cd android && ./gradlew clean
    $ cd ../ && react-native start -- --reset-cache
    $ react-native run-android


### For iOS build errors

  Delete Xcode derived data 
  
    Xcode -> File -> Preferences -> Locations -> Derived Data
    Select arrow to open folder in Finder and delete everything.
    Then close Xcode and reopen the project.

  Delete platform caches and reset npm 
    
    $ rm -rf ios/build
    $ npm start -- --reset-cache

### If CocoaPods is setup for iOS

    $ rm -rf ios/Pods
    $ pod cache clean --all
    $ pod repo update && pod install
    
    
### Upgrading React Native

  *Note: It's helpful to unlink native modules first. This reduces conflicts when upgrading the build.*

  Unlink dependencies individually  
    
    $ react-native unlink NATIVEMODULENAME 

  Ensure that react-native-git-upgrade is installed
    
    $ npm install -g react-native-git-upgrade
      
  Run the upgrade with option to specify version. This can sometimes be used to downgrade
    
  *Note: Read release notes to be aware of changes between builds e.g. single entry point with 0.49*
    
    $ react-native-git-upgrade
    $ react-native-git-upgrade 0.51
      
  Resolve any conflicts in build
    
  Link all 3rd party libs back into the project

    $ react-native link
