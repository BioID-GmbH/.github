# Welcome to BioID on GitHub

## **About Us**
BioID is a leader in AI-powered biometric security solutions, offering state-of-the-art technologies like face recognition, liveness detection, and deepfake detection. Our solutions are tailored for identity verification, fraud prevention, and KYC (Know Your Customer) processes. With over 25 years of experience, we ensure privacy-friendly, secure, and user-centric technology for global applications.

## BWS 3 Samples $${\color{#ee726b}NEW!}$$ 

### **1. [BWSClient-WebApp][BWSClient-WebApp]**  
- **Description:** A demo web application showcasing biometric features like liveness detection, video liveness detection, and biometric verification of ID ownership (PhotoVerify).  
- **Technologies:** ASP.NET Core, gRPC, HTML5, CSS, JavaScript.  
- **Highlights:**  
  - Real-time liveness detection via webcam image data.
  - Protection against spoofing attacks in both presentation attacks (like 3D masks, video replays, projection etc.) and deepfakes.  
- **Use Cases:** Creation of web applications with integrated biometric functionality for capturing images and transmitting them to the server.  
- **Links:**  
  - [Repository][BWSClient-WebApp]
  - [Documentation][BWSClient-WebApp-ReadMe]

---

### **2. [BioIDCapture-iOS][BioIDCapture-iOS]**  
- **Description:** A native iOS application demonstrating passive and active liveness detection, challenge response and Photo ID verification.  
- **Technologies:** Objective-C.  
- **Highlights:**
  - Shows how to capture individual images for passive liveness detection or a sequence of images (image capture) for active liveness detection.
  - Features challenge-response mechanisms.  
- **Use Cases:** Build and test biometric applications for iOS/iPadOS and macOS devices.  
- **Links:**  
  - [Repository][BioIDCapture-iOS]
  - [Documentation][BioIDCapture-iOS-ReadMe]
- **Upcoming:** The sample code for the Android app is currently being developed and will be available soon.

---

### **3. [BWSTools][BWSTools]**  
- **Description:** A set of tools, including a command-line interface and JWT support, to efficiently interact with BioID Web Services (BWS 3).  
- **Technologies:** .NET, JWT, CLI, gRPC.
- **Highlights:**  
  - Fast integration and testing for developers.  
- **Use Cases:** Simplify backend integration of biometric services.  
- **Links:**  
  - [Repository][BWSTools]
  - [Documentation][BWSTools-ReadMe]

---

### **4. [BWSScripting][BWSScripting]**  
- **Description:** Scripting tools for quick tests of Liveness Detection, Video Liveness Detection and PhotoVerify.  
- **Technologies:** PowerShell, Shell scripting.  
- **Highlights:**   
  - Supports both active and passive liveness detection.
  - Supports video liveness detection.
- **Use Cases:** Fraud prevention in enterprise-scale workflows.  
- **Links:**  
  - [Repository][BWSScripting]
  - [Documentation][BWSScripting-ReadMe]

---

### **5. [BWSClient-RestGrpc-CSharp][BWSClient-RestGrpc-CSharp]**  
- **Description:** Demonstration of how RESTful API calls can be accepted and forwarded as gRPC messages to BioID Web Service (BWS 3).  
- **Technologies:** ASP.NET Core, REST, gRPC.  
- **Highlights:**  
  - Acts as a bridge between REST-based systems and BioID Web Services gRPC API.
  - Supports cross-platform environments (Windows, Linux, macOS).  
- **Use Cases:** Quickly connect REST-based systems to biometric services of BWS 3.  
- **Links:**  
  - [Repository][BWSClient-RestGrpc-CSharp]
  - [Documentation][BWSClient-RestGrpc-CSharp-ReadMe]

---

### **6. [BWSClient-RestGrpc-Java][BWSClient-RestGrpc-Java]**  
- **Description:** Demonstration of how RESTful API calls can be accepted and forwarded as gRPC messages to BioID Web Service (BWS 3).  
- **Technologies:** Java Spring Boot, REST, gRPC.  
- **Highlights:**  
  - Acts as a bridge between REST-based systems and BioID Web Services gRPC API.
  - Supports cross-platform environments (Windows, Linux, macOS).  
