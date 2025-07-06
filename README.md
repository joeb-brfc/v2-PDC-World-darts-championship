# v2-PDC-World-Darts-Championship

This web project is a responsive, Bootstrap-powered tribute to the PDC World Darts Championship. It aims to educate, entertain, and celebrate the evolution of the competition, legendary players, and its cultural impact.

## 💡 Purpose & Value

The website is designed for darts fans, new audiences, and sports history enthusiasts. It delivers value by:

- Centralising champion stats, career highlights, and venue information in one engaging interface
- Showcasing multimedia content (images, embedded video) to enhance learning and engagement
- Celebrating diversity and modern progress in darts (e.g. Fallon Sherrock and Lisa Ashton)
- Offering a mobile-friendly, accessible browsing experience using Bootstrap 5 and alt-tagged images

## 🌐 Deployment Instructions

- **Live Website:** [https://joeb-brfc.github.io/v2-PDC-World-darts-championship/](https://joeb-brfc.github.io/v2-PDC-World-darts-championship/)
- **GitHub Repository:** [https://github.com/joeb-brfc/v2-PDC-World-darts-championship](https://github.com/joeb-brfc/v2-PDC-World-darts-championship)

### 🔧 Running the site locally:
1. Clone the repository or download it as a ZIP.
2. Extract the files if downloaded.
3. Open `index.html` in your preferred browser.
4. No build tools or installations are required — this is a fully static project.

## 👥 Detailed User Stories

### 🧭 First-Time Visitor

**User Story:**  
As a First-Time Visitor, I need easy navigation and a user-friendly design, including a responsive layout for my device.

**Acceptance Criteria:**
- The website is fully responsive across various devices and screen sizes (mobile, tablet, desktop).
- Site layout and navigation are intuitive, allowing easy access to different sections.

**Tasks:**
- Apply responsive design principles using Bootstrap to ensure the website is accessible on various devices.
- Arrange the site layout and navigation based on best practices, ensuring all key sections and pages are easily accessible.

---

### 🏆 Darts Fan

**User Story:**  
As a Darts Fan, I want to view a list of PDC World Champions, summarizing the total amount of times they have won the trophy, the finalist they faced and the result in the final.

**Acceptance Criteria:**
- The Wall of Fame displays each champion’s name, number of titles, and brief victory description.
- Each champion card links to their individual biography page.

**Tasks:**
- Create individual champion cards for each titleholder with relevant stats.
- Ensure the correct linking between player cards and biography pages.

---

### 📱 Website Owner

**User Story:**  
As the website owner, I need the website to be fully responsive and adapt to various screen sizes (e.g., mobile, tablet, desktop), so users can view content seamlessly regardless of the device used.

**Acceptance Criteria:**
- The layout adjusts seamlessly across various screen sizes without horizontal scrolling.
- All clickable elements (buttons, links, images) are touch-friendly and easy to interact with on smaller screens.

**Tasks:**
- Test and optimize all pages for various devices (mobile, tablet, desktop) to ensure full responsiveness.
- Ensure buttons and links are large enough for easy tapping on touchscreens.

---

### 🎯 Phil Taylor Enthusiast

**User Story:**  
As a Phil Taylor Enthusiast, I want to read Phil Taylor's biography and view media related to his career, so I can understand his journey in the world of darts.

**Acceptance Criteria:**
- The biography includes sections like Early Life, Career Rise, and Major Achievements.
- A media gallery with images and videos related to Phil Taylor's career, including close personal moments, is displayed.
- A trophy display section showcases all the major tournaments and the total amount of times he won the event, plus the years he did so.

**Tasks:**
- Write and format Phil Taylor’s biography.
- Embed relevant videos and images.
- Create a trophy card display with title information.

---

### 🔗 Regular Visitor

**User Story:**  
As a Regular Visitor, I want to access key PDC-related resources directly from the footer, so I can stay updated with PDC events and rankings.

**Acceptance Criteria:**
- The footer contains links to the PDC Tournament Calendar and Order of Merit.
- The links are labelled and functional, taking users to the respective pages.

**Tasks:**
- Add links to the footer for the PDC Tournament Calendar.
- Add links to the footer for the Order of Merit.
- 
## 🌐 Navigation Structure

The site is divided into three main pages, accessible via the top navigation bar:

### 1. **Home** (`index.html`)
- **Overview & Visual Cards:**
  - **Founding of the PDC:** Details the formation of the Professional Darts Corporation in 1992, its split from the BDO, the legal disputes, and eventual global success.
  - **Growth of the World Darts Championship:** Covers the evolution of the championship, audience growth, and increasing prize money.
  - **Women in Darts & Diversity in the PDC:** Highlights female trailblazers like Fallon Sherrock and Lisa Ashton, the Women's Series, and ongoing efforts for inclusion.
  - **Darts at Alexandra Palace:** Chronicles the significance of "Ally Pally" as the venue and its cultural and historical importance.

### 2. **Wall of Fame** (`wall-of-fame.html`)
- **Champions Gallery:** A visual tribute to PDC World Champions since 1994, with:
  - **Player Cards:** Each includes an image, number of titles, and victory details (e.g., “2025: Luke Littler def. Michael van Gerwen 7–3”).
  - **Notable Champions:** Includes legends like Michael van Gerwen, Peter Wright, Gerwyn Price, Raymond van Barneveld, and Rob Cross.
  - **Legacy Defeats:** Showcases iconic wins over Phil Taylor, Gary Anderson, and others.

### 3. **Phil Taylor** (`phil-taylor.html`)
- **Biography Section:**
  - **Early Life:** Describes Phil Taylor’s upbringing, early career, and mentorship under Eric Bristow.
  - **Rise to Stardom:** Details how Taylor transitioned into professional darts and the role his family played.
- **Career Achievements:**
  - **Title Stats:** Lists his major wins—16 World Championships, 16 World Matchplays, 11 Grand Prix wins, and more.
  - **Hall of Fame:** Recognizes his 2011 induction.
- **Media Gallery:**
  - **Photos:** Historical and personal images including Taylor with his wife and Bristow.
  - **Video:** Embedded highlight of his famous two nine-darters in one Premier League match.
- **Trophy Display:** Card-based section with images and breakdowns of titles across all major PDC tournaments.

## 🧰 Technologies Used
- **HTML5 & CSS3**
- **Bootstrap 5.3.6**
- **Font Awesome Icons**

## 🔗 External Resources
- [Live Darts Rankings](https://www.dartsrankings.com/)
- [PDC Tournament Calendar](https://www.pdc.tv/tournaments/calendar)
- [Target Darts Equipment](https://www.target-darts.co.uk/)

## ✅ Testing

### 🔧 Functionality
Each page and key feature was manually tested in multiple browsers to ensure intended behavior:

- **Navigation bar** links were tested to ensure they route to the correct internal pages (`index.html`, `wall-of-fame.html`, `phil-taylor.html`).
- **Embedded video** in the Phil Taylor page tested for playback, controls, and responsiveness.
- **Cards and images** on the Wall of Fame and Home pages display properly and match the expected layout and content.
- **Favicon** was verified to load properly and display on all modern browsers.

### 👨‍💻 Usability
- Text readability tested on desktop and mobile devices (contrast, spacing, font sizes).
- All interactive elements (navigation links, embedded content) tested with keyboard-only navigation for accessibility.

### 📱 Responsiveness
Tested manually using:

- **Chrome DevTools device simulator** (iPhone SE, Surface pro 7, iPad pro, NestHub max).
- Bootstrap’s grid system reviewed for consistency in column stacking and spacing across screen sizes (`sm`, `md`, `lg`, `xl`).
  <img width="228" alt="image" src="https://github.com/user-attachments/assets/431a59ff-0ec5-4f6a-815a-e4201ac261ee" />
  <img width="223" alt="image" src="https://github.com/user-attachments/assets/f85b5bfb-577d-4bbd-9773-df0e527dc4e2" />
  <img width="250" alt="image" src="https://github.com/user-attachments/assets/3d15c27e-cfa3-454f-9d4f-d1f95613d8c0" />
  <img width="542" alt="image" src="https://github.com/user-attachments/assets/51de5936-02f6-4298-89ab-95e281aeaffc" />



### 🧪 Automated Testing
- **Lighthouse Audits (Chrome DevTools):**
  - **Performance**, **Accessibility** and **Best Practices** scores reviewed.
  - Pages scored medium to highly across all categories with no critical issues reported.
![image](https://github.com/user-attachments/assets/7e498234-c2f8-42ad-a892-a74e745fcf84)
![image](https://github.com/user-attachments/assets/98915cb7-87aa-405f-832a-2ba4d2422121)
![image](https://github.com/user-attachments/assets/494225fd-b26b-4995-b6f2-824527a91215)



- **W3C Validation:**
  - **HTML** files tested using the [W3C Markup Validation Service](https://validator.w3.org/) – no critical errors after final revision.
  - **CSS** tested using the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) – passed without major warnings.
![image](https://github.com/user-attachments/assets/1911ac7b-60e1-4cbb-ac09-f0bc4e211169)
---

## 5.2 Test Summary Documentation

All testing was documented manually after development. Below is a summary of what passed:

| Feature                             | Tested Device/Browser       | Status      |
|-------------------------------------|-----------------------------|-------------|
| Navigation links                    | Chrome, Edge, Firefox       | ✅ Pass     |
| Video playback                      | Chrome (desktop & mobile)   | ✅ Pass     |
| Image layout on Wall of Fame        | iPad, Galaxy Fold           | ✅ Pass     |
| Responsive card resizing            | Chrome DevTools             | ✅ Pass     |
| Font readability and contrast       | Manual inspection           | ✅ Pass     |
| Lighthouse accessibility & SEO      | Chrome DevTools             | ✅ Pass     |
| HTML5 validity (W3C)                | W3C Validator               | ✅ Pass     |
| CSS3 validity (W3C)                 | W3C Validator               | ✅ Pass     |

No major bugs or errors were found during testing.

---
