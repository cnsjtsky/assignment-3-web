Assignment #3: Responsive Web Design

Name: Daniyar Abdusadykov  
Group: IT-2504  

Overview

This project is a single-page responsive web layout created for Assignment #3. It covers CSS3 media queries, fluid typography, flexbox adjustments, and Bootstrap 5's 12-column grid system.



 Project Structure

├── index.html           Main HTML structure
├── style.css            Custom CSS rules and media queries
├── screenshots/         Task screenshots for the report
<img width="1904" height="1025" alt="image" src="https://github.com/user-attachments/assets/a58bce9d-8926-46b9-8c66-87f28fd4133b" />
<img width="1775" height="266" alt="image" src="https://github.com/user-attachments/assets/bccd1a6c-fdb7-4199-b32c-9394f540bc3f" />
<img width="1700" height="396" alt="image" src="https://github.com/user-attachments/assets/83354455-5c2b-4ce7-8b0b-c659d2a7368f" />
<img width="1699" height="328" alt="image" src="https://github.com/user-attachments/assets/cefdb35c-b991-4797-a72d-2df6211b4884" />


Tasks 
Task 0. Responsive Typography
Implemented breakpoint-based heading and text sizes using CSS media queries (@media (min-width: 768px) and @media (min-width: 1024px)). Font sizes scale smoothly from mobile viewports up to desktop screens.

Task 1. Responsive Layout with Media Queries
Created a 3-box card row using pure CSS Flexbox without any external frameworks.

Desktop: 3 cards side-by-side (calc(33.333% - 0.67rem)).

Tablet: 2 cards on the top row, 1 full-width card on the bottom.

Mobile: All 3 cards stacked vertically.

Task 2. Bootstrap Responsive Columns
Built a responsive 3-column section using Bootstrap's 12-column grid system (col-12 col-md-6 col-lg-4).

Spans 12 columns on mobile screens.

Expands to 6 columns on tablet viewports.

Equal 4-column distribution on desktop screens

Task 3. Bootstrap Navigation Bar
Integrated a responsive Bootstrap navigation bar featuring brand text, desktop links, and a collapsible hamburger menu toggle button for mobile screens

Task 4. Responsive Portfolio Page
Combined custom CSS and Bootstrap grid utilities to build a structured portfolio section

Main Content Area (8 columns): Displays project cards in a 2x2 grid on desktop screens

Sidebar Area (4 columns): Displays student information, academic details, and links On desktop viewports, the sidebar uses sticky positioning (sticky-lg-top)


