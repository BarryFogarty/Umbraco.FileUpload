# Umbraco.SimpleFileUpload
A simple Umbraco Angular app to handle file uploads.  Can be used as a dashboard control or as a starting point for a custom package / property editor.

## Instructions
- Clone the repo
- Copy the App_Plugins/SimpleFileUpload folder into your Umbraco project
- Copy FileUploadApiController.cs to your Umbraco project.  Amend the namespace and compile
- Add a dashboard control pointed at ../App_Plugins/SimpleFileUpload/app.html

Inspired by the discussion at https://our.umbraco.org/forum/developers/extending-umbraco/63947-Uploading-files-to-server-wAngularJS-API-service-and-Umbraco-API-controller

Props:  Kyle Weems (csssquirel)
https://gist.github.com/cssquirrel/3e5daad14bd2ff40edcc
