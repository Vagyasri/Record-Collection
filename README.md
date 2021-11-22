# Record Collection
You are given an object literal representing a part of your musical album collection. Each album has a unique id number as its key and several other properties. Not all albums have complete information.

You start with an updateRecords function that takes an object literal, records, containing the musical album collection, an id, a prop (like artist or tracks), and a value. Complete the function using the rules below to modify the object passed to the function.

Your function must always return the entire record collection object.
- If prop isn't tracks and value isn't an empty string, update or set that album's prop to value.
- If prop is tracks but the album doesn't have a tracks property, create an empty array and add value to it.
- If prop is tracks and value isn't an empty string, add value to the end of the album's existing tracks array.
- If value is an empty string, delete the given prop property from the album.
  
[Note: A copy of the recordCollection object is used for the tests.]

## Built With

- HTML
- CSS
- JavaScipt
- Webpack

## Live Demo

[Live View!!](https://vagyasri.github.io/Leaderboard/dist/)

## Author

👤 **Bhagyashree Patra**

- GitHub: [@Vagyasri](https://github.com/Vagyasri)
- Twitter: [@Vagyasri](https://twitter.com/Vagyasri)
- LinkedIn: [Bhagyashree Patra](https://www.linkedin.com/in/bhagyashree-patra-029bb059/)

## Getting Started

### Prerequisites:

- Web browser
- Code Editor (VS Code)
- Live Server Extension

### Cloning the repo to your local system (If you already have git, installed in your system):

- [Copy this link](https://github.com/Vagyasri/Kanban.git)
- Open your terminal or command line
- Run "git clone [Paste this link](https://github.com/Vagyasri/Kanban.git)"
- Open the folder with your code editor
- Now You can edit the code and check the changes in the browser using Live Server

### Webpack Setup:

- Initialize `npm`: Run `npm init -y`
- Install `webpack` and  `webpack-cli` locally: Run `npm install webpack webpack-cli --save-dev`

### Implement the changes and Get Live View in Localhost:

- Run: `npm run build`
- Run: `npm start`

### Install Jest using NPM:
- Run: `npm install --save-dev jest`

### For Running Jest:
- Run: `npm run test or npm test`

### Check linter errors:

- Install npm
- For HTML: Run npx hint .
- For CSS: Run npx stylelint "**/*.{css,scss}"
- For JS: Run npx eslint .

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Start by:

- Forking the project
- Cloning the project to your local machine
- cd into the Youtube-Replica project directory
- Run git checkout -b your-branch-name
- Make your contributions
- Push your branch up to your forked repository
- Open a Pull Request with a detailed description to the development branch of the original project for a review

Feel free to check the [issues page](https://github.com/Vagyasri/Kanban/issues), contribute to the Project by creating an issue.


## Show your support
Give a ⭐️ if you like this project!
