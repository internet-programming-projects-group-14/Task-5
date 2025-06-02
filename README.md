
## Vital Sign – Real-Time Network QoE Feedback Application

**Vital Sign** is a mobile application developed as part of the CEF440: Internet Programming (J2EE) and Mobile Programming course. The app allows users to provide real-time feedback on their network Quality of Experience (QoE), which is transmitted to their network providers to promote improved service accountability.

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Brand Identity](#brand-identity)
- [Screens and Figma Link](#screens-and-figma-link)
- [Technical Stack](#technical-stack)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [License](#license)

## About the Project

Vital Sign is designed to collect both subjective user feedback and objective network metrics, such as bandwidth, latency, jitter, and packet loss. It provides users and network providers with a structured, data-driven way to assess the real-time quality of network services.

## Features

- Real-time network data display (e.g., bandwidth, latency)
- Location-aware network context (e.g., area, carrier, network type)
- User feedback via rating and issue reporting interface
- Community analytics showing network trends based on crowdsourced data
- Speed test with download/upload speeds, latency, jitter, and packet loss
- Settings for privacy and notification management

## Brand Identity

### Visual Identity

| Element               | Hex Code / Style             | Description                                      |
|-----------------------|------------------------------|--------------------------------------------------|
| Background            | #1C1F2A                      | Dark blue-gray for professional tone             |
| Foreground Panels     | #2A2E3D                      | Slightly lighter shade for structure             |
| Highlight (Yellow)    | #FFD54F / #FFC107            | Used in rating systems and badges                |
| Active Status (Green) | #00C853 / #7ED957            | Indicates live monitoring or good connection     |
| Accent (Blue)         | #3FA9F5                      | Used for buttons and GPS data                    |
| Text                  | #FFFFFF (90–95% opacity)     | Ensures legibility                               |
| Borders/Containers    | White, low opacity           | For subtle section separation                    |

### Typography

- **Font Family**: Poppins (Regular and Bold)
- **Titles**: Bold, capitalized
- **Subtitles**: Medium/regular, left-aligned
- **Body Text**: Clean, legible at small sizes

### Iconography

- Minimalist, functional icons from Lucide React
- Used in buttons, indicators, and menus

### Layout

- Card-based design with rounded containers
- Uniform padding and spacing
- Interactive UI elements such as toggles, emoji feedback, and map-based analysis

## Screens and Figma Link

The UI was designed in Figma and implemented using React Native.

### Screens

- Home Screen (Live Network Metrics)
- Feedback Form
- Community Analytics
- Network Performance Trends
- Settings Page
- Speed Test

### Figma Link

-[Figma Design Reference](https://www.figma.com/design/faHGtiWW0cQx9CrZyWAw1i/InternetProgramming?node-id=34-2849&p=f&t=s8HZqLJ5TXQCuRjJ-0)

-[FrontEnd Source Code](https://github.com/internet-programming-projects-group-14/source-code)

## Technical Stack

| Component           | Tool/Technology     | Purpose                                         |
|---------------------|---------------------|-------------------------------------------------|
| Language            | JavaScript / TypeScript | Frontend logic and UI behavior               |
| Framework           | React Native         | Cross-platform mobile app development           |
| Development Tools   | Expo, VS Code        | App bundling, debugging, and previewing         |
| Icon Library        | Lucide React         | Modern, lightweight icons for UI                |

## Setup and Installation

### Prerequisites

- Node.js and npm
- Expo CLI (`npm install -g expo-cli`)
- A physical device with Expo Go or an emulator (Android Studio / Xcode)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/internet-programming-projects-group-14/source-code
````

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npx expo start
   ```

4. Scan the QR code with Expo Go or run it on an emulator.

## Usage

* Open the app to view real-time network metrics.
* Submit feedback by selecting ratings and context issues.
* Explore network trends and community insights.
* Perform a speed test to measure current network performance.
* Adjust privacy settings and notification preferences from the Settings screen.

This project was developed as part of the Internet Programming and Mobile Programming course (CEF440) under the supervision of Dr. Nkemeni V., Faculty of Engineering and Technology, Department of Computer Engineering, University of Buea.

