  # SmartCycle: ML-Powered Recycling App

  An iOS app that gamifies sustainability by using machine learning to detect recyclable items and reward users with points for proper recycling habits.

  ## Overview

  SmartCycle combines computer vision and mobile technology to encourage recycling through real-time feedback and gamified rewards. Point your phone at a recycling bin and let our ML model identify what you're recycling—earn points and build sustainable habits.

  ## Features

  ### 🤖 ML-Powered Detection
  - **Real-time image classification** using Apple CoreML
  - **Custom-trained model** on thousands of recyclable items
  - **Fraud detection** built-in to prevent cheating (discriminates against water bottles)
  - Fast inference for instant feedback

  ### 🎮 Gamification
  - **Point rewards** for successfully recycling items
  - **Progress tracking** and sustainability metrics
  - **Achievement badges** for recycling milestones
  - Leaderboards to compete with friends

  ### 💾 Cloud Backend
  - **Firebase integration** for persistent user data
  - Real-time sync across devices
  - Secure authentication
  - User profiles and recycling history

  ### 📱 iOS Native
  - Built with **Swift** for optimal performance
  - Seamless CoreML integration
  - Camera access for instant detection
  - Native iOS UI/UX patterns

  ## Tech Stack

  **Frontend:**
  - Swift
  - UIKit
  - CoreML (Apple's ML framework)
  - AVFoundation (camera access)

  **Backend:**
  - Google Firebase (Realtime Database)
  - Firebase Authentication
  - Cloud Storage

  **ML/Training:**
  - Custom ML model trained on recyclable items dataset
  - ~95% accuracy on common recyclables
  - Anti-cheating logic for edge cases

  ## How It Works

  1. **Open the app** and point your camera at a recycling bin
  2. **Capture an image** of items you're recycling
  3. **ML model classifies** the recyclable material in real-time
  4. **Earn points** for proper recycling
  5. **Track progress** on your sustainability dashboard

  ## Key Technical Achievements

  ✅ **ML Anti-Fraud System**
  - Trained model to specifically discriminate against reusable water bottles
  - Prevents users from gaming the point system
  - Maintains integrity of recycling rewards

  ✅ **Real-time Processing**
  - CoreML inference optimized for mobile
  - <500ms detection latency
  - Efficient battery usage with background processing

  ✅ **Secure Data Persistence**
  - Firebase authentication with encrypted user data
  - Cloud-synced recycling history
  - Privacy-first design respecting user data

  ## Installation

  ```bash
  # Clone the repository
  git clone https://github.com/RyanJHamby/SmartCycle.git

  # Open in Xcode
  open SmartCycle.xcodeproj

  # Build and run on iOS 13+

  Requirements

  - iOS 13.0+
  - iPhone with rear camera
  - 50MB free storage

  Project Timeline

  May 2020 - Sept 2021

  Developed from concept through production, including:
  - ML model training and validation
  - iOS app development and UI/UX design
  - Firebase backend setup and integration
  - Testing and deployment to App Store

  Future Enhancements

  - AR visualization of recycling impact
  - Corporate partnership integrations
  - Donate points to environmental nonprofits
  - Multi-language support
  - iPad app version
  - Community recycling challenges

  Contributing

  Contributions welcome! Please feel free to submit issues or pull requests.

  License

  MIT License - See LICENSE file for details

  ---
  Built with ♻️ for a more sustainable future
