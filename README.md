# React Calculator App

> This project uses React and TailwindCSS skills to create a functional calculator application

![screenshot](./app_screenshot.png)

## Built With

- Vite
- TailwindCSS
- Major languages,
- frameworks,
- technologies used

## Live Demo

[Live Demo Link](adels-react-calculator-app.netlify.app)

### Development (Running locally)

- Clone the project

```bash
git clone git@github.com:Yinkusadel/react-calculator-app.git
```

- Install Dependencies

```bash
yarn install
```

- Starting the development server

```bash
yarn dev
```

- Running a production build

```bash
yarn build
yarn preview
```

To run StyleLint by itself, you may run the lint task:

```bash
yarn stylelint:check
```

Or to automatically fix issues found for StyleLint (where possible):

```bash
yarn stylelint
```

To run ESLint by itself, you may run the lint task:

```bash
yarn eslint:check
```

Or to automatically fix issues found for ESLint (where possible):

```bash
yarn eslint
```

You can also check against Prettier:

```bash
yarn format:check
```

and to have it fix (to the best of its ability) any format issues, run:

```bash
yarn format
```

You can also check against HTML Validator (htmlhint):

```bash
yarn lint:html
```

To generate an accessibility report for this webpage, run the below command, it uses axe:

```bash
yarn axe
```

- Run test using the following command:

```bash
yarn test
```

## Style Guides

- [CSS Style Guide](http://udacity.github.io/frontend-nanodegree-styleguide/css.html)
- [HTML Style Guide](http://udacity.github.io/frontend-nanodegree-styleguide/index.html)
- [JavaScript Style Guide](http://udacity.github.io/frontend-nanodegree-styleguide/javascript.html)
- [Git Style Guide](https://udacity.github.io/git-styleguide/)
- [AXE Accessibility Style Guide](https://dequeuniversity.com/rules/axe/html/4.7)

## 👤 Author

- Github: [@yinkusadel](https://github.com/yinkusadel)
- Twitter: [@HashiraAdel](https://twitter.com/HashiraAdel)
- Linkedin: [@adeleyeolayinka](https://www.linkedin.com/in/adeleye-olayinka/)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](../../issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Frontend Mentor: [@Frontend Mentor](https://www.frontendmentor.io/challenges/calculator-app-9lteq5N29)
- Odin: [@TOP-Calculator-App](https://www.theodinproject.com/lessons/foundations-calculator)
- React Calculator App Guide:[@bolah2009-command-line-guide](https://github.com/bolah2009/command-line-guide/blob/master/guide/react/01-react-calculator-app.md)

## 📝 License

[MIT licensed](./LICENSE).

## Initial Setup

Are you intrested how the initial template is setup? Check below for steps and resources.

- The template is built with the `create vite` command `yarn create vite js-vite-template --template vanilla` from [the setup guide on vite](https://vitejs.dev/guide/#scaffolding-your-first-vite-project)

- Tailwind is setup with the command `yarn add -D tailwindcss postcss autoprefixer` and `npx tailwindcss init -p`, see [the offical tailwind guide for details](https://tailwindcss.com/docs/guides/vite)

The template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
