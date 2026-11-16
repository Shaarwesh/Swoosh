# 🚀 SWOOSH – Campus Convenience, Delivered

<p align="center">
  <strong>A Student-to-Student Campus Delivery Application</strong><br/>
  Making campus life easier, one delivery at a time.
</p>

## 📌 About the Project

**SWOOSH** is an Android-based campus delivery application developed to improve convenience and accessibility for students at **Universiti Teknikal Malaysia Melaka (UTeM)**.

The application introduces a student-to-student delivery ecosystem that connects students who need delivery assistance with fellow students who are willing to work as runners.

Instead of travelling to distant collection points or worrying about unattended food orders, students can use SWOOSH to request parcel collection, food pickup and delivery, and other campus convenience services.

Beyond convenience, SWOOSH also creates structured earning opportunities for student runners by providing a centralized platform to manage delivery requests, track earnings and interact with customers.

The project was developed collaboratively as part of **BITU 3923 – Workshop 2**, using an Agile development approach.

## 🎯 Problem Statement

University students frequently encounter difficulties accessing delivery services within campus environments.

Some of the major challenges identified during the project were:

- **Limited transportation:** Students without personal vehicles may need to travel significant distances to collect parcels from designated collection centres.
- **Inconvenient food collection:** Food orders are often left at campus guardhouses, increasing the possibility of misplaced or incorrectly collected orders.
- **Time constraints:** Academic schedules, assignments and examinations make it difficult for students to collect their deliveries.
- **Unstructured runner services:** Students offering delivery services often lack a centralized platform to organize requests, manage customers and track earnings.

SWOOSH addresses these challenges through a centralized campus delivery platform.

## ✨ Key Features

SWOOSH is organized into three main user roles and four major functional modules.

### 1. Customer Module

Designed for students who require delivery assistance.

- Customer registration and authentication.
- Account and profile management.
- Create parcel and food pickup requests.
- Provide pickup and delivery information.
- View delivery requests and track delivery progress.
- Receive runner and delivery status updates.
- Access delivery location information through map integration.
- Confirm completed deliveries.
- Rate runners and submit feedback.

### 2. Runner Module

Designed for students who want to earn additional income by providing delivery services.

- Runner registration and account management.
- Manage availability status.
- View available pickup requests.
- Accept delivery requests.
- Update pickup and delivery statuses.
- Track completed deliveries.
- Monitor runner earnings and delivery history.
- Receive relevant delivery notifications.

### 3. Administrator Module

Provides centralized management and monitoring capabilities.

- Manage user accounts and access permissions.
- Monitor transactions and delivery activities.
- Generate reports.
- Manage runner payments and revenue distribution.
- Handle disputes.
- Review customer feedback.
- Monitor overall system performance.

### 4. Revenue & Feedback Management

Supports the financial and service-quality aspects of the application.

- Calculate runner earnings.
- Manage revenue distribution.
- Track individual runner earnings.
- Collect customer ratings and feedback.
- Generate reports for administrative review.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Java | Android application development |
| Android Studio | Development environment and IDE |
| Firebase Authentication | User registration and authentication |
| Firebase Cloud Firestore | Cloud-based NoSQL database |
| Firebase Storage | Storage for user-uploaded files and images |
| Google Maps API | Map integration and delivery location visualization |
| Google Play Services Location | Location-related functionality |
| MPAndroidChart | Data visualization and charts |
| Gson | JSON serialization and parsing |
| OkHttp | HTTP networking |

### System Architecture

SWOOSH follows a client-cloud architecture.

- **Frontend:** Android application developed using Java in Android Studio.
- **Backend:** Firebase services for authentication, database operations and cloud storage.
- **Database:** Cloud Firestore for managing user profiles, delivery information, transactions and feedback.
- **External Services:** Google Maps and location services for location-related functionality.

The application uses Firebase to facilitate communication between its frontend and backend components, supporting data synchronization and centralized information management.

## 🧑‍💻 My Individual Contribution

### Role: Customer Module Developer

**My name is Shaarweshwary A/P Saravanan**, and I was primarily responsible for the development and quality assurance of the Customer Module.

My involvement extended across multiple stages of the Software Development Life Cycle (SDLC), from requirements analysis to system review.

#### 1. Requirements Analysis
- Identified and analysed the functional requirements of the Customer Module.
- Studied customer needs and translated them into application functionalities.
- Contributed to defining customer workflows and expected system behaviour.

#### 2. UI/UX & System Design
- Contributed to refining customer-facing interface layouts.
- Assisted in designing customer workflows and navigation.
- Reviewed interface usability to support a straightforward user experience.

#### 3. Application Development
- Implemented core functionalities of the Customer Module.
- Contributed to developing customer-facing features and workflows.
- Worked on integrating customer functionalities with the overall application.

#### 4. Testing & Debugging
- Conducted functional testing of Customer Module features.
- Verified customer-facing functionality against expected results.
- Identified and checked functionality issues to ensure the module operated as expected.

