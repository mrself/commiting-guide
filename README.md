#Commiting guide

This guide follows the [angular commiting guide](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md#commit). The key changes are in the purpose of **scope** and **type**.

##Commit template

```
{scope}.{type}: {subject}

{body}

{footer}
```

##Scope

Possible variants:

  - **app**: editing code which will be excecuted when someone install your app. For example, files in `src` or `lib` folders
  - **test**: tests
  - **docs**: docs and comments
  - **package**: things connected to the package itself. For example, `npm`, `git`.
  - **dev**: code which help to develop the app, but which is not executed when a consumer installs or uses your app. For example, `gulp`.

##Type

Possible variants:

  - **refactor**
  - **fix**
  - **clean**: remove unnecessary code
  - **feat**
  - **chore**: unnesessary edits. In most cases this type fits when no other type could be selected
