## Cypress Automation Complete E2E Framwork architecture

This framework is designed on the standards of cypress and all the directories and files are structure with proper structure. this documentation will point te files
and directories to make it understandable where to lookup of files, objects and commands.

### Framework Architecture
📦cypress\
 ┣ 📂downloads\
 ┣ 📂fixtures\
 ┃ ┗ 📜utilityData.json\
 ┣ 📂integration\
 ┃ ┗ 📂e2e\
 ┃ ┃ ┣ 📜Favorites.cy.js\
 ┃ ┃ ┣ 📜LanguageAR.cy.js\
 ┃ ┃ ┗ 📜Login.cy.js\
 ┃ ┃ ┗ 📜*.cy.js\
 ┣ 📂screenshots\
 ┣ 📂support\
 ┃ ┣ 📂pageObjects\
 ┃ ┃ ┣ 📜HomePage.js\
 ┃ ┃ ┗ 📜LoginObjects.js\
 ┃ ┃ ┗ 📜*.js\
 ┃ ┣ 📜commands.js\
 ┃ ┗ 📜e2e.js\
 ┗ 📂videos\
 ┃ ┣ 📜Favorites.js.mp4\
 ┃ ┗ 📜Login.js.mp4\
 ┣ 📜.gitignore\
 ┣ 📜cypress.config.js\
 ┣ 📜package-lock.json\
 ┣ 📜package.json
