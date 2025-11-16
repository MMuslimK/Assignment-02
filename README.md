![DesktopView](https://github.com/user-attachments/assets/292c9b2a-73b8-4538-b1fd-b17a7b189f10)# Assignment-02
## Studymate: Your Personal Study Planner

This project is a responsive, single-page website for "Studymate," a fictional service that helps students create a smart study timetable. The site is built using only HTML5 and CSS3, with a focus on semantic structure, responsive design, and CSS-only interactivity.

**Live GitHub Pages Link:** [https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)

*(Replace the link above with your published GitHub Pages URL)*

---

### 1. Seed / Project Idea

The core idea (seed) is **"Studymate."** This isn't just a generic landing page; it's a tool. The website's main purpose is to guide a user to a "Study Plan Builder" form. This form collects information about the student's subjects, goals, and study challenges (like procrastination or time management) to (fictionally) generate a custom timetable. The entire design is built to support this single call-to-action.

---

### 2. Design Rationale

The design aims to be clean, encouraging, and professional to build trust with a student who might be feeling overwhelmed.

* **Layout (Grid + Flexbox):**
    * **CSS Grid** is used for the main page layout. This includes a 3-row grid (`header`, `main`, `footer`) to create a sticky footer. On desktop, the `main` element switches to a 2-column grid to place the hero/features on the left and the "smart form" on the right.
    * **CSS Flexbox** is used for all component-level layouts. This includes the header navigation, the feature cards, and all form groups (e.g., aligning labels and inputs, or custom radio/checkbox elements).

* **Color Palette:**
    * **Primary Blue (`--primary-color`):** Chosen to inspire trust, focus, and intelligence, which is fitting for an academic tool.
    * **Light Grey / White (`--bg-color`, `--surface-color`):** Used to create a clean, modern, and high-contrast background that makes text easy to read.
    * **Dark Grey (`--text-color`):** Used for body text instead of pure black, as it's softer on the eyes during extended reading.

* **Typography:**
    * **Inter (sans-serif):** This font was chosen for its excellent readability on screens at all sizes. It has a clean, modern, and neutral feel that is professional and un-distracting.

* **CSS-Only Interactivity:**
    1.  **Custom Form Elements:** Radio buttons and checkboxes are fully custom-styled using `appearance: none` and pseudo-elements to create a modern, consistent look that matches the site's theme.
    2.  **Focus States:** All interactive elements (links, buttons, inputs) have a clear, custom `outline` or `box-shadow` on `:focus-visible` for accessible keyboard navigation.
    3.  **Hover Transitions:** Buttons and feature cards have subtle `transform` and `box-shadow` transitions on `:hover` to provide visual feedback to the user.

---

### 3. Screenshots


#### Desktop View
![DesktopView](https://github.com/user-attachments/assets/2fd794b2-937c-498e-b476-0d1442c9e380)

#### Tablet View
<img width="1640" height="2360" alt="Tablet View" src="https://github.com/user-attachments/assets/ac17de25-5fb9-47c1-b7e4-05736de0b993" />


#### Mobile View (Showing the form)
<img width="1170" height="2532" alt="Phone view" src="https://github.com/user-attachments/assets/f3e91a59-c9cc-49dc-9ec0-aa00f62b9b81" />


---

### 4. Validator Proofs

*(To add proof: Take screenshots of the validator results and drag them here)*

#### HTML Validation (W3C)
[Screenshot of W3C HTML validator passing]

#### CSS Validation (W3C Jigsaw)
[Screenshot of W3C CSS validator passing]

