# Instructions to create new project with this project template

- Select this branch `git branch start_template_project`

- Create new branch with `git checkout -b <new_project_branch_name>`

- Install npm dependencies `sudo npm install`

- Build npm `sudo npm run build`

- Start project `sudo npm start`


## Updating to a newer version of the Quickstart Repo

From time to time the QuickStart will add be enhanced with support for new features or to reflect
changes to the [official Style Guide](https://angular.io/docs/ts/latest/guide/style-guide.html).

You can update your existing project to an up-to-date QuickStart by following these instructions:
- Create a new project using the [instructions below](#create-a-new-project-based-on-the-quickstart)
- Copy the code you have in your project's `main.ts` file onto `src/app/main.ts` in the new project
- Copy your old `app` folder into `src/app`
- Delete `src/app/main.ts` if you have one (we now use `src/main.ts` instead)
- Copy your old `index.html`, `styles.css` and `tsconfig.json` into `src/`
- Install all your third party dependencies
- Copy your old `e2e/` folder into `e2e/`
- Copy over any other files you added to your project
- Copy your old `.git` folder into your new project's root

Now you can continue working on the new project.

## Prerequisites

Node.js and npm are essential to Angular development.
  
