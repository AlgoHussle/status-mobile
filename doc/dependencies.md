## "@react-native-community/netinfo": "^4.4.0"

Updated from "^3.2.1". Used to monitor network information (connected, expensive, connection type).

## "bignumber.js": "git+https://github.com/status-im/bignumber.js.git#v4.0.2-status"

No changes. Used to work with big numbers in JS. BN.js (used in web3-utils) doesn't support decimals, though we could work without decimals.

## "buffer": "^5.4.2"

No changes. Required by bignumber.js otherwise there is a compilation error.

## "chance": "^1.1.0"

No changes. Used to generate guids and random values in `status-im.utils.random`.

## "create-react-class": "^15.6.2"

No changes. Internal react library, used by figwheel for instance but also probably react.

## "emojilib": "^2.4.0"

No changes. Used for emojis.

## "eth-phishing-detect": "^1.2.0"

Updated from "^1.1.13". Used to check if URL is known for phishing.

## "i18n-js": "^3.3.0"

No changes. Used to manage translations.

## "qrcode": "^1.4.1"

No changes. Used to generate QR code.

## "react": "18.0.0"

Updated from "16.8.3". React library, update based on react-native recommendation.

## "react-dom": "^16.4.2"

No changes. React library, update based on react-native recommendation.

## "react-native": "0.69.10"

Updated from "git+https://github.com/status-im/react-native.git#v0.59.10". React-native library.

## "react-native-background-timer": "^2.1.1"

No changes. Used to have setTimeout and setInterval that don't trigger yellow warning about long timeouts.

## "react-native-config": "^1.5.0"

Updated from "git+https://github.com/status-im/react-native-config.git#0.11.2-1". Used to fetch config values from env.

## "react-native-fetch-polyfill": "^1.1.2"

Updated from "^1.1.3". Used to be able to put a timeout on fetch request.

## "react-native-fs": "^2.14.1"

No changes. Used for some filesystem related functions, for instance to get no-backup directory in `status-im.utils.platform`.

## "react-native-gesture-handler": "2.6.1"

Updated from "1.3.0". Library used by react-navigation.

## "react-native-keychain": "git+https://github.com/status-im/react-native-keychain.git#v.3.0.0-5-status"

No changes. Used for storing password when user saves password.

## "react-native-languages": "^3.0.2"

No changes. Used to get user language and interact with i18n.js.

## "react-native-webview": "git+https://github.com/status-im/react-native-webview.git#v11.16.0-status"

Updated from "git+https://github.com/status-im/react-native-webview.git#v8.0.7_3". Used for browser.

## "react-navigation": "3.11.0"

No changes. Used for native navigation.

## "rn-emoji-keyboard": "0.7.0"

No changes. Used for taking emoji input## "react-native-draggable-flatlist": "^3.0.3"

Updated from "https://github.com/computerjazz/react-native-draggable-flatlist". A drag-and-drop-enabled FlatList component for React Native.

## "react-native-image-resizer": "^1.2.3"

Updated from "git+https://github.com/status-im/react-native-image-resizer.git#1.0.##-status". Used for profile picture.

## "react-native-image-crop-picker": "git+https://github.com/status-im/react-native-image-crop-picker.git#refs/tags/v0.36.2-status.0"

Updated from "^0.18.2". Used for profile picture.

## "react-native-reanimated": "2.11.0"

New addition. Provides a more comprehensive, low level abstraction for the Animated library API to be built on top of and can be used in parallel with the Animated library.

## "react-native-redash": "^16.0.11"

New addition. Utility library for React Native Gesture Handler and React Native Reanimated.

## "react-native-svg": "^9.8.4"

Updated from "9.7.1". Used for svg icons, mostly collectibles are using svg.

## "react-native-touch-id": "^4.4.1"

No changes. Used for touch-id identification.

## "react-native-background-timer": "^2.1.1"

No changes. Used to have setTimeout and setInterval that don't trigger yellow warning about long timeouts.

## "react-native-lottie-splash-screen": "^1.0.1"

No changes. Used to make splash screen with lottie animation during initial loading for android, also used as replacement of "react-native-splash-screen" for iOS.

## "react-native-status-keycard": "git+https://github.com/status-im/react-native-status-keycard.git#refs/tags/v2.5.39"

No changes. Used for keycard.

## "react-native-static-safe-area-insets": "^2.2.0"

New addition. A small library to help you get the correct safe area insets on iOS and Android.

## "react-native-transparent-video": "git+https://github.com/status-im/react-native-transparent-video.git#refs/tags/0.0.9"

New addition. A React Native module that allows you to play video with a transparent background.

## "react-native-async-storage/async-storage": "^1.17.9"

New addition. An asynchronous, unencrypted, persistent, key-value storage system for React Native.

## "react-native-blob-util": "^0.13.18"

New addition. A React Native module that allows you to use Blob object and File API in your React Native app.

## "react-native-camera-kit": "^13.0.0"

New addition. A high performance, easy to use, rock solid camera library for React Native apps.

