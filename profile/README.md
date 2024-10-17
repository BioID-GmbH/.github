# BWS 3 Samples <span style="color:#ee726b">NEW!</span>

![BWS 3 Samples Overview](https://github.com/BioID-GmbH/.github/blob/main/images/BWS3-Samples.png)

## Test the Powerful Biometric Functions of BioID with the Following Sample Code

<p>
First, a brief explanation of the above graphic. The sample code is divided into three categories (columns). The category "Client Apps" contains examples of mobile apps (iOS and Android). 
These implementations demonstrate the possibilities of capturing images on mobile devices.

In the "BWS Client" category, you can send these images from a mobile app to a server via REST API. To do this, the REST-gRPC forwarder server receives the REST call from the mobile app and sends it as a gRPC call to the BioID Web Service 3 (category).

### Mobile Apps
The iOS app BioIDCapture shows how to capture an image using the standard ImagePickerController for, e.g., Passive Liveness Detection. 
For Active Liveness Detection with/without a challenge-response mechanism, two images are always captured during a recording. 
There is an implementation for this that starts a recording and automatically returns two images, triggered by a movement of the user's head.

The sample code for the Android app is currently being developed and will be available soon.

### BWS Clients
The RestGrpcForwarder servers demonstrate how RESTful API calls can be accepted and forwarded as a gRPC call. These sample implementations are 
intended to show you how to interact with the BWS 3 gRPC endpoint using your company server. Available for ASP.NET Kestrel Server (C#) and Apache Tomcat Server (Java).

### BWSClient-WebApp 
his project is an ASP.NET server with dynamic web pages for Liveness Detection, Face Deepfake Detection, and PhotoVerify. This web app implements image capturing and sends the images as form data to its server. 
The server calls the BioID Web Service via gRPC.

### BWS Tools
To test the BioID Web Service 3 (BWS3), you can use the BWS-CLI. This BWS command-line interface can be used to easily test BWS 3 installations. 
The JWT tool is for creating JSON Web Tokens to authenticate with various BWS 3 services:
<ul>
<li>BWS Management API</li>
<li>BWS 3 Client</li>
</ul>

### BWS Scripting
Scripting is a quick way to try it out. You can test Liveness Detection, Video Liveness Detection, and PhotoVerify.


<div class="markdown-alert markdown-alert-note">
<p class="markdown-alert-title">
<svg class="octicon octicon-info mr-2" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8Zm8-6.5a6.5 6.5 0 1 0 0 13 6.5 6.5 0 0 0 0-13ZM6.5 7.75A.75.75 0 0 1 7.25 7h1a.75.75 0 0 1 .75.75v2.75h.25a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1 0-1.5h.25v-2h-.25a.75.75 0 0 1-.75-.75ZM8 6a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"></path></svg> Note</p>
<p>
Please note that all examples for the new BioID Web Service 3 are labeled BWS 3 in the repo description. 
The Classic BWS is the previous version of the BioID Web Service. The examples for this are marked with “Classic BWS” in the description. 
</p>
</div>


[bioidaccountregister]: https://account.bioid.com/Account/Register "Register a BioID account" 
[trial]: https://bwsportal.bioid.com/register "Register for a trial instance"
[bwsportal]: https://bwsportal.bioid.com "BWS Portal"
[liveness]: https://developer.bioid.com/bws/grpc/livenessdetection/ "Presentation attack detection."
[photoverify]: https://developer.bioid.com/bws/grpc/photoverify/ "PhotoVerify"
[videoliveness]: https://developer.bioid.com/bws/grpc/videolivenessdetection/ "Presentation attack detection in videos."
[playground]: https://playground.bioid.com "BioID Playground"
