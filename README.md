# TodoAuthApp 🚀

A robust, full-stack mobile productivity application built with **React Native (Ignite)** and **Firebase**, designed with a focus on high-scale logic and data integrity.

## 🛠 Tech Stack
- **Framework:** React Native / Expo
- **State:** Redux Toolkit (Thunks & Slices)
- **Auth:** Firebase Authentication
- **Type Safety:** TypeScript
- **Styling:** Ignite Theme System

## 🧠 Key Features & Logic
### 1. Mixed Sorting Algorithm
Unlike standard lists, this app uses a custom weighted formula to calculate task urgency:
`Score = (PriorityWeight * 10) - (HoursUntilDeadline)`
This ensures that high-priority tasks move up as their deadlines approach, satisfying the "fault-tolerant" logic required for complex systems.

### 2. Robust State Management
- Utilizes **Redux Toolkit** to handle task persistence and completion status.
- Implements strict **TypeScript interfaces** to prevent state leakage and ensure predictable UI behavior.

### 3. Production Standards
- Zero-semicolon code style enforced by **ESLint**.
- Themed color management to eliminate hardcoded literals and ensure UI consistency.

## 🚀 How to Run
1. Clone the repo.
2. Run `yarn install`.
3. Run `cd ios && pod install` (for Mac users).
4. Run `npx expo run:ios`.
