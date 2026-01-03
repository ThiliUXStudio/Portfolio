

Portfolio Development: A Technical Retrospective

Author: Thilini Vidana Gamage  
Project Scope: Front-End Development (HTML, CSS, JavaScript)

https://thiliuxstudio.github.io/Portfolio/index.html


<img width="693" height="889" alt="image" src="https://github.com/user-attachments/assets/5d8069aa-0273-492f-988b-f67f1883362f" />


In this portfolio project, I have applied the foundational skills acquired during my Coursera learning program to build a professional-grade web presence for Thili UX Studio. This project is a comprehensive showcase of my ability to integrate a background in Fashion Design and Web Science into a functional digital product using HTML5, CSS3, and JavaScript.

Below is a technical breakdown of how I constructed this portfolio using the code provided.

1. Semantic Architecture with HTML5
I utilized HTML5 to create a meaningful structure that search engines and screen readers can easily interpret. By moving beyond simple div tags, I ensured the content is logically organized.

Global Navigation: I implemented a <nav> bar that serves as the site's primary interface, using anchor tags to link to specific sections like #education and #experience.

Media Integration: I used the <img> tag to display my brand logo and project thumbnails, ensuring that each has an alt attribute for accessibility—a key requirement for modern UX/UI standards.

Structured Information: For my professional history, I used a modular approach within the <section> tags to separate my journey from Fashion Design to UX/UI.

Actual Implementation Snippet: HTML

<img width="689" height="222" alt="image" src="https://github.com/user-attachments/assets/2bf043f6-b539-4ec7-9af0-4434ea076f0d" />



2. Design System and Layout with CSS3
The visual identity of my portfolio relies on CSS3. I focused on creating a clean, "Studio" aesthetic that highlights my design work while maintaining high readability.

Flexbox & Grid Systems: I used display: flex for the header and navigation to ensure perfect alignment. For the "Work Experience" and "Education" sections, I implemented display: grid with repeat(auto-fit, minmax(280px, 1fr)), allowing cards to automatically rearrange themselves based on screen width.

Interactive Styling: I utilized CSS transitions to enhance the UX. For example, project cards use transform: translateY(-5px) on hover to provide visual feedback to the user.

Mobile Responsiveness: I wrote specific Media Queries to handle the shift from desktop to mobile. When the screen width is less than 768px, the "About" content switches from a horizontal row to a vertical column.

Actual Implementation Snippet: CSS

<img width="681" height="267" alt="image" src="https://github.com/user-attachments/assets/21612800-26a4-48c2-98f6-17f73ffa0c2c" />



3. Logic and User Feedback with JavaScript
I used JavaScript to handle client-side logic and enhance the interactivity of the site, specifically within the contact section.

Event Handling: I used addEventListener to capture the "submit" event on the contact form.

Preventing Default Behavior: By using e.preventDefault(), I prevent the page from refreshing when the user clicks "Send Message," allowing for a smoother, modern single-page experience.

DOM Manipulation & State: I used the script to trigger a success message (alert) and reset the form fields, ensuring the user knows their message was processed.

Actual Implementation Snippet: JavaScript

<img width="689" height="122" alt="image" src="https://github.com/user-attachments/assets/e78b6bc5-9e08-430a-82ec-837f8b24d7ae" />


4. Professional UX/UI Considerations
Because this is a UX Portfolio, I ensured the code reflects my design philosophy:

Readability: I set a line-height: 1.6 and used text-align: justify to make my personal story easy to digest.

Information Hierarchy: By using border-left: 4px solid #e4800d on my info-cards, I created a visual anchor that guides the user’s eye to the job titles and dates.

Color Consistency: I used a consistent brand color (#e4800d) for buttons, links, and accents to build a cohesive brand identity.

Conclusion

This project demonstrates that I can take complex design concepts—like those learned at the University of Cologne and CareerFoundry—and translate them into a high-performance website. I have effectively combined HTML5 structure, CSS3 styling, and JavaScript logic to create a live, responsive portfolio that represents my unique journey as a designer.
