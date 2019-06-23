- The name of the given podspec `yoga` doesn't match the expected one `Yoga`
  - 解决办法:将cocoapods 中`Yoga` 改成`yoga`
- 'folly/Portability.h' file not found
  - pod "Folly", :podspec => "../../../RNAPP/node_modules/react-native/third-party-podspecs/Folly.podspec"
  - https://github.com/facebook/react-native/issues/18769
- CocoaPods could not find compatible versions for pod

```
CocoaPods could not find compatible versions for pod "DoubleConversion":
  In snapshot (Podfile.lock):
    DoubleConversion (= 1.1.5)

  In Podfile:
    DoubleConversion (from `../../../RNAPP/node_modules/react-native/third-party-podspecs/DoubleConversion.podspec`)
```

```
* pod install --repo-update
```

- 'folly/Portability.h' file not found

```
    post_install do |installer|
        installer.pods_project.targets.each do |target|
            if target.name == "React"
                target.remove_from_project
            end
        end
    end
```

- framework not found React

```

```

- undefined is not a function (near '...React.createClass...')
  - npx react-codemod class --mixin-module-name=react-addons-pure-render-mixin --flow=true --pure-component=true --remove-runtime-proptypes=false <path>
- undefined is not an object (evaluating 'React.PropTypes.func')
  - npx react-codemod React-PropTypes-to-prop-types <path>
  - npx react-codemod ReactNative-View-propTypes <path>
- https://github.com/CodingPapi/blog/issues/1

```
// static propTypes =
// export default class EZRScrollableTabBar extends React.Component {
```

- rm -rf ~/Library/Developer/Xcode/DerivedData
- rm -rf node_modules; rm -rf Pods
- yarn start --reset-cache
- https://myrnnote.blogspot.com/2018/10/

- watchman watch-del-all
- rm -rf node_modules && npm install
- npm start -- --reset-cache
- rm -rf /tmp/metro-bundler-cache-*
- rm -rf /tmp/haste-map-react-native-packager-*

### #

```
Failed to load bundle(http://localhost:8081/index.ios.bundle?platform=ios&dev=true) with error:(Unable to resolve module `react-native-circular-progress` from `/Users/megahertz/RNAPP/app/redux/components/Objective.js`: Module `react-native-circular-progress` does not exist in the Haste module map

This might be related to https://github.com/facebook/react-native/issues/4968
To resolve try the following:
  1. Clear watchman watches: `watchman watch-del-all`.
  2. Delete the `node_modules` folder: `rm -rf node_modules && npm install`.
  3. Reset Metro Bundler cache: `rm -rf /tmp/metro-bundler-cache-*` or `npm start -- --reset-cache`.
  4. Remove haste cache: `rm -rf /tmp/haste-map-react-native-packager-*`. (null))

```

#### Failed to load bundle(http://localhost:8081/index.ios.bundle?platform=ios&dev=true) with error:(Unable to resolve module `react-native-gesture-handler` from `/Users/megahertz/RNAPP/node_modules/@react-navigation/native/src/Scrollables.js`: Module `react-native-gesture-handler` does not exist in the Haste module map

```
Failed to load bundle(http://localhost:8081/index.ios.bundle?platform=ios&dev=true) with error:(Unable to resolve module `react-native-gesture-handler` from `/Users/megahertz/RNAPP/node_modules/@react-navigation/native/src/Scrollables.js`: Module `react-native-gesture-handler` does not exist in the Haste module map

This might be related to https://github.com/facebook/react-native/issues/4968
To resolve try the following:
  1. Clear watchman watches: `watchman watch-del-all`.
  2. Delete the `node_modules` folder: `rm -rf node_modules && npm install`.
  3. Reset Metro Bundler cache: `rm -rf /tmp/metro-bundler-cache-*` or `npm start -- --reset-cache`.
  4. Remove haste cache: `rm -rf /tmp/haste-map-react-native-packager-*`. (null))

__38-[RCTCxxBridge loadSource:onProgress:]_block_invoke.228
    RCTCxxBridge.mm:414
___ZL36attemptAsynchronousLoadOfBundleAtURLP5NSURLU13block_pointerFvP18RCTLoadingProgressEU13block_pointerFvP7NSErrorP9RCTSourceE_block_invoke.118
__80-[RCTMultipartDataTask URLSession:streamTask:didBecomeInputStream:outputStream:]_block_invoke
-[RCTMultipartStreamReader emitChunk:headers:callback:done:]
-[RCTMultipartStreamReader readAllPartsWithCompletionCallback:progressCallback:]
-[RCTMultipartDataTask URLSession:streamTask:didBecomeInputStream:outputStream:]
__88-[NSURLSession delegate_streamTask:didBecomeInputStream:outputStream:completionHandler:]_block_invoke
__NSBLOCKOPERATION_IS_CALLING_OUT_TO_A_BLOCK__
-[NSBlockOperation main]
-[__NSOperationInternal _start:]
__NSOQSchedule_f
_dispatch_call_block_and_release
_dispatch_client_callout
_dispatch_continuation_pop
_dispatch_async_redirect_invoke
_dispatch_root_queue_drain
_dispatch_worker_thread2
_pthread_wqthread
start_wqthread

```

```
Module AppRegistry is not a registered callable module (calling runApplication)

__callFunction
    index.ios.bundle?platform=ios&dev=true:8168:18
<unknown>
    index.ios.bundle?platform=ios&dev=true:7927:31
__guard
    index.ios.bundle?platform=ios&dev=true:8124:15
callFunctionReturnFlushedQueue
    index.ios.bundle?platform=ios&dev=true:7926:21
callFunctionReturnFlushedQueue
    [native code]:0

```

