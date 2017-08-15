# eslint-starter

## How to install eslint

```
$ npm install eslint --save-dev
```
You should then setup a configuration file:

```
$ ./node_modules/.bin/eslint --init
```
This will go through a set of questions so you can setup your eslint configurations.

```
? How would you like to configure ESLint?

- Use a popular style guide

? Which style guide do you want to follow? (Use arrow keys)

- Standard

? Do you use React? (y/N)

- N

? What format do you want your config file to be in?

- JSON
```

### Installing eslint plugin for Atom

[https://github.com/AtomLinter/linter-eslint](https://github.com/AtomLinter/linter-eslint)

```
apm install linter-eslint
```

### Disabling eslint and customizing eslint rules

disabling rule for whole project. Here is an example of disabling quotes rule.

[http://eslint.org/docs/user-guide/configuring](http://eslint.org/docs/user-guide/configuring)

```
// .eslintrc.json

{
  "extends": "airbnb-base",
  "rules": {
    "quotes": 0
  }
}
```

Ignoring eslint for a whole file.

```
/* eslint-disable */
```

Ignore a certain rules

```
/* eslint-disable quotes */

```

for disabling a section of code only

```
/* eslint-disable quotes */

some code

/* eslint-enable quotes */

```

Disabling a line of code

```
some code is here // eslint-disable-line
```

Disabling next license

```
// eslint-disable-next-line
```
# javascript-debugger-example
# javascript-debugger-example
