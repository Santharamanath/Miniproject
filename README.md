## Title of the Project
TryNbuy: Augmented Reality E-commerce Platform with Live Product Visualization
The integration of Augmented Reality (AR) within an e-commerce platform, aimed at enhancing the online shopping experience by allowing users to visualize products in their real-world environment before purchase

## About
TryNbuy is an innovative e-commerce project designed to integrate cutting-edge Augmented Reality technology to transform traditional online shopping. Conventional online shopping often suffers from a lack of tangible interaction, making it difficult for customers to accurately gauge product size, fit, and appearance in their own spaces. This project seeks to overcome these challenges by providing an intuitive AR interface. It allows users to place virtual 3D models of products (like shoes, glasses, or furniture) directly into their physical environment using their smartphone camera, enabling them to "try before they buy" and make more informed purchase decisions. This significantly improves customer confidence and reduces returns, offering a more immersive and engaging shopping experience.

## Features
Real-time AR Product Visualization: Seamlessly overlay 3D product models onto the user's live camera feed, anchored to real-world surfaces.

Intuitive 3D Model Interaction: Users can easily rotate, scale, and reposition virtual products within their physical space using touch gestures.

Comprehensive Product Catalog: A robust e-commerce backend to manage diverse product categories (e.g., Dresses, Glasses, Shoes) with detailed specifications.

Seamless E-commerce Flow: Integrated shopping cart, secure checkout process, and user profile management.

Optimized Performance: Efficient loading and rendering of high-quality 3D models on mobile devices.

High Scalability: Designed to handle a growing product catalog and increasing user base.

User Authentication & Authorization: Secure login/registration for personalized experiences.

## Requirements
Operating System:

Client (Mobile): iOS (13.0+) for ARKit compatibility, Android (8.0+) for ARCore compatibility.

Server: Linux (Ubuntu 20.04+ recommended) or Windows Server for backend deployment.

Development Environment:

Backend: Python 3.8+ (with Django/Flask) or Node.js (with Express.js) for API development.

Frontend (Web): HTML5, CSS3, JavaScript (React/Vue/Angular).

Frontend (Mobile): Swift/Kotlin for native AR development, or React Native/Flutter with AR extensions.

AR Frameworks: ARKit (for iOS) and ARCore (for Android) are essential for AR capabilities.

3D Libraries/Engines: Three.js / Babylon.js (for WebAR), SceneKit (for iOS), Filament (for Android) for 3D model rendering.

Database: PostgreSQL or MongoDB for product catalog, user data, and orders.

Cloud Storage: AWS S3, Google Cloud Storage, or Cloudinary for efficient storage and delivery of 3D models and product images.

Version Control: Git for collaborative development and code management.

IDE: VSCode, Xcode (for iOS), Android Studio (for Android) for coding, debugging, and deployment.

Additional Dependencies:

Backend: ORM libraries, payment gateway SDKs, authentication libraries.

Frontend: UI component libraries, state management libraries.

AR: Libraries for GLTF/USDZ loading, texture compression.

## System Architecture
Client Tier: Mobile Application (iOS/Android) or Web Application. Handles UI, user interaction, and leverages native AR frameworks.

Server Tier: Application Backend (Microservices/API Gateway). Manages user authentication, product catalog, shopping cart, order processing, and payment integration.

Database: Stores user profiles, product details (SKUs, metadata), and order information.

3D Asset Storage: Dedicated cloud storage for optimized 3D models and textures.

External Services: Payment Gateway, Email/SMS Notification Services.

AR Engine OS: Native AR frameworks (ARKit/ARCore) running on the mobile device, handling SLAM, surface detection, and motion tracking.

<img width="1024" height="683" alt="image" src="https://github.com/user-attachments/assets/efa9286d-0a6b-4f7d-85b3-2c07f09335fe" />



## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Login page

<img width="1024" height="535" alt="image" src="https://github.com/user-attachments/assets/2f7bfbea-a150-4b79-b673-d4350e3cffc8" />


#### Output2 - Profile Page

<img width="1024" height="535" alt="image" src="https://github.com/user-attachments/assets/ee55d745-f83f-45ed-b6dd-7d6d0e40e938" />


#### Output1 - Collection page

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/ebe1967e-31ed-42bd-b3b1-cac02d985811" />




## Results and Impact
The AR-Enhanced Virtual Try-On Web Application successfully demonstrates the integration of Augmented Reality with modern web technologies to improve online product visualization and enhance the customer shopping experience. The system enables users to virtually try on eyewear in real time using a browser-based environment, eliminating the need for physical trials or separate mobile applications. By incorporating MediaPipe for accurate facial landmark detection and Three.js for 3D rendering, the project achieves smooth alignment and natural display of virtual products on the user’s face.

## Articles published / References
[1] S. Thapa, A. Shah, and R. Joshi, “Real-Time Web-Based AR Eyewear Try-On Using Face Classification,” 2025.

[2] A. Siregar et al., “Influence of Augmented Reality on Consumer Purchase Intention in Fashion E-Commerce,” 2023.

[3] P. Rana and J. Kim, “Virtual Try-On Using Personalized Avatars in AR and VR,” MDPI Journal, 2020.

[4] L. Zhang, Y. Chen, and W. Zhao, “Deep Learning-Based AR Recommendation System for Retail Applications,” 2024.



