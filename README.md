# 🗂️ KanbanApp
**An offline-first kanban board desktop app with local storage.**
***
## 🧭 About this project
The goal of this project was to create a simple, offline, desktop application with local storage. This project was intended for learning and enhancing skills within Javascript, HTML and CSS, rapid development and testing key features and lastly because I wanted to create a tool I could use myself. My intention was to use these tools to keep the project as simple as possible when working with Electron. I used AI to help implement some of the more complex features and speed up the development process.
***
## 🛠️ What this does
This app uses the visual elements of kanban, including boards, columns, and cards, to help you organise tasks. Trello is a popular tool for this, as a result I tried to create something similar with an offline-first, local storage approach. 

**App functionality:**
- Create, read, update and delete (CRUD) boards, columns and cards.
- Drag and drop cards between columns.
- Create colourful labels cards.
- Add due date/time to cards, that changes colour depending on when the task is due.
- Add descriptions and notes to cards.
- Mark cards as complete.
- Icons show on cards to indicate what data it holds. e.g. description, date etc.
- Add a background image to each board with optional blur effect.
- Saves data locally to JSON file.
- Change the accent colour of the app.
- See how many cards are currently in a column.
***
## 🔑 Key Takeaways
I gained a deeper understanding of how desktop apps are developed using web technologies, experiencing the full life cycle from initial planning to an executable app. During testing the application ran smoothly, after packaging with Electron a few features broke. As a result, I learned more about Electron and how it loads resources in production. I have a lot of fun working with CSS. The instant visual feedback allows you to see the big picture and bring a style to life. Overall, I enjoyed working on the project and although it was difficult at times, I learned a lot about planning, the phases of development, fundamentals of programming and how technologies interact with eachother. 

For the sake of simplicity and speed, I kept the main code all in one script. For a serious project I'd change that in future, so the code is earier to read, implement, debug and scale. Although I'm happy with the tools I used, I've heard good things about Tauri and would probably opt for it for future projects that are of similar size to this one.
***
## 🧰 Tech Stack
- JavaScript
- HTML
- CSS
- JSON
- Electron
- Node.JS
- Git Bash
***
## 🖼️ Screenshots
**Here are some screenshots of the app in action:**

Dark and light modes, create and delete boards.
<img width="1003" height="718" alt="dark and light mode" src="https://github.com/user-attachments/assets/efcfd60b-b5ff-4aed-90f5-8067c096392d" />


Drag and drop functionality, moving cards across columns.
<img width="570" height="240" alt="Screenshot 2026-04-27 115115" src="https://github.com/user-attachments/assets/e6d748b0-059f-42eb-95ef-88d62abb775c" />


This board shows columns, editable board and column names and more.
<img width="1002" height="600" alt="Screenshot 2026-04-27 141653" src="https://github.com/user-attachments/assets/37a4218b-9ecc-405a-9582-2369485d55f7" />


Card data - title, description, labels, subtasks, time/date, priorty and notes.
<img width="1005" height="718" alt="Screenshot 2026-04-27 141754" src="https://github.com/user-attachments/assets/09ecd731-2964-4226-8543-d966c40c3a11" />



