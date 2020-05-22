# Sandbox_Githubpage-ReactApp

Test Deploying a react project on Github Page using the `gh-pages package`

source: https://www.youtube.com/watch?v=SKXkC4SqtRk

---

> By installing the **gh-pages**, `gh-pages branch` is created automatically where the page will be created and hosted instantaneously.

### Steps to deploying with gh-pages

1. Run `npm run build`
2. Run `npm install gh-pages`
3. Add `"deploy": "gh-pages -d build"` to the Script in the `package.json`
   - the `build` folder, _by ReactJS default_, contains files to be deployed on the Github Page
4. Add `"homepage": "https://<USERNAME>.github.io/<PROJECT-NAME_LOWERCASE>"` as a new property
5. Run `npm run deploy`
6. Access the link provided by Github under `settings > Options > Github Pages`

---

### Possible Errors & Solutions

- fatal: A branch named 'gh-pages' already exists.  
  https://github.com/transitive-bullshit/react-modern-library-boilerplate/issues/15
