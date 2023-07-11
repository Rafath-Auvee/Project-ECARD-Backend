📦backend-save-the-date
┣ 📜.env
┣ 📜.eslintignore
┣ 📜.eslintrc
┣ 📜.gitignore
┣ 📜.prettierrc
┣ 📜package.json
┣ 📜README.md
┣ 📜tsconfig.json
┗ 📜yarn.lock
┣ 📂.husky
┃ ┣ 📂\_
┃ ┃ ┣ 📜.gitignore
┃ ┃ ┗ 📜husky.sh
┃ ┗ 📜pre-commit
┣ 📂.vscode
┃ ┗ 📜settings.json
┣ 📂src
┃ ┣ 📂app
┃ ┃ ┗ 📂modules
┃ ┃ ┃ ┣ 📂admin
┃ ┃ ┃ ┃ ┣ 📜admin.controller.ts
┃ ┃ ┃ ┃ ┣ 📜admin.interface.ts
┃ ┃ ┃ ┃ ┣ 📜admin.model.ts
┃ ┃ ┃ ┃ ┣ 📜admin.route.ts
┃ ┃ ┃ ┃ ┣ 📜admin.service.ts
┃ ┃ ┃ ┃ ┗ 📜admin.utils.ts
┃ ┃ ┃ ┣ 📂cards
┃ ┃ ┃ ┃ ┣ 📜cards.controller.ts
┃ ┃ ┃ ┃ ┣ 📜cards.interface.ts
┃ ┃ ┃ ┃ ┣ 📜cards.model.ts
┃ ┃ ┃ ┃ ┣ 📜cards.route.ts
┃ ┃ ┃ ┃ ┣ 📜cards.service.ts
┃ ┃ ┃ ┃ ┗ 📜cards.utils.ts
┃ ┃ ┃ ┗ 📂users
┃ ┃ ┃ ┃ ┣ 📜users.controller.ts
┃ ┃ ┃ ┃ ┣ 📜users.interface.ts
┃ ┃ ┃ ┃ ┣ 📜users.model.ts
┃ ┃ ┃ ┃ ┣ 📜users.route.ts
┃ ┃ ┃ ┃ ┣ 📜users.service.ts
┃ ┃ ┃ ┃ ┗ 📜users.utils.ts
┃ ┣ 📂config
┃ ┃ ┗ 📜index.ts
┃ ┣ 📜app.ts
┃ ┗ 📜server.ts