## "react-native-clipboard": "^1.2.2"

New addition. A React Native module that allows you to use native UI to select media from the device library or directly from the camera.

## "react-native-community/hooks": "^3.0.0"

New addition. A collection of React Hooks for React Native.

## "react-native-community/masked-view": "^0.1.6"

New addition. A masked view is a view that clips (or masks) its children to a shape.

## "react-native-community/push-notification-ios": "^1.4.1"

New addition. A React Native module that allows you to use native Push Notifications.

## "react-native-community/slider": "^3.0.0"

New addition. A pure JavaScript <Slider> component for React Native.

#### "react-native-fast-image": "^8.5.11"

New addition. A performant replacement for React Native's Image component, including support for caching, placeholders, and more.

## "react-native-gesture-handler": "2.6.1"

Updated from "1.3.0". Provides native-driven gesture management APIs for building best possible touch-based experiences in React Native.

## "react-native-haptic-feedback": "^1.9.0"

New addition. A React Native module that allows you to trigger haptic feedback on iOS and Android.

## "react-native-hole-view": "git+https://github.com/status-im/react-native-hole-view.git#refs/tags/v2.1.3-status"

New addition. A React Native component that allows you to create views with a hole inside.

## "react-native-image-viewing": "git+https://github.com/status-im/react-native-image-viewing.git#refs/tags/v0.2.1.status"

New addition. A fullscreen image viewer for React Native.

## "react-native-linear-gradient": "^2.5.6"

New addition. A <LinearGradient> component for react-native, as seen in react-native-login.

## "react-native-navigation": "^7.27.1"

New addition. A complete native navigation solution for React Native.

## "react-native-orientation-locker": "^1.5.0"

New addition. A react native module that can lock/unlock the screen orientation.

## "react-native-permissions": "^2.1.5"

New addition. An unified permissions API for React Native on iOS and Android.

## "react-native-randombytes": "^3.6.1"

New addition. Native random bytes for React Native.

## "react-native-share": "^8.2.2"

New addition. Social share, sending simple data to other apps.

## "react-native-screens": "1.0.0-alpha.22"

Removed. Was used by react-navigation.

## "react-native-shake": "^3.3.1"

No changes. Used to send email to support when phone is shaked.

## "tdigest": "^0.1.1"

New addition. A new data structure for accurate on-line accumulation of rank-based statistics such as quantiles and trimmed means.

## "react-native-draggable-flatlist": "^3.0.3"

Updated from "https://github.com/computerjazz/react-native-draggable-flatlist". A drag-and-drop-enabled FlatList component for React Native.

## "rn-emoji-keyboard": "0.7.0"

No changes. Used for taking emoji input, for custom emoji thumbnails for community channels.

## "@walletconnect/client": "^2.0.0-beta.23"

New addition. WalletConnect is an open protocol for connecting Wallets to Dapps.

## "base-64": "^1.0.0"

New addition. This is a polyfill for the base64 encoding and decoding functions.

## "functional-red-black-tree": "^1.0.1"

New addition. A functional (immutable) red-black tree.

## "node-libs-react-native": "^1.2.1"

New addition. As of 0.18 React Native uses React as a npm dependency.

## "react-native-async-storage/async-storage": "^1.17.9"

New addition. An asynchronous, unencrypted, persistent, key-value storage system for React Native.

## "react-native-blob-util": "^0.13.18"

New addition. A React Native module that allows you to use Blob object and File API in your React Native app.

## "react-native-camera-kit": "^13.0.0"

New addition. A high performance,## "react-native-clipboard": "^1.2.2"

New addition. A clipboard API for React Native that supports both iOS and Android platforms for copying and pasting text.

## "react-native-community/hooks": "^3.0.0"

New addition. A collection of well-tested, commonly used React Hooks for React Native.

## "react-native-community/masked-view": "^0.1.6"

New addition. A masked view is a view that clips (or masks) its children to a shape.

## "react-native-community/push-notification-ios": "^1.4.1"

New addition. A React Native module that allows you to use native Push Notifications.

## "react-native-community/slider": "^3.0.0"

New addition. A pure JavaScript <Slider> component for React Native.

## "react-native-fast-image": "^8.5.11"

New addition. A performant replacement for React Native's Image component, including support for caching, placeholders, and more.

## "react-native-gesture-handler": "2.6.1"

Updated from "1.3.0". Library used by react-navigation.

## "react-native-haptic-feedback": "^1.9.0"

New addition. A React Native module that allows you to trigger haptic feedback on iOS and Android.

## "react-native-hole-view": "git+https://github.com/status-im/react-native-hole-view.git#refs/tags/v2.1.3-status"

New addition. A React Native component that allows you to create views with a hole inside.

## "react-native-image-viewing": "git+https://github.com/status-im/react-native-image-viewing.git#refs/tags/v0.2.1.status"

New addition. A fullscreen image viewer for React Native.

## "react-native-linear-gradient": "^2.5.6"

