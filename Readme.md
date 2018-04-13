# Facebook SDK for Unity + Bitcode
 
## What

Original Facebook 7.11.1 (no modifications) with Bitcode support, because FB recently is breaking every single release. 

7.11 SDK couldn't compile at all on iOS, and their 7.11.1 hotfix broke Bitcode support, that many companies need.

This is fixed release, with no code modifications at all.  <b> It is safe to use. </b>

## Usage

All files are included in /Assets, or <b> .unitypackage </b> is in /Releases directory.

## I don't trust it, I want official release  

If you don't trust me, I can't blame you. You can do the fix yourself, following this steps:

1. Download FB for Unity: https://origincache.facebook.com/developers/resources/?id=facebook-unity-sdk-7.11.1.zip

2. Download FB for iOS: https://origincache.facebook.com/developers/resources/?id=FacebookSDKs-iOS-4.32.0.zip

3. Swap the <b>.framework</b> files from iOS SDK into Unity SDK.

4. Enjoy.

## More info about FB issues

You can see open issues on FB official GitHub:

https://github.com/facebook/facebook-sdk-for-unity/issues/143 
https://github.com/facebook/facebook-sdk-for-unity/issues/135
