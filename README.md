# Skillora Freelancing Marketplace – Week 5

A responsive and interactive freelancing marketplace developed using **HTML5, CSS3, and JavaScript** as part of my internship project. Week 5 focuses on connecting the existing marketplace functionality with a project management and order tracking system.

---

## 📌 Project Overview

Week 5 extends the existing Skillora Freelancing Marketplace by introducing a dedicated **My Orders dashboard**. It connects the proposal acceptance workflow to project tracking, allowing accepted proposals to become projects that can be viewed from the orders page.

The objective was to make the platform more connected and practical by building on the functionality developed in the previous weeks rather than creating a separate, disconnected project.

## ✨ Features Implemented in Week 5

- **My Orders Dashboard:** A dedicated page for viewing projects and their current statuses.
- **Proposal Acceptance:** Clients can accept pending proposals from the proposals page.
- **Proposal-to-Project Integration:** Accepting a proposal creates a corresponding project in the orders dashboard.
- **Project Status Tracking:** Projects display their current status, including in-progress, submitted, and completed states where applicable.
- **Order Statistics:** Summary cards display project counts and project value information.
- **Search Functionality:** Search through projects using the dashboard search field.
- **Status Filtering:** Filter projects according to their current status.
- **Role Filtering:** Filter projects by client or freelancer role.
- **Local Storage Integration:** Project and proposal information is stored in the browser using the Local Storage API.
- **Duplicate Prevention:** The acceptance workflow checks whether a project has already been created for a proposal.
- **Responsive Design:** The dashboard layout adapts to different screen sizes.
- **Navigation Integration:** The My Orders page is accessible through the homepage navigation.

## 🔗 Integration with Previous Weeks

Week 5 builds on the functionality developed in Weeks 1–4:

1. Users browse the existing freelancing marketplace.
2. Freelancers submit proposals for available jobs.
3. Clients review proposals on the proposals page.
4. Clients accept a pending proposal.
5. The accepted proposal is saved as a project in Local Storage.
6. The project appears in the My Orders dashboard.

This workflow connects the proposal submission and acceptance process with the new project management functionality.

## 🛠️ Technologies Used

- **HTML5** – Page structure and content
- **CSS3** – Styling, layout, and responsive design
- **JavaScript (Vanilla JS)** – Interactive functionality and application logic
- **Local Storage API** – Client-side storage of proposals and projects
- **Font Awesome** – Icons used throughout the existing marketplace, where included
- **Google Fonts** – Typography used throughout the existing marketplace, where included

## 📂 Main Week 5 Files

| File | Purpose |
|---|---|
| `orders.html` | Displays the My Orders dashboard |
| `week5.css` | Contains the styling for the Week 5 dashboard |
| `week5.js` | Handles dashboard rendering, project statistics, searching, and filtering |
| `script.js` | Connects proposal acceptance to project creation and supports existing marketplace functionality |

## 🚀 How to Run the Project

1. Download or clone the project repository.
2. Open the project folder in Visual Studio Code.
3. Ensure the Week 5 files are in the correct folder alongside the existing project files.
4. Open `index.html` using the **Live Server** extension.
5. Navigate to the proposals page and submit a proposal if required.
6. Accept a pending proposal to create a project.
7. Click **My Orders** in the navigation bar to open the orders dashboard.
8. Use the search field and filters to explore the available projects.

**Note:** The proposal and project data is stored in the browser's Local Storage. For the best results, use the same browser and development origin when testing the different pages.

## 🧪 Testing Checklist

- [x] Week 5 dashboard opens successfully.
- [x] Project cards and dashboard statistics are displayed.
- [x] Search and filters are available.
- [x] Pending proposals display an Accept Proposal button.
- [x] Accepting a proposal creates a project in Local Storage.
- [x] The accepted proposal's status is updated.
- [x] The My Orders page can be opened from the homepage navigation.
- [x] Existing sample projects remain available in the dashboard.

## 🔮 Future Improvements

- User-specific client and freelancer accounts
- Backend database integration
- Real project deadlines and milestone management
- Freelancer progress updates and delivery submissions
- Client delivery approval and revision requests
- Notifications for proposal and project status changes
- Secure authentication and authorization
- Real payment and transaction integration

## ⚠️ Current Limitations

This version is a frontend demonstration. Data is stored locally in the browser, and client/freelancer names used in the Week 5 integration are placeholders. A backend and database would be required for shared data between different users and devices, secure access control, and production-ready project management.

## 🎯 Learning Outcomes

Through Week 5, I practiced:

- Integrating new features into an existing multi-page project
- Connecting proposal workflows with project management
- Using JavaScript event delegation
- Managing application data with Local Storage
- Rendering dynamic project cards
- Implementing search and filtering
- Maintaining existing functionality while extending a project
- Testing navigation and cross-page data persistence

---

**Project:** Skillora Freelancing Marketplace  
**Task:** Internship Week 5  
**Technologies:** HTML5, CSS3, JavaScript, Local Storage API

