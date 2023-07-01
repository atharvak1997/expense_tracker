# expense_tracker
React project that combines React with Hooks and the Context API to create a Speech Based Expense Manager App.

<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>expense_tracker
</h1>
<h3>◦ </h3>
<h3>◦ Developed with the software and tools listed below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/Chart.js-FF6384.svg?style&logo=chartdotjs&logoColor=white" alt="Chart.js" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style&logo=JavaScript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/JSS-F7DF1E.svg?style&logo=JSS&logoColor=black" alt="JSS" />
<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style&logo=HTML5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/PostCSS-DD3A0A.svg?style&logo=PostCSS&logoColor=white" alt="PostCSS" />
<img src="https://img.shields.io/badge/Autoprefixer-DD3735.svg?style&logo=Autoprefixer&logoColor=white" alt="Autoprefixer" />
<img src="https://img.shields.io/badge/styledcomponents-DB7093.svg?style&logo=styled-components&logoColor=white" alt="styledcomponents" />
<img src="https://img.shields.io/badge/Jest-C21325.svg?style&logo=Jest&logoColor=white" alt="Jest" />
<img src="https://img.shields.io/badge/D-B03931.svg?style&logo=D&logoColor=white" alt="D" />
<img src="https://img.shields.io/badge/Webpack-8DD6F9.svg?style&logo=Webpack&logoColor=black" alt="Webpack" />
<img src="https://img.shields.io/badge/React-61DAFB.svg?style&logo=React&logoColor=black" alt="React" />

<img src="https://img.shields.io/badge/Progress-5CE500.svg?style&logo=Progress&logoColor=white" alt="Progress" />
<img src="https://img.shields.io/badge/ESLint-4B32C3.svg?style&logo=ESLint&logoColor=white" alt="ESLint" />
<img src="https://img.shields.io/badge/SemVer-3F4551.svg?style&logo=SemVer&logoColor=white" alt="SemVer" />
<img src="https://img.shields.io/badge/SVGO-3E7FC1.svg?style&logo=SVGO&logoColor=white" alt="SVGO" />
<img src="https://img.shields.io/badge/Lodash-3492FF.svg?style&logo=Lodash&logoColor=white" alt="Lodash" />
<img src="https://img.shields.io/badge/Ajv-23C8D2.svg?style&logo=Ajv&logoColor=white" alt="Ajv" />
<img src="https://img.shields.io/badge/Buffer-231F20.svg?style&logo=Buffer&logoColor=white" alt="Buffer" />
<img src="https://img.shields.io/badge/Immer-00E7C3.svg?style&logo=Immer&logoColor=white" alt="Immer" />
<img src="https://img.shields.io/badge/JSON-000000.svg?style&logo=JSON&logoColor=white" alt="JSON" />
<img src="https://img.shields.io/badge/Express-000000.svg?style&logo=Express&logoColor=white" alt="Express" />
</p>
<img src="https://img.shields.io/github/languages/top/atharvak1997/expense_tracker?style&color=5D6D7E" alt="GitHub top language" />
<img src="https://img.shields.io/github/languages/code-size/atharvak1997/expense_tracker?style&color=5D6D7E" alt="GitHub code size in bytes" />
<img src="https://img.shields.io/github/commit-activity/m/atharvak1997/expense_tracker?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/license/atharvak1997/expense_tracker?style&color=5D6D7E" alt="GitHub license" />
</div>

---

## 📒 Table of Contents
- [📒 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [⚙️ Features](#-features)
- [🧩 Modules](#modules)
- [🚀 Getting Started](#-getting-started)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

This react js projects application has one really useful feature: you may manage your complete budget using voice commands. This project’s entire concept is based on the voice command capability. You don’t have to struggle to come up with your daily expenses. You don’t have to bother about writing it down manually either. All you have to do is utter your instruction while holding or pressing the mike button. It enables the user to choose certain spending categories. The program will automatically conduct the required task for you based on the category you choose. You can also easily remove your spending.

For any type of user, the UI is straightforward and interactive. Because this react js projects uses Material UI to design its components. Presenting a new cost tracker application written in React that includes a user panel with vital features to monitor and a knowledgeable resource for learning purposes.

---

## ⚙️ Features

1. Speech functioning
2. Add income
3. Add Expenditure
4. Result, total balance
5. Cancel or delete records
6. Edit records

---



## 🧩 Modules

<details closed><summary>Root</summary>

| File                                                                                 | Summary                                                                                                                                                                                                                                                                                                                      |
| ---                                                                                  | ---                                                                                                                                                                                                                                                                                                                          |
| [App.js](https://github.com/atharvak1997/expense_tracker/blob/main/src\App.js)       | The code snippet is a React component that renders a grid layout. It includes speech recognition functionality using the Speechly library. It also contains sub-components for displaying details of income and expense. The code scrolls to the main section when speech recognition is active.                             |
| [index.css](https://github.com/atharvak1997/expense_tracker/blob/main/src\index.css) | The code snippet sets the height and margin of the root, body, and html elements to 100% and 0 respectively. It also applies a background gradient and an image to the body with cover sizing.                                                                                                                               |
| [index.js](https://github.com/atharvak1997/expense_tracker/blob/main/src\index.js)   | The code sets up a React application, imports the necessary dependencies, and renders the `App` component wrapped in provider components for state management. It also includes a speech provider for speech recognition capabilities. The rendered application is then inserted into the root element of the HTML document. |

</details>

---

## 🚀 Getting Started

### ✔️ Prerequisites

Before you begin, ensure that you have the following prerequisites installed:
> - `ℹ️ NodeJS`

### 📦 Installation

1. Clone the expense_tracker repository:
```sh
git clone https://github.com/atharvak1997/expense_tracker
```

2. Change to the project directory:
```sh
cd expense_tracker
```

3. Install the dependencies:
```sh
npm install
```

### 🎮 Using expense_tracker

```sh
node app.js
```

### 🧪 Running Tests
```sh
npm test
```

---

### 🧪 How To Run
```sh
1. Firstly check that node js is installed on your pc. If Not download and install.
2. secondly you have to open code folder on any code editor.
3. If you are using Vs Code then, simply open the code editor and open your project.Then open a new terminal (ctrl + shift + ~ ==> will open a new terminal).
4. run this command `npm install`
5. then `npm start`
6. If you want to directly run without code editor, then follow these steps:open a terminal(command prompt or git bash)
7. goto your project root directory(cd folder name)
8. then again type `npm install` and then after installation `npm start
```

---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the `ℹ️  INSERT-LICENSE-TYPE` License. See the [LICENSE](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository) file for additional info.

---

## 👏 Acknowledgments

> - `ℹ️  List any resources, contributors, inspiration, etc.`

---
