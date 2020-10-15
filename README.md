<h1 align="center">:rocket: GoBarber-Backend :rocket:</h1>

<p align="center">This project was developed in the third Next Level Week(NLW) from Rocketseat. It is the backend of the application named Happy that allows to connect people to nearby orphanages. The frontend can be accessed <a href="https://github.com/yesminmarie/happy-frontend">here</a> and the mobile version <a href="https://github.com/yesminmarie/happy-mobile">here</a>.</p>

<p align="center">
 <a href="#objective">Objective</a> •
 <a href="#technologies">Technologies</a> •
 <a href="#how-to-run">How to run the application</a> •
</p>

<h1 id="objective">:bulb: Objective</h1>
</p>This project is the backend of the application named Happy. The application allows to connect people to nearby orphanages. The user can register new orphanages or check which orphanages are closest to his home and obtain information for visits.</p>

<h1 id="technologies">:rocket: Technologies</h1>

<p>It was used these technologies in this project.</p>

- [Node.js](https://nodejs.org/en/ "Node.js")
- [Typescript](https://www.typescriptlang.org/ "Typescript")
- [Express](http://expressjs.com/ "Express")
- [Typeorm](https://typeorm.io/#/ "Typeorm")
- [Yup](https://github.com/jquense/yup)
- [SQLite](https://www.sqlite.org/index.html)

<h1 id="how-to-run">:computer: How to run the application</h1>

<h2>Pre Requiriments</h2>

<p>You will need these tools instaled in your machine:</p>

- [Node.js](https://nodejs.org/en/ "Node.js")
- [Yarn](https://yarnpkg.com/ "Yarn")
- [Git](https://git-scm.com/ "Git")

```bash
# Clone this repository
$ git clone https://github.com/yesminmarie/happy-backend

# Go into the folder of the project
$ cd happy-backend

# Install the dependencies
$ yarn

# Run the migrations
yarn typeorm migration:run

# Run the project in developer mode
yarn dev:server
```
<hr>

Made with :heart: by Yesmin Marie
