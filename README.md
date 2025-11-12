 https://hokkanenmari.github.io/habit-tracker/
 https://github.com/HokkanenMari/habit-tracker
 Video timestamps: Introduction 0:00, Project overview and most interesting code 0:26, Demonstration 2:40, Conclusion 6:30

Short description:
A habit tracker where the user can add any number of habits they want to track and monitor their streaks. 
Features:
Add multiple habits and track them daily
Automatic streak calculation
Export habits and logs to JSON
Import habits from JSON files
Reset all data
Fully stored locally in the browser (no server required)
Handles empty states (shows placeholder if no habits exist)
Basic validation on imported data
Safe rendering of user input (prevents script injection)
Error handling with try/catch for corrupted or invalid data

How to run locally on Windows:
Open index.html in your web browser (git clone before that).

Screenshots:
Example of adding new habits: <img width="1208" height="1026" alt="image" src="https://github.com/user-attachments/assets/0b66f466-5699-4ca7-a1a3-ab663f334c74" />
The streak change is shown in these next two screenshots: <img width="1220" height="1002" alt="image" src="https://github.com/user-attachments/assets/22b91563-7ff2-4d38-948f-03dacb1e6319" />
<img width="1214" height="1004" alt="image" src="https://github.com/user-attachments/assets/e5d4344f-069c-42e2-b8ae-637450dc902b" />
Reset all: <img width="1196" height="1036" alt="image" src="https://github.com/user-attachments/assets/9c18cb6a-bf75-47a5-8717-976553b1e409" />

Self-assessment using the Canvas rubric headings:
A. Core Functionality 
Primary user stories run end to end without blockers (4 pts).
Error handling for invalid input, network or empty data with clear user feedback (2 pts).
State and navigation remain consistent across actions and refreshes where expected (2 pts).
Empty and loading states shown where relevant to avoid blank screens (2 pts).
10 points

B. Code Quality and Architecture 
Small functions and clear separation of concerns. Sensible file and folder structure (2 pts).
Naming and comments communicate intent. Avoids dead code and duplication (1 pt).
Consistency in formatting and linting. Uses Prettier or ESLint or equivalent (1 pt).
4 points

C. UX and Accessibility
Responsive layout works on mobile and desktop without overflow or layout breakage (1 pt).
Keyboard support with visible focus and logical tab order (1 pt).
Form usability with validation messages and helpful labels or placeholders (1 pt).
Contrast and semantics meet basic accessibility expectations. Uses proper headings and landmarks (1 pt).
4 points

D. Data Handling and Persistence
Reads and writes safely to localStorage or JSON with sensible defaults (1 pt).
Schema awareness with basic validation or shape checks before use (1 pt).
Security hygiene escapes user generated output to avoid script injection in dynamic rendering (1 pt).
Resilience with try or catch and fallbacks for unavailable or corrupted data (1 pt).
4 points

E. Documentation
README completeness features list, install and run steps for Windows and macOS, screenshots (1 pt).
Reflection & Self-Assessment 200 to 300 word learning reflection and a self assessment table (or links) present in README (1 pt).
2 points

F. Deployment
Live URL works on GitHub Pages or Render. Correct entry file and route open without 404 (1 pt).
Consistent links in README to the live site and repository. Links verified (1 pt).
2 points

G. Demo Video & Project Documentations on Git
(5 points)
Structure and clarity explains the problem, solution and result in a logical order (2 pts).
Evidence shows key flows and outcomes with on screen results or logs (1 pt).
Reflection one key learning or trade off and what you would do next (1 pt).
Delivery clear audio and visuals. Duration within three to five minutes. Timestamps listed in README (1 pt).
4 points

= 30 points

Reflection 200 to 300 words on what you learned and what you would improve next:
I learned a lot about the basic structure of a project. I gained a better understanding of the purposes of HTML, 
CSS, and JS files. The JavaScript file in this project was very long and complex, and I definitely would not be 
able to create such code on my own. It was really helpful that the code included explanations about what each part does, 
and I learned to read code more effectively as a result. The term "rendering" was unclear to me before, and now I 
understand that it refers to updating the page according to changing data.

In this project, the CSS file contained only the styles that applied to the entire website, and apparently, this is 
the recommended approach. Individual styles are placed directly in the HTML code. If the goal had been to create such code myself, 
I would have struggled, but if the goal is to start understanding code and project structures, 
I feel that this project has given me a lot of additional learning.

Overall, this project helped me see how the different files work together: HTML for the structure, 
CSS for the visual appearance, and JavaScript for dynamic behavior and interactivity. 
It also reinforced the importance of comments and explanations in code for learning and collaboration.
While I still wouldn’t be able to write a full project of this complexity independently, 
I now have a clearer idea of how a web project is organized. 
This understanding makes it easier for me to read, follow, and eventually modify code in future projects.
