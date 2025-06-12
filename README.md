# Atiqlo Mobile Marketplace

A Flutter-based mobile marketplace application.

> **⚠️ This project is currently under development.**

A mobile application designed to empower Sri Lankan artisans by providing them with a dedicated platform to showcase and sell their handmade products directly to customers.

## 🎯 Project Overview

Atiqlo addresses the lack of digital market access for talented Sri Lankan handcrafters who remain isolated from online marketplaces. The app serves as a bridge between traditional artisans and modern e-commerce, enabling them to build virtual storefronts and connect directly with customers.

## ✨ Features

- User authentication
- Product management
- Shopping cart
- Order management
- Chat functionality
- Seller profiles

### For Sellers (Artisans)
- **Artisan Profiles**: Create detailed profiles with bio and contact information
- **Product Listing**: Upload products with images, descriptions, and pricing
- **Inventory Management**: Track stock levels with low-stock alerts
- **Order Management**: View, accept, cancel, and complete orders
- **Sales Analytics**: Basic reports on sales performance
- **Secure Chat**: Direct communication with potential buyers

### For Buyers
- **Product Discovery**: Browse products by categories with search and filter options
- **Wishlist**: Save favorite products for later purchase
- **Secure Payments**: Integrated Sri Lankan payment gateways (PayHere, Genie)
- **Order Tracking**: Monitor order status and delivery updates
- **Local Pickup**: Option to collect products directly from sellers
- **Reviews & Ratings**: Rate products and provide feedback

### General Features
- **Multi-language Support**: Sinhala, Tamil, and English
- **Real-time Notifications**: Alerts for messages, orders, and special offers
- **Discount System**: Promo codes and special offers
- **Local Delivery Support**: Optimized for Sri Lankan market

## 🛠️ Technical Stack

- **Frontend**: Flutter (Cross-platform - Android & iOS)
- **Backend**: Firebase
  - Firestore (Database)
  - Authentication (User Management)
  - Storage (Image hosting)
- **Image Management**: Cloudinary
- **Version Control**: Git & GitHub
- **Design**: Figma (UI/UX wireframes)

## 📱 Screenshots

The app includes comprehensive screens for:
- User authentication (Login/Signup)
- Home dashboard and marketplace
- Product pages and shopping cart
- Chat system and messaging
- Order management for both buyers and sellers
- User profiles and settings
- Payment processing

## 🏗️ System Architecture

The application follows a modern mobile architecture with:
- **Client-side**: Flutter mobile application
- **Cloud Backend**: Firebase services
- **Real-time Database**: Firestore for instant updates
- **Secure Authentication**: Firebase Auth
- **Media Storage**: Cloudinary integration

## 📋 Requirements Addressed

### Functional Requirements
- User registration and authentication
- Product listing and management
- Search and filtering capabilities
- Secure messaging system
- Order processing and tracking
- Payment integration
- Review and rating system

### Non-Functional Requirements
- **Usability**: Simple interface for all age groups
- **Performance**: Quick response times
- **Security**: Protected user data and payments
- **Compatibility**: Works on Android and iOS
- **Availability**: High uptime and reliability
- **Localization**: Multi-language support

## 🚀 Development Methodology

This project was developed using **Agile methodology** with:
- Sprint-based development cycles
- Iterative testing and feedback incorporation
- Team collaboration and continuous integration
- Regular performance evaluation and improvements

## 🎯 Problem Solved

### Before Atiqlo
- Limited visibility for artisan products
- Reliance on social media without proper selling tools
- Manual order and inventory tracking
- Lack of secure payment methods
- Communication barriers between buyers and sellers

### After Atiqlo
- Dedicated platform for handmade products
- Built-in inventory and order management
- Secure payment integration
- Direct buyer-seller communication
- Wider market reach for local artisans

## 🔧 Setup Instructions

1. Copy `firebase_options.template.dart` to `firebase_options.dart`
2. Fill in your Firebase configuration values from your Firebase Console
3. Create a `.env` file with your environment variables:
   - CLOUDINARY_CLOUD_NAME

## 💻 Installation & Development

1. Clone the repository
```bash
git clone https://github.com/deaneeth/artiqo-mobile-marketplace
cd artiqo-mobile-marketplace
```

2. Install Flutter dependencies
```bash
flutter pub get
```

3. Configure Firebase
   - Create a Firebase project
   - Add your `google-services.json` (Android) and `GoogleService-Info.plist` (iOS)
   - Set up Firestore security rules

4. Configure Cloudinary
   - Add your Cloudinary credentials to the configuration

5. Run the application
```bash
flutter run
```

## 🔮 Future Enhancements

- **Web Platform**: Flutter Web implementation for desktop users
- **International Shipping**: Global delivery integration
- **Advanced Analytics**: Detailed sales insights with charts and reports
- **Bulk Upload**: Multiple product upload functionality
- **In-app Wallet**: Points and credits system
- **AI Recommendations**: Personalized product suggestions
- **Third-party Logistics**: Courier service integration

## 🎓 Academic Context

This project was developed as part of the **Mobile App Development** coursework at University, demonstrating practical application of mobile development technologies and e-commerce solutions for local markets.

## 📄 License

This project was created for educational purposes as part of university coursework.
Refer [LICENSE](LICENSE)

## 🤝 Contributing

This is an academic project. For any questions or suggestions, please feel free to reach out.

---

**Note**: This application was specifically designed for the Sri Lankan market and includes local payment gateways and language support optimized for local users. 