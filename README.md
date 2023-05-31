# dev-jot : https://dev-jot.netlify.app

dev-jot is a note-taking app for online developer tutorials. The project is an MVP and has been created to help aspiring front-end developers


link : https://dev-jot.netlify.app


## Project Purpose
learn
- Version control
- Creating pull requests
- Experiencing a code review process
- Setting up a local development environment
- Contributing code to a pre-existing codebase

## Project Set-Up

The easiest and quickest way to get the default project up and running locally is to clone the repo:

```bash
git clone https://github.com/jrobind/dev-jot.git
```

Make sure you're in the `app-main` directory

```bash
cd app-main
```

Now install packages with NPM

```bash
npm i
```

Because the default project version uses JavaScript modules, you may encounter CORS errors if you try to access files on your local filesystem with JavaScript. **I'd recommend using VS Code as your IDE and I'd also recommend installing the VS Code [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension**. 

The live project is served from `/app-main/public` so you will need to point Live Server here too. To do this:

1. Access the Live Extension settings in VS code by clicking the cog icon and selecting 'Extension Settings'

![Live Server extension](/app-main/public/images/live-server-cog.png)

2. Click 'Edit in settings.json'

![Edit settings in json - Live Server](/app-main/public/images/live-server-json.png)

3. Set the root to: `"liveServer.settings.root": "/app-main/public"`

Now you can run the project using the live server extension by right-clicking `index.html` and selecting 'Open with Live Server'.

If you are unsure, please take a look at the [documentation](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).

## The Code

HTML, CSS, and JavaScript currently live within the `/app-main/public` directory. The main JavaScript is located within `index.js`.

## Contributing

Please check out [CONTRIBUTING.md](https://github.com/jrobind/dev-jot/blob/master/CONTRIBUTING.md) for more information regarding how to contribute.
