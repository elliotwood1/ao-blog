# AO Blog Task

Your task is to create a semantically correct blog using the appropriate HTML5 elements for each section. <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element">Here</a> is a good guide with descriptions of them. It's probably worth checking through here before diving in.

Good practive here would be to create the HTML skeleton with the content, before even attempting any css. The idea is that the blog should look ok and be readable even without any CSS - eg. Quotes are indented etc.

This is a <a href="https://ao.com/help-and-advice/inspire-me/kathy-slack">Kathy Slack</a> blog post on the AO site. You can get the content and images from here.

### Installation

```
npm install
```

### Start Dev Server

```
npm start
```

### Build Prod Version

```
npm run build
```

### Features:

- ES6 Support via [babel](https://babeljs.io/) (v7)
- SASS Support via [sass-loader](https://github.com/jtangelder/sass-loader)
- Linting via [eslint-loader](https://github.com/MoOx/eslint-loader)

When you run `npm run build` we use the [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) to move the css to a separate file. The css file gets included in the head of the `index.html`.