New addition. A <LinearGradient> component for react-native, as seen in react-native-login.

## "react-native-navigation": "^7.27.1"

New addition. A complete native navigation solution for React Native.

## "react-native-orientation-locker": "^1.5.0"

New addition. A react native module that can lock/unlock the screen orientation.

## "react-native-permissions": "^2.1.5"

New addition. An unified permissions API for React Native on iOS and Android.

## "react-native-randombytes": "^3.6.1"

New addition. Native random bytes for React Native.

## "react-native-share": "^8.2.2"

New addition. Social share, sending simple data to other apps.

## "react-native-static-safe-area-insets": "^2.2.0"

New addition. A small library to help you get the correct safe area insets on iOS and Android.

## "react-native-transparent-video": "git+https://github.com/status-im/react-native-transparent-video.git#refs/tags/0.0.9"

New addition. A React Native module that allows you to play video with a transparent background.

## "tdigest": "^0.1.1"

New addition. A new data structure for accurate on-line accumulation of rank-based statistics such as quantiles and trimmed means.

## "react-native-draggable-flatlist": "^3.0.3"

Updated from "https://github.com/computerjazz/react-native-draggable-flatlist". A drag-and-drop-enabled FlatList component for React Native.

## "rn-emoji-keyboard": "0.7.0"

No changes. Used for taking emoji input, for custom emoji thumbnails for community channels.

## "@walletconnect/client": "^2.0.0-beta.23"

New addition. WalletConnect is an open protocol for connecting Wallets toDapps.

## "base-64": "^1.0.0"

New addition. This is a polyfill for the base64 encoding and decoding functions.

## "functional-red-black-tree": "^1.0.1"

New addition. A functional (immutable) red-black tree.

## "node-libs-react-native": "^1.2.1"

New addition. As of 0.18 React Native uses React as a npm dependency.

## "react-native-async-storage/async-storage": "^1.17.9"

New addition. An asynchronous, unencrypted, persistent, key-value storage system for React Native.

## "react-native-blob-util": "^0.13.18"

New addition. A React Native module that allows you to use Blob object and File API in your React Native app.

## "react-native-camera-kit": "^13.0.0"

New addition. A high performance, easy to use, rock solid camera library for React Native apps.

## "react-native-clipboard": "^1.2.2"

New addition. A clipboard API for React Native that supports both iOS and Android platforms for copying and pasting text.

## "react-native-community/hooks": "^3.0.0"

New addition. A collection of well-tested, commonly used React Hooks for React Native.

## "react-native-community/masked-view": "^0.1.6"

New addition. A masked view is a view that clips (or masks) its children to a shape.

## "react-native-community/push-notification-ios": "^1.4.1"

New addition. A React Native module that allows you to use native Push Notifications.

## "react-native-community/slider": "^3.0.0"

New addition. A pure JavaScript <Slider> component for React Native.

## "react-native-fast-image": "^8.5.11"

New addition. A performant replacement for React Native's Image component, including support for caching, placeholders, and more.

## "react-native-gesture-handler": "2.6.1"

Updated from "1.3.0". Library used by react-navigation.

## "react-native-haptic-feedback": "^1.9.0"

New addition. A React Native module that allows you to trigger haptic feedback on iOS and Android.

## "react-native-hole-view": "git+https://github.com/status-im/react-native-hole-view.git#refs/tags/v2.1.3-status"

New addition. A React Native component that allows you to create views with a hole inside.

## "react-native-image-viewing": "git+https://github.com/status-im/react-native-image-viewing.git#refs/tags/v0.2.1.status"

New addition. A fullscreen image viewer for React Native.

## "react-native-linear-gradient": "^2.5.6"

New addition. A <LinearGradient> component for react-native, as seen in react-native-login.

## "react-native-navigation": "^7.27.1"

New addition. A complete native navigation solution for React Native.

## "react-native-orientation-locker": "^1.5.0"

New addition. A react native module that can lock/unlock the screen orientation.

## "react-native-permissions": "^2.1.5"

New addition. An unified permissions API for React Native on iOS and Android.

## "react-native-randombytes": "^3.6.1"

New addition. Native random bytes for React Native.

## "react-native-share": "^8.2.2"

New addition. Social share, sending simple data to other apps.

## "react-native-static-safe-area-insets": "^2.2.0"

New addition. A small library to help you get the correct safe areainsets on iOS and Android.

## "react-native-transparent-video": "git+https://github.com/status-im/react-native-transparent-video.git#refs/tags/0.0.9"

New addition. A React Native module that allows you to play video with a transparent background.

## "tdigest": "^0.1.1"

New addition. A new data structure for accurate on-line accumulation of rank-based statistics such as quantiles and trimmed means.

## "react-native-draggable-flatlist": "^3.0.3"

Updated from "https://github.com/computerjazz/react-native-draggable-flatlist". A drag-and-drop-enabled FlatList component for React Native.

## "rn-emoji-keyboard": "0.7.0"

No changes. Used for taking emoji input, for
