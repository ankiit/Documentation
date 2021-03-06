
---
title: Release Notes
description: 
platform: Unity
updatedAt: Mon May 25 2020 07:55:12 GMT+0800 (CST)
---
# Release Notes
This page provides the release notes for the Agora Unity SDK.

## Overview

The Agora Unity SDK supports the following scenarios:

-   Voice Communication
-   Live Voice Broadcast

For the key features included in each scenario, see [Voice Overview](https://docs.agora.io/en/Voice/product_voice?platform=All%20Platforms) and [Audio Broadcast Overview](https://docs.agora.io/en/Audio%20Broadcast/product_live_audio?platform=All_Platforms).

## v2.9.2

v2.9.2 is released on Feb 17, 2020.

- This release fixed some abnormal behaviors on Android devices.
- This release fixed the stuck behavior of using the Editor debug mode on Windows platform.

## v2.9.1

Agora Unity SDK is widely used in games, education, AR, VR and other scenarios.

v2.9.1 was released on December 23, 2019.

**Functions and features**

#### 1. Multi-platform support
Supports iOS, Android, macOS and Windows (x86/x86_64) platforms.

#### 2. Interoperability with the Agora Web SDK
Provides the `EnableWebSdkInteroperability` method for enabling interoperability with the Agora Web SDK in a live broadcast. 

#### 3. Raw data
Supports raw audio data. You can capture and process the raw data according to your needs.

#### 4. External data source
Provides APIs for accessing to the external data source. You can configure the external audio source, and push the data to the Agora Unity SDK.

#### 5. Encryption
Supports encryption of audio streaming. The following table shows the information of the encryption libraries for the Android and iOS platforms. If you do not intend to use this function, you can remove the encryption libraries to decrease the SDK size.

   | Platform | Encryption libraries                          |
   | :------- | :-------------------------------------------- |
   | Android  | libagora-crypto.so                            |
   | iOS      | <ul><li>AgoraRtcCryptoLoader.framework <li>libcrypto.a</li></ul> |

#### 6. Cloud proxy

Supports the cloud proxy service. See [Use Cloud Proxy](../../en/Audio%20Broadcast/cloudproxy_unity.md) for details.

**Related documentation**

See the following documentation to quickly integrate the SDK and implement real-time voice and video communication in your project.

- [Start a Voice Call](../../en/Audio%20Broadcast/start_call_audio_unity.md) or [Start a Voice Broadcast](../../en/Audio%20Broadcast/start_live_audio_unity.md)
- [API Reference](https://docs.agora.io/en/Audio%20Broadcast/API%20Reference/unity/index.html) 

Agora also provides an open-source [Unity Sample](https://github.com/AgoraIO/Agora-Unity-Quickstart/tree/master/audio/Hello-Unity3D-Agora) on GitHub.
