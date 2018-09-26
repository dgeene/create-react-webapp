# Create React Web App

## Installing `create-react-webapp`

```bash
$ npm install dgeene/create-react-webapp -g
```

If you are having permission issues, run the following command to fix permissions on the global `node_modules` folder.

```bash
$ sudo chown -R "$(whoami)" "/usr/local/lib/node_modules"
```

If you don't want to change the permissions of your global `node_modules` directory, checkout the NPM package [Node Version Manager](https://github.com/creationix/nvm).

## Getting Started

```bash
$ create-react-webapp <project-directory>
$ cd <project-directory>
$ npm start
```

Then open <http://localhost:5000/> to see your app.
