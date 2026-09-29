# Digital Insights – Blog Website

A full-stack blog platform built for seamless content creation, reading, and management. This repository contains the application source code alongside comprehensive Quality Assurance (QA) documentation verifying frontend responsiveness, backend API logic, and overall system reliability.

## Project Overview

The core focus of this repository is ensuring high software quality, optimal UI/UX standards, and robust error handling across the **Digital Insights** application. The platform was evaluated through structured manual testing and API verification to ensure production readiness.

## Testing Scope & Key Responsibilities

### 1. Manual Functional & Responsiveness Testing

* **End-to-End Verification:** Executed manual test cases across key pages (Home, Article Details, Categories, Navigation) to ensure functional accuracy.
* **Cross-Device Responsiveness:** Tested layout adaptability, typography scaling, and UI alignment across desktop, tablet, and mobile viewports.

### 2. UI/UX Defect Reporting & Tracking

* **Defect Identification:** Spotted visual bugs, overlapping elements, broken links, and layout shifts during page renders.
* **Bug Documentation:** Created detailed bug reports including exact steps to reproduce (STR), environment details, expected vs. actual outcomes, and visual screenshot evidence.

### 3. Form Input Validation & Edge Case Handling

* **Boundary & Input Testing:** Evaluated input fields (search, forms, comment sections) using special characters, long strings, SQL/script injection attempts, and empty submissions.
* **Error State Handling:** Ensured informative, user-friendly error messages and clear inline alerts appear when invalid data is provided.

### 4. API & Backend Data Flow Verification

* **Endpoint Testing:** Validated RESTful API requests and responses for correct status codes (`200 OK`, `400 Bad Request`, `401 Unauthorized`, `404 Not Found`, etc.).
* **Data Flow Analysis:** Verified that database responses accurately map to UI elements without missing attributes or delayed updates.

## Tech Stack & Testing Tools

* **Frontend:** HTML5, CSS3, JavaScript / React
* **Backend:** Node.js, Express, REST APIs
* **Testing & Inspection Tools:** Chrome DevTools (Console, Network Tab, Device Mode), Postman
* **Version Control & Tracking:** Git, GitHub

## Getting Started

### Prerequisites

* [Node.js](https://nodejs.org/) (v16 or higher)
* `npm` or `yarn`

### Installation & Setup

1. **Clone the repository**

   Bash

   ```
   git clone https://github.com/PriyaMandal14/DIGITAL_INSIGHTS---Blog-Website.git
   cd DIGITAL_INSIGHTS---Blog-Website

   ```

2. **Install dependencies**

   Bash

   ```
   npm install
   # or
   yarn install

   ```

3. **Configure environment variables**

   Create a local `.env` file in the root directory (never commit this file to public repositories):

   Code snippet

   ```
   PORT=3000
   API_BASE_URL=http://localhost:5000

   ```

4. **Run the development server**

   Bash

   ```
   npm start
   # or
   yarn start
   ```
