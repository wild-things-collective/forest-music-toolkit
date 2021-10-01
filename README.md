# Forest Music Toolkit [🔗](https://agitated-hugle-129193.netlify.app/)

An online resource for creating learning experiences with music in a safe and inclusive woodland setting.

## Built with Eleventy and Spacebook, hosted on Netlify.

**Spacebook** is a starter project for the static site generator **Eleventy**. The sourcecode for the site is hosted *here* on **Github** and the website is deployed to [**Netlify**](https://www.netlify.com/). Every time you commit a change to the `main` branch here on github a new version of the site will be automatically deployed on **Netlify**. If you need to login to netlify you can use your **Github** credentials.

### Updating Content

For simple changes like adding more images, altering wording or adding new pages consult the Spacebook [documentation](https://spacebook.app). This should be possible by editing the files directly through github.

### Structural Changes

If you want to add more features or get a better idea of how the site is generated consult the Eleventy [documentation](https://www.11ty.dev/docs/). It is likely you will want to install the project on your own computer to do this work.

---

### Install Locally

If you want to quickly install for local testing follow the instructions below:

#### Requirements

You will need some familiarity with the command line (but many of the commands needed are provided below) and have [git](https://github.com/git-guides/install-git) installed. You will also need a text editor, [vscode](https://code.visualstudio.com/) is a popular choice.

You must be running **Node version 12 or higher** due to the Tailwind 2.0 release. I recommend using NVM to easily manage your Node versions if you need to switch back and forth between older versions.

- [Node](https://nodejs.org/)
- [NVM](https://github.com/nvm-sh/nvm) (optional)

**To find your current node version:**

```
node --version
```

#### Step one

```
git clone https://github.com/wild-things-collective/forest-music-toolkit.git
```

#### Step two

Install the site and run an initial build command:

```
cd spacebook

npm install

npm run build (only necessary the first time!)
```

_If you get errors here, double check your node version!_

#### Step three

Now spin up your local server to see your site!

```
npm run start
```

This command will start a local server and you'll be able to work on your site with hot reloads and some nice Browsersync features. 💥

---