- **Use Cases:** Quickly connect REST-based systems to biometric services of BWS 3.
- **Links:**  
  - [Repository][BWSClient-RestGrpc-Java]  
  - [Documentation][BWSClient-RestGrpc-Java-ReadMe]

---

## BWS 3 Samples at a Glance

![BWS 3 Samples Overview](https://github.com/BioID-GmbH/.github/blob/main/images/BWS3-Samples.png)

A brief explanation of the above graphic. The sample code is divided into three categories (columns). The category "Client Apps" contains examples of mobile apps (iOS and Android). 
These implementations demonstrate the possibilities of capturing images on mobile devices.

In the "BWS Client" category, you can send these images from a mobile app to a server via RESTful API. To do this, the BWSClient Web Server receives the RESTful call from the mobile app and sends it as a gRPC call to the BioID Web Service 3 (category).

> ### NOTE
> 
> Please note that all examples for the new **BioID Web Service 3** are labeled **BWS 3** in the repo description. 
> The **Classic BWS** is the previous version of the BioID Web Service. The examples for this are marked with **Classic BWS** in the description.

---

## **Getting Started**
1. **Explore our Live Demo:** Visit the [BioID Playground][BioIDPlayground] to test our services in real-time.  
2. **Clone a Repository:** Download the source code and begin implementing our solutions.  
3. **Install Developer Tools:** Use environments like Visual Studio, .NET CLI, or Java Spring Boot to quickly start your projects.  

---

## **Why Choose BioID?**
- **Top-Level Security:** Protection against spoofing, deepfake attacks, and replay fraud.  
- **Cross-Platform Compatibility:** Runs on Windows, Linux, macOS, Android, and iOS.  
- **Privacy First:** GDPR-compliant with privacy-by-design principles.

---

## **Community & Support**
We value collaboration and contributions from the community!  
- **Need Help?** [Contact Support][BioIDSupport].  
- **Want to Contribute?** Submit pull requests or open issues in our repositories.  
- **Stay Updated:** Follow us on [LinkedIn][BioIDLinkedIn] and [Twitter][BioidTwitter].
- **Want more Information about BioID:** Visit our [company website][BioIDCompany]

[BWSClient-WebApp]: https://github.com/BioID-GmbH/BWSClient-WebApp
[BWSClient-WebApp-ReadMe]: https://github.com/bioid-gmbh/BWSClient-WebApp#readme

[BioIDCapture-iOS]: https://github.com/BioID-GmbH/BioIDCapture-iOS 
[BioIDCapture-iOS-ReadMe]: https://github.com/bioid-gmbh/BioIDCapture-iOS#readme

[BWSTools]: https://github.com/BioID-GmbH/BWSTools
[BWSTools-ReadMe]: https://github.com/BioID-GmbH/BWSTools#readme

[BWSScripting]: https://github.com/BioID-GmbH/BWSScripting
[BWSScripting-ReadMe]: https://github.com/BioID-GmbH/BWSScripting#readme

[BWSClient-RestGrpc-CSharp]: https://github.com/BioID-GmbH/BWSClient-RestGrpc-CSharp
[BWSClient-RestGrpc-CSharp-ReadMe]: https://github.com/BioID-GmbH/BWSClient-RestGrpc-CSharp#readme

[BWSClient-RestGrpc-Java]: https://github.com/BioID-GmbH/BWSClient-RestGrpc-Java
[BWSClient-RestGrpc-Java-ReadMe]: https://github.com/BioID-GmbH/BWSClient-RestGrpc-Java#readme


[BioIDCompany]: https://www.bioid.com 
[BioIDPlayground]: https://playground.bioid.com "See for yourself how good we are"
[BioIDLinkedIn]: https://www.linkedin.com/company/bioid-gmbh/ "What's new at BioID?"
[BioidTwitter]: https://twitter.com/BioID "What's new at BioID?"
[BioIDSupport]: mailto:support@bioid.com "We are happy to help you"


[liveness]: https://developer.bioid.com/bws/grpc/livenessdetection/ "Presentation attack detection."
[photoverify]: https://developer.bioid.com/bws/grpc/photoverify/ "PhotoVerify"
[videoliveness]: https://developer.bioid.com/bws/grpc/videolivenessdetection/ "Presentation attack detection in videos."
