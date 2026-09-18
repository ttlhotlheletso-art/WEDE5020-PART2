# Youth Empowerment Website – Part 2

## Student details
- **Student:** Tlhotlheletso Makodi
- **Student number:** ST10517484
- **Subject:** Web Development
- **Group:** 03
- **Project:** Youth Empowerment Website
- **Part:** 2 – Designing the Visuals: CSS Styling and Responsive Design

## 1. Overview

Part 1 gave the project its basic HTML structure and five pages. For Part 2, I kept the same Youth Empowerment idea and improved the website mainly through CSS. I wanted the pages to feel cleaner and easier to use without making the design too complicated.

The original proposal uses white, brown and black as the main colours. I kept that idea because it gives the website a simple and professional look while still feeling warm and suitable for a youth-focused organisation.

## 2. Changes made from Part 1

The following changes were made after reviewing the Part 1 website:

- Added one external stylesheet called `style.css` and linked it to all five pages.
- Improved the navigation bar and added a clear active-page state.
- Added consistent spacing, typography, buttons, cards and form styling.
- Improved the page banner and image presentation.
- Used CSS Grid for programme, information and image sections.
- Added a desktop-first layout and responsive breakpoints for tablets and mobile phones.
- Used relative sizing such as `rem`, `%`, `min()`, `clamp()` and flexible grid columns.
- Added visible keyboard focus styles and a skip-to-content link to improve accessibility.
- Kept the donation form as a front-end demonstration because the project does not connect to a real payment gateway.
- Reworded some content so that it reads more naturally and does not make unsupported claims about real programme results or partnerships.
- Kept the five-page structure from Part 1: Home, About, Programmes, Donate and Contact.

## 3. CSS styling decisions

### 3.1 Colour scheme
The main colours are white, brown and black, following the original proposal. Brown is mainly used for navigation, headings, buttons and highlighted areas. White keeps the pages open and clean, while dark text makes the content easy to read.

### 3.2 Typography
The website uses a simple system font stack (`Segoe UI`, Arial, sans-serif). Headings are larger and use stronger weights so that visitors can scan the page easily. The `clamp()` function is used for the main heading so that it can adjust between larger and smaller screens.

### 3.3 Layout
CSS Grid is used for the cards, gallery and project statistics. On a desktop screen these sections can display several columns. At the tablet breakpoint they reduce to fewer columns, and on mobile they become a single-column layout.

### 3.4 Forms
The donation and contact forms use consistent labels, borders, spacing and buttons. The form fields use a full available width so they are easier to use on smaller screens.

## 4. Responsive design

Three main screen ranges were considered:

- **Desktop:** wider than 900px. Multi-column layouts are used where there is enough space.
- **Tablet:** 601px–900px. Navigation and content columns become more compact.
- **Mobile:** 600px and below. Cards, statistics and image sections become single-column, and spacing is reduced.

The images use `max-width: 100%` and flexible sizing so they do not overflow their containers.

## 5. Testing and iteration

The website was checked at desktop, tablet and mobile viewport sizes. The screenshots in the `screenshots` folder provide evidence of the responsive layout.

During the CSS work I checked:

- Navigation wrapping on smaller screens.
- Text readability and heading sizes.
- Image scaling.
- Card and gallery columns.
- Form widths.
- Button visibility and spacing.
- Keyboard focus visibility.
- Horizontal overflow on mobile layouts.

## 6. Changelog

### Part 2 – September 2026
- Added external `style.css`.
- Linked the stylesheet to all five HTML pages.
- Redesigned navigation, hero area, cards, galleries, statistics and forms.
- Added desktop, tablet and mobile media queries.
- Added responsive typography and image sizing.
- Added accessibility improvements including skip navigation and focus states.
- Updated page wording to sound more natural and consistent with the original proposal.
- Added responsive testing screenshots.
- Updated this README with Part 2 changes and references.

## 7. References

Department of Basic Education. (n.d.). *Youth Citizen Action Programme*. South African Government. https://www.education.gov.za/

Government Communication and Information System (GCIS). (n.d.). *Youth and learning opportunities*. South African Government. https://www.gov.za/

National Youth Development Agency (NYDA). (n.d.). *National Youth Service*. NYDA. https://www.nyda.gov.za/

UNICEF South Africa. (n.d.). *Adolescent and youth development*. UNICEF South Africa. https://www.unicef.org/southafrica/

WordPress.org. (2026). *Documentation*. WordPress.org. https://wordpress.org/documentation/

The sources above were used as background information for the project. They are not presented as confirmed partners of Youth Empowerment.

## 8. Folder structure

```text
Youth_Empowerment_Part2/
│
├── index.html
├── about.html
├── programs.html
├── donate.html
├── contact.html
├── style.css
├── README.md
│
├── assets/
│   ├── Website_Project_Proposal.docx
│   └── website images
│
└── screenshots/
    ├── desktop-home.png
    ├── tablet-home.png
    └── mobile-home.png
```

## 9. How to open the project

Open the folder in Visual Studio Code and open `index.html` in a browser. The other pages can be opened through the navigation menu.

This version is intentionally a front-end student project. It does not process real donations or store form submissions.
