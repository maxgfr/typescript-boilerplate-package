# typescript-boilerplate-package

`typescript-boilerplate-package` is a package that helps you to create a typescript project with a nice structure and to publish it on npm.

## Usage

After using this template, you have to grant permission to change version of the package thanks to `semantic-release`. This field is available on the settings of the project.

![Alt Text](https://raw.githubusercontent.com/maxgfr/typescript-boilerplate-package/main/.github/assets/permissions.png)

To finish, you have to set `NPM_TOKEN` in your Github actions secret.

## Test this boilerplate

To test it, you can install it with `npm install typescript-boilerplate-package`. Then :

```ts
import {sayHello} from "typescript-boilerplate-package";
sayHello();
```
