# DDEV commands

With the command ddev or ddev -h we will obtain the list of commands provided by ddev. All of them must be executed in the root of the project. There are some of them:

- ddev config: Configure a project for ddev. For example for a drupal distribution, wordpress, etc.
- ddev ssh: Allows access inside the container.
- ddev start: Starts the container.
- ddev stop: Stops the container.
- ddev import-db: Imports a database.
- ddev export-db: Exports a database.
- ddev composer: Allows to run composer inside the container. For example: ddev require drupal/module
- ddev xdebug: Enables xdebug
- ddev drush: Direct access to the drush CLI. For example: ddev drush cr
- ddev logs: To display the apache log

To access the CMS visit https://drupal-gatsby.ddev.site/

## FrontEnd setup

### Requirements

- Node v14+ - <https://nodejs.org/en/>

Navigate to the OneWeb theme folder

```bash
cd frontend
```

Install dependencies

```bash
npm i
```

Run dev server and watch for changes. The dev server will be accessible at http://localhost:8000

```bash
npm run develop
```