#### 5. Deployment & Integration
- Ensured proper deployment of the Customer Module.
- Supported the integration and deployment of customer-facing functionalities.
- Worked with the team to ensure compatibility with the overall application.

#### 6. System Review
- Reviewed Customer Module usability.
- Evaluated customer experience and application workflows.
- Identified potential improvements to enhance the overall user experience.

**My main responsibility was ensuring that the customer side of SWOOSH provided a functional and accessible experience for students requesting campus delivery services.**

## 🔄 Development Methodology

The project followed the **Agile Software Development Methodology**.

Agile was selected to support iterative development, continuous improvement and effective collaboration among team members.

The development process involved:

1. **Requirement Gathering** – Identifying user requirements and system objectives.
2. **System Design** – Planning application architecture, database structures and interfaces.
3. **Development** – Implementing application modules and integrating backend services.
4. **Testing** – Performing functional, unit and integration testing.
5. **Deployment** – Preparing and integrating the application for deployment.
6. **Review** – Evaluating functionality and identifying areas for improvement.

This iterative approach allowed the team to address development challenges and refine application features throughout the project.

## 🧪 Software Testing

Testing was conducted to evaluate the functionality, reliability and overall behaviour of the SWOOSH application.

The documented testing approaches included:

- **Unit Testing:** Verifying individual functionalities independently.
- **Integration Testing:** Checking interactions between different application modules.
- **Functional Testing:** Ensuring features behaved according to their requirements.
- **Acceptance Testing:** Evaluating whether the application met its intended objectives.

My assigned testing responsibilities focused specifically on the Customer Module.

## 📂 Project Structure

The repository contains the Android Studio project and its application module.

```text
Swoosh/
│
├── .idea/
│
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/
│   │       ├── res/
│   │       └── AndroidManifest.xml
│   │
│   └── build.gradle
│
├── gradle/
│
├── build.gradle
├── gradle.properties
├── gradlew
├── gradlew.bat
├── settings.gradle
│
└── README.md
```

## ⚙️ Getting Started

### Prerequisites

Before running the project, ensure you have:

- Android Studio installed.
- Android SDK configured.
- Java development environment compatible with the project.
- A Firebase project configured for the application.
- Google Maps API credentials if using map-related functionality.

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/Shaarwesh/Swoosh.git
```

**2. Open the project**

Open the cloned `Swoosh` folder using Android Studio.

**3. Configure Firebase**

- Create or select a Firebase project.
- Register the Android application using its application ID.
- Add the required `google-services.json` configuration file to the `app/` directory.
- Enable the Firebase services required by the application.

**4. Configure Google Maps**

Configure the required Google Maps API credentials and permissions for map-related functionality.

**5. Build and Run**

- Allow Android Studio to complete Gradle synchronization.
- Configure an Android emulator or connect an Android device.
- Build and run the application.

*Note: Firebase and Google Maps configuration credentials are environment-specific and should not be committed to a public repository.*

## 👥 Project Team

Developed collaboratively by Group 9 as part of BITU 3923 – Workshop 2.

| Team Member | Main Responsibility |
|---|---|
| Nizkia Silalahi | Project coordination and overall system integration |
| Shaarweshwary A/P Saravanan | Customer Module development |
| Sharifah Alysya Wafa | Customer Module development and testing |
| Noor Elyana Assyura | Runner Module tracking functionality |
| Sneha Seenivasan | Runner task assignment and communication |

**Project Supervisor:** Dr Abdul Karim Bin Mohamad

**Institution:** Universiti Teknikal Malaysia Melaka (UTeM)

## 📚 Key Learning Outcomes

Working on SWOOSH provided practical experience in:

- Android mobile application development using Java.
- Firebase integration and cloud-based database management.
- User authentication and application data management.
- Designing and implementing customer-facing functionalities.
- Understanding software architecture and system workflows.
- Software testing, debugging and integration.
- Applying Agile methodology and SDLC principles.
- Collaborative software development and task management.

## 🚀 Future Improvements

Potential enhancements that could further improve SWOOSH include:

- More advanced real-time delivery tracking.
- In-app communication between customers and runners.
- Improved runner assignment based on availability and proximity.
- Additional payment gateway integrations.
- Enhanced administrative analytics and reporting.
- Improved application security and performance.
- Wider deployment across university campuses.

## 📌 Project Information

| Category | Details |
|---|---|
| Project | SWOOSH – Campus Convenience, Delivered |
| Project Type | Academic Group Project |
| Course | BITU 3923 – Workshop 2 |
| Semester | Semester 1, Session 2024/2025 |
| Institution | Universiti Teknikal Malaysia Melaka |
| Platform | Android |
| Language | Java |
| Backend | Firebase |
| Methodology | Agile |
| My Role | Customer Module Developer |

---

<p align="center">
  <strong>SWOOSH – Campus Convenience, Delivered.</strong><br/>
  Making campus life easier, one pickup at a time. 🚀
</p>
