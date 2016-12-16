# ChromecastSender-Video

ChromecastSender-Video demo application shows how to cast single video from an android device.

Setup Instructions:-

1. Get a Chromecast device and set it up
2. Import the project into Android Studio or use gradle to build the project.
3. This sample includes a published app id in the res/values/strings.xml file so the project can be built and run without a need to register an app id. If you want to use your own receiver (which is required if you need to debug the receiver), update "app_id" in that file with your own app id.
4. In res/values/strings.xml, change video_url with your video and content_type with your video content type
5. Compile and deploy to your Android device.
