
# DIVE IN
#### GETTING STARTED
- [Presentation: overview of React Native](https://docs.google.com/presentation/d/1XHoO5OzxoWgOQD6zDhGFssL-PT9MNp7P89pFWWnyFHw/edit?usp=sharing)

- [Overview with Tutorial](http://www.reactnativeexpress.com/)

- [Docs](https://facebook.github.io/react-native/docs/getting-started.html)

#### DEV TOOLS
- [IDE - Atom](https://atom.io/)

- [React Native package for Atom - Nuclide](https://nuclide.io/)

- [IDE - Visual Studio Code](https://code.visualstudio.com/)

- [Catch typing errors - Flow](https://flow.org/)

- [Unit Tests - Jest](http://facebook.github.io/jest/)

- [Debugging - React Native docs](https://facebook.github.io/react-native/docs/debugging.html)

#### STARTER KITS
- [Easiest way to build your first project - Expo](https://expo.io/) 

- [Overview of Expo - JS Solutions blog](https://jssolutionsdev.com/blog/tools-for-react-native-app-development-expo-review/)

- [CLI with boilerplates, plugins, etc - Ignite](https://github.com/infinitered/ignite) 

- [UI starter kit - Kitten Tricks](https://github.com/akveo/kittenTricks)

- [UI components library - React Native Elements](https://github.com/react-native-training/react-native-elements)

- [UI components library - Nacho UI](https://avocode.com/nachos-ui/docs)


#### RUN ON A DEVICE
- [Running on Device - React Native docs](https://facebook.github.io/react-native/docs/running-on-device.html)

#### COMMUNITY
- [Support resources - React Native docs](https://facebook.github.io/react-native/support.html)

- [Reactiflux Dischord channel](https://discord.gg/0ZcbPKXt5bZjGY5n)

- [FB React Native Community](https://www.facebook.com/groups/react.native.community)

- [Official Twitter for React Native](https://twitter.com/reactnative)

- [Official React Native blog](https://facebook.github.io/react-native/blog/)

# SOLIDIFY THE FOUNDATION
#### JAVASCRIPT
- [JavaScript envirnoment and syntax with React Native - React Native docs](http://facebook.github.io/react-native/releases/0.49/docs/javascript-environment.html)

- [MDN docs on JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

- [ES6 feature overview - lukehoban on GitHub](https://github.com/lukehoban/es6features)

#### REACT
- [React docs](https://reactjs.org/)

#### COMPONENTS
- Native, not web components e.g. <view> not <div>

- Building blocks of React Native app

- Has JSX, props and state

- [Components and APIs - React Native docs](https://facebook.github.io/react-native/docs/components-and-apis.html) 

#### JSX
- Write markup language in the codebase

- Syntax for embedding XML within JavaScript e.g. <Text>Hello world!</Text>

- [JSX in Depth - React docs](https://reactjs.org/docs/jsx-in-depth.html) 

#### PROPS
- Set by the parent

- Fixed throughout lifetime of the app

- Creation parameters customize components

- [Props - React Native docs](https://facebook.github.io/react-native/docs/props.html) 

#### STATE
- Track data changes in app

- Init in constructor, then call setState to update 

- Changes in state trigger RN lifecycle e.g. render() to run again

- [State - React Native docs](https://facebook.github.io/react-native/docs/state.html) 

#### LIFECYCLE
- [Component Lifecycle - React docs](https://reactjs.org/docs/react-component.html) 

- [React Lifecycle methods - Musefind blog](https://engineering.musefind.com/react-lifecycle-methods-how-and-when-to-use-them-2111a1b692b1) 

#### REDUX
- Paradigm to manage app state and data flow

- [Redux docs](http://redux.js.org/)

- [Videos on redux - Dan Abramov on egghead.io](https://egghead.io/courses/getting-started-with-redux)

- [Redux tutorial - happypoulp on GitHub](https://github.com/happypoulp/redux-tutorial)

- [Redux cartoon - Lin Clark on Meduim](https://code-cartoons.com/a-cartoon-intro-to-redux-3afb775501a6)

#### MOBILE DEVELOPMENT

- [Typical Mobile Development Cycle - Thinslices blog](https://www.thinslices.com/blog/phases-mobile-product-development-process)

- [Indepth Mobile Development Process - The BHW Group](https://thebhwgroup.com/blog/mobile-app-development-process)

- [Add custom splash screen - Medium](https://medium.com/handlebar-labs/how-to-add-a-splash-screen-to-a-react-native-app-ios-and-android-30a3cec835ae)

- [Update app icon - Bam Tech Blog](https://blog.bam.tech/developper-news/change-your-react-native-app-icons-in-a-single-command-line)

- Note: Caches increase loading times, but may need to be deleted to process project updates. For changes to core app settings like app icon and splash screens, make sure to clear Derived Data in Xcode. iOS Emulators should be reset or uninstall the app. Android emulators also need to be reset as well for updates to app icons/splash screens.

#### iOS DEVELOPMENT

- [iOS permissions in Info.plist - Apple Developer docs](https://developer.apple.com/library/content/documentation/General/Reference/InfoPlistKeyReference/Introduction/Introduction.html)

- [Overview of iOS certificates, identifiers and profiles - Theodo](https://www.theodo.fr/blog/2017/02/a-beginners-guide-to-ios-provisioning-profiles/)

- [Program to setup iOS certificates, provisioning profiles, TestFlight, Distribution - Apple Developer](https://developer.apple.com/programs/)

- [iOS certificate types - Apple Developer](https://developer.apple.com/support/certificates/)

- [iOS App Distribution Guide - Apple Developer docs](https://developer.apple.com/library/content/documentation/IDEs/Conceptual/AppDistributionGuide/Introduction/Introduction.html)

- [Platform to manage App Store submissions - iTunesConnect](https://itunesconnect.apple.com/)

- [Xcode: Delete derived data and clean project - iOSDevCenters](https://iosdevcenters.blogspot.com/2015/12/how-to-delete-derived-data-and-clean.html)

- To reset iOS Emulators:
    
      For Xcode 9, Simulator -> Hardware -> Erase All Content and Settings...
    
      For Xcode 8, Simulator > Reset Content and Settings

#### ANDROID DEVELOPMENT

- [Android permissions in AndroidManifest.xml - Android Developer docs](https://developer.android.com/guide/topics/permissions/index.html)

- [Platform to manage Google Play submission - Android Developer](https://developer.android.com/distribute/console/index.html)

- [Features with Google Play Console - Android Developer](https://developer.android.com/distribute/console/features.html)

- To reset Android emulator: 
       
      Add the parameter -wipe-data to commandline when starting an emulator 
          e.g. /Users/YOURNAME/Library/Android/sdk/tools/emulator -avd Nexus_S_API_25 -wipe-data        
  
      Android Studio -> Tools > Android > AVD Manager -> Select your emulator device -> Wipe data

# THE NEXT LEVEL
#### CONTRIBUTE
- [How to contribute to open source - Opensource.guide](https://opensource.guide/how-to-contribute/) 

- [Contributing to React Native - React Native docs](https://facebook.github.io/react-native/docs/contributing.html)

#### PERFORMANCE
- [Performance with React Native - React Native docs](https://facebook.github.io/react-native/docs/performance.html)

#### DESIGN
- [Design, prototyping for UI - Figma](https://www.figma.com)

- [Vector editor - Designer.io](https://designer.io/)

- [Image editor - Pixlr](https://pixlr.com/web)

- [Simple graphic design tool - Canva](https://www.canva.com/)

- [Add custom icons to an app - Medium](https://medium.com/bam-tech/add-custom-icons-to-your-react-native-application-f039c244386c)

#### NODE
- [Node.js docs](https://nodejs.org/en/docs/)

- [packager managers: yarn vs npm - RisingStack](https://blog.risingstack.com/yarn-vs-npm-node-js-package-managers/)

- [Understanding differences between npm, yarn and pnpm - Alex Kras](https://www.alexkras.com/understanding-differences-between-npm-yarn-and-pnpm/)

#### TOOLS FOR LIBRARY SELECTION
- [Compare repos: stars, issues, etc - npmcompare](https://npmcompare.com/)

- [Resource for recommended React Native libaries - Awesome React Native](http://www.awesome-react-native.com)

#### LINKING LIBRARIES
- [Linking libraries for iOS builds - React Native docs](https://facebook.github.io/react-native/docs/linking-libraries-ios.html) 

- [Manage iOS native modules w CocoaPods - React Native docs](https://facebook.github.io/react-native/docs/integration-with-existing-apps.html#3-install-cocoapods)

- [Native Modules with Android - React Native docs](https://facebook.github.io/react-native/docs/native-modules-android.html) 

#### UPGRADING BUILDS
- Currently updates once a month

- DO NOT recommend upgrading immediately unless read the release notes and are willing to break a project build. There are typically unforeseen issues with dependencies and 3rd party libraries.

- DO recommend upgrading immediately if you want to help stabilize the build by reporting bugs and collaborating with the community to create patches. The core team can’t test everything. Why not help fix it?

- [List of versions - React Native docs](http://facebook.github.io/react-native/versions.html) 

- [Upgrading React Native - React Native docs](https://facebook.github.io/react-native/docs/upgrading.html)

- [Upgrade package.json dependencies - tjunnone on GitHub](https://github.com/tjunnone/npm-check-updates)

#### 3rd PARTY LIBRARIES
- [Icons and fonts - react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)

- [Officially recommended navigation library - react-navigation](https://github.com/react-community/react-navigation)

- [Really popular navigation library - react-native-navigation](https://github.com/wix/react-native-navigation)

- [FB login, sharing, etc - react-native-fbsdk](https://github.com/facebook/react-native-fbsdk)

- [Device storage w relational db - realm](https://realm.io/docs/javascript/latest/)

- [Mapview w markers - react-native-maps](https://github.com/airbnb/react-native-maps)

- [Animations - lottie-react-native](https://github.com/airbnb/lottie-react-native)

- [SVG library - react-native-svg](https://github.com/react-native-community/react-native-svg)

- [Data visualization - victory-native](https://github.com/FormidableLabs/victory-native)

- [Data visualization - react-native-chart](https://github.com/tomauty/react-native-chart)

- [Progress bars - react-native-image-progress](https://github.com/oblador/react-native-image-progress)

- [Cross-platform: web, mobile - reactxp](https://github.com/Microsoft/reactxp)

- [Calendar UI - react-dates](https://github.com/airbnb/react-dates)

- [Select media from device library or camera - react-native-image-picker](https://github.com/react-community/react-native-image-picker)

- [Device info - react-native-device-info](https://github.com/rebeccahughes/react-native-device-info)

- [Firebase sdk - react-native-firebase](https://github.com/invertase/react-native-firebase)

- [Google Analytics wrapper - react-native-google-analytics-bridge](https://github.com/idehub/react-native-google-analytics-bridge)

- [Documentation generation - react-docgen](https://github.com/reactjs/react-docgen)

- [AWS SDK - aws-sdk-js](https://github.com/aws/aws-sdk-js)

- [File access and data transfer - react-native-fetch-blob](https://github.com/wkh237/react-native-fetch-blob)

- [Record audio - react-native-audio](https://github.com/jsierles/react-native-audio)

- [Image pan and zoom - react-native-photo-view](https://github.com/alwx/react-native-photo-view)

# HOME STRETCH
#### CREATING AND MANAGING ASSETS
- [Automate build and release steps - fastlane](https://github.com/fastlane/fastlane)

- [Transform app icon/splashscreen resource into necessary sizes for iOS and Android - Image Gorilla](http://apetools.webprofusion.com/tools/imagegorilla)

#### PROJECTS WITHOUT NATIVE MODULES
- [Continuous deloyment via Microsoft's CodePush](https://github.com/Microsoft/react-native-code-push)

#### PUBLISH FOR IOS
1. Update Xcode scheme for project Product -> Scheme -> Edit Scheme -> Run -> Info -> Build Configuration -> Release

2. Ensure certificates are set for Distribution (configure w Apple Developer account)

3. Each new archive sent to the App Store must have an incremental version number e.g. 1.0 -> 1.01 Target PROJECTNAME -> General -> Identity -> Version

4. Update platform to 'Generic iOS Device'

5. Clean the project

6. Product -> Archive

7. Window -> Organizer -> Archives -> PROJECTNAME -> select version -> Upload to App store The process may take a few minutes to complete.

8. The new binary will become available in iTunesConnect.

#### PUBLISH FOR ANDROID

- [Google Play Store Checklist - Android Developer](https://developer.android.com/distribute/best-practices/launch/launch-checklist.html)

1. [Create signed APK - React Native docs](https://facebook.github.io/react-native/docs/signed-apk-android.html)

2. The generated APK is found under PROJECTNAME/android/app/build/outputs/apk/app-release.apk

3. Upload this file to Google Play Console.

