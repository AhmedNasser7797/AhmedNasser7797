Markdown# Hi, I'm Ahmed Nasser 👋
### Senior Flutter Engineer | Cross-Platform Systems & Clean Architecture

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmednasser7797/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:a.nasser9600@gmail.com)
[![Location](https://img.shields.io/badge/Alexandria%2C%20Egypt-grey?style=for-the-badge&logo=google-maps&logoColor=red)](#)

---

## 🚀 Technical Arsenal

Core Frameworks : Flutter, Dart, Android Native (Kotlin, Jetpack Compose)Architecture    : Clean Architecture, Feature-First, Dependency InjectionState Mgmt      : BLoC / Cubit, ProviderReal-Time & Sync: Pusher WebSockets, Firebase (Auth, Cloud Messaging, Firestore)CI/CD & DevOps  : Shorebird OTA, Codemagic, App Store Connect, Play ConsoleLocal Storage   : Hive, SQLite
---

## 📱 Featured Case Studies

### 1. 🎧 Rafeek — Cross-Platform Audio Tour Guide
> Location-aware walking companion with real-time landmark tracking and background media playback.

<p align="center">
  <!-- Replace with a GIF or device mockup of Rafeek -->
  <img src="https://via.placeholder.com/800x400.png?text=Rafeek+App+Demo+GIF+or+Screenshots" width="100%" alt="Rafeek Demo" />
</p>

* **Architecture:** Clean Architecture + BLoC.
* **Core Challenge:** Streaming audio without interruption while fetching dynamic points of interest via OpenStreetMap in low-connectivity areas.
* **Engineering Solution:** Built an offline caching layer that pre-fetches audio and guides while throttling GPS pings to preserve device battery life.
* **Live Links:** [Website](https://rafeek.app/) • *Available on Google Play & App Store*

```mermaid
graph LR
    A[OpenStreetMap Service] --> B(Location BLoC)
    B --> C{Geofence Match?}
    C -->|Yes| D[Audio Engine Handler]
    C -->|No| E[Idle Tracker]
    D --> F[Local Disk Cache / Stream]
2. 🏥 Bepharma — Enterprise Pharmaceutical CRMField-force automation tool for medical representatives with real-time synchronization.Impact: Refactored core legacy modules using Clean Architecture and BLoC, delivering a 70% increase in app performance and boosting field visit logging by 68%.Zero-Downtime Deployment: Integrated Shorebird OTA to deploy live hotfixes directly to field agents without waiting for app store reviews.Real-Time Layer: Integrated Pusher WebSockets for instant manager-rep synchronization.3. 🎓 Asquera — Three-Tier Educational EcosystemScaled cross-platform platform serving 3,000+ students, teachers, and parents in Egypt.Asquera Core (Student & Admin)Asquera Practice (Gamification)Asquera Parents (Monitoring)Secure video streaming & offline QR attendanceHigh-retention short-video reel feed & daily leaderboardsReal-time grade sync, billing, and attendance tracking(Clean Architecture, REST)(Reels Engine, Hive)(FCM, Background Sync)4. 💼 Finiex — Enterprise ERP Mobile ClientDigital conversion of a legacy desktop/web ERP suite into a mobile application.Reverse-Engineered Network Contracts: Mapped internal web requests to define clean, typed REST contracts.Client-Side Calculation Engine: Built an offline calculation system to handle real-time tax brackets, volume discounts, and instant point-of-sale (POS) invoice generation.Modules: Inventory, POS, Procurement, and Multi-role Access.📊 GitHub Analytics📬 Connect With MeLinkedIn: ahmednasser7797Email: a.nasser9600@gmail.com
