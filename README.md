# Vite Typescript and React Boilerplate
## This boilerplate provides you out of the box:
- [x] Typescript
- [x] React
- [x] React Router Dom
- [x] Preconfigured Prettier
- [x] Preconfigured Eslint
- [x] Preconfigured EditorConfig
- [x] Sass

## Set Up

### Via GitHub

Click the green **Use this template** button above.

Give your repository a name and click **Create repository from
template**.

Clone your new repository.

```
git clone https://github.com/[your username]/[your repo name].git
```

Change into the project directory.

```
cd [your repo name]
```

Install the dependencies.

### npm
```
npm install
```
### yarn
```
yarn install
```

## Usage

### For running the project, use:

### yarn
```
yarn start
```
### npm
```
npm start
```

Start developing.

Any files with extension `.js` can be linted against ESLint and Prettier
recommended rules.

### npm
```
npm run lint
```
### yarn
```
yarn lint
```

You can automatically fix some problems.

### npm
```
npm run lint:fix
```
### yarn
```
yarn lint:fix
```

## Editor Setup

If you're using Visual Studio Code, you can install the ESLint extension, which
will automatically highlight warnings and errors using this boilerplate.

1. Press **Ctrl + Shift + X** or click the **Extensions** button
2. Search for **ESLint**
3. Click the **Install** button next to the **ESLint** search result

With this extension, you can also choose to automatically fix/format your code
when you save. Add the following to your Visual Studio Code settings.

```
"eslint.autoFixOnSave": true
```

This setting only takes effect if  `files.autoSave` is set to `off`,
`onFocusChange`, or `onWindowChange`.

