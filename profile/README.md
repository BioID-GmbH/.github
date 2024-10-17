# BWS 3 Samples $${\color{#ee726b}NEW!}$$ 

![BWS 3 Samples Overview](https://github.com/BioID-GmbH/.github/blob/main/images/BWS3-Samples.png)

## Test the Powerful Biometric Functions of BioID with the Following Sample Code

First, a brief explanation of the above graphic. The sample code is divided into three categories (columns). The category "Client Apps" contains examples of mobile apps (iOS and Android). 
These implementations demonstrate the possibilities of capturing images on mobile devices.

In the "BWS Client" category, you can send these images from a mobile app to a server via REST API. To do this, the REST-gRPC forwarder server receives the REST call from the mobile app and sends it as a gRPC call to the BioID Web Service 3 (category).

### Mobile Apps
The [BioIDCapture iOS app][BioIDCapture-iOS] shows how to capture an image using the standard ImagePickerController for, e.g., Passive Liveness Detection. 
For Active Liveness Detection with/without a challenge-response mechanism, two images are always captured during a recording. 
There is an implementation for this that starts a recording and automatically returns two images, triggered by a movement of the user's head.

The sample code for the Android app is currently being developed and will be available soon.

### BWS Clients
The RestGrpcForwarder servers demonstrate how RESTful API calls can be accepted and forwarded as a gRPC call. These sample implementations are 
intended to show you how to interact with the BWS 3 gRPC endpoint using your company server. Available for [ASP.NET Kestrel Server (C#)][BWSClient-RestGrpc-CSharp] and [Apache Tomcat Server (Java)][BWSClient-RestGrpc-Java].

### [BWSClient-WebApp][BWSClient-WebApp] 
his project is an ASP.NET server with dynamic web pages for Liveness Detection, Face Deepfake Detection, and PhotoVerify. This web app implements image capturing and sends the images as form data to its server. 
The server calls the BioID Web Service via gRPC.

### [BWS Tools][BWSTools]
To test the BioID Web Service 3 (BWS3), you can use the BWS-CLI. This BWS command-line interface can be used to easily test BWS 3 installations. 

The JWT tool is for creating JSON Web Tokens to authenticate with various BWS 3 services:
* BWS Management API
* BWS 3 Client


### [BWS Scripting][BWSScripting]
Scripting is a quick way to try it out. You can test Liveness Detection, Video Liveness Detection, and PhotoVerify.


> ### NOTE
> 
> Please note that all examples for the new **BioID Web Service 3** are labeled **BWS 3** in the repo description. 
> The **Classic BWS** is the previous version of the BioID Web Service. The examples for this are marked with **Classic BWS** in the description. 


[BioIDCapture-iOS]: https://github.com/BioID-GmbH/BioIDCapture-iOS "Go to this Repo"
[BWSClient-WebApp]: https://github.com/BioID-GmbH/BWSClient-WebApp
[BWSClient-RestGrpc-CSharp]: https://github.com/BioID-GmbH/BWSClient-RestGrpc-CSharp
[BWSClient-RestGrpc-Java]: https://github.com/BioID-GmbH/BWSClient-RestGrpc-Java
[BWSTools]: https://github.com/BioID-GmbH/BWSTools
[BWSScripting]: https://github.com/BioID-GmbH/BWSScripting

[bioidaccountregister]: https://account.bioid.com/Account/Register "Register a BioID account" 
[trial]: https://bwsportal.bioid.com/register "Register for a trial instance"
[bwsportal]: https://bwsportal.bioid.com "BWS Portal"
[liveness]: https://developer.bioid.com/bws/grpc/livenessdetection/ "Presentation attack detection."
[photoverify]: https://developer.bioid.com/bws/grpc/photoverify/ "PhotoVerify"
[videoliveness]: https://developer.bioid.com/bws/grpc/videolivenessdetection/ "Presentation attack detection in videos."
[playground]: https://playground.bioid.com "BioID Playground"
