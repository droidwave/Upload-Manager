# Upload Manager
## [Display Notification Progress Bar while Uploading](https://androidwave.com/upload-manager/)   

Upload Manager is complete solution for file uploading, with all actionable button. We will show the notification progress bar during file upload. During uploading some error occured and uploading failed due to network failure , We have RETRY and CANCEL action. Our intesion is Upload Manager works like Android Download Manager  

### Prerequisite
For achianing upload manage we have used bekow tech stack.
- Getting image from gallery and camera.  [References Article](https://androidwave.com/capture-image-from-camera-gallery/)
- JobIntentService for background jobs    [References Article](https://androidwave.com/working-with-jobintentservice/)
- Android imposed background imitations in Android Oreo [References Article](https://androidwave.com/background-limitations-android-oreo/)
- BroadcastReceiver

### Dataflow of upload manager will 
![DFD Upload Manager ](https://androidwave.com/wp-content/uploads/2019/04/upload-manager-1024x551.png)


## Implementation Step
- Create a new project and Add dependency in build.gradle
- Create Retrofit Client 
- Create JobIntentService for uploading
- Create a BroadcastReceiver that receive file progress
- Second BroadcastReceiver with Retry and Cancel action
- In MainActivity, We write code for getting the file from camera & gallery using FileProvider


**After following all the above step your app is ready to use, If you have any queries, feel free to ask them in the comment section below. Happy Coding :)**

### If you stuck somewhere follow this [References Article](https://androidwave.com/upload-manager/)

### [Watch Sample APP Video ](https://www.youtube.com/watch?v=JZIlB8qffag&feature=youtu.be)

