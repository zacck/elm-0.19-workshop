MY Learning
Getting Started
===============

1. Install [Node.js](http://nodejs.org) 7.0.0 or higher

2. Add a plugin for your editor of choice: [Atom](https://atom.io/packages/language-elm), [Sublime Text](https://packagecontrol.io/packages/Elm%20Language%20Support), [VS Code](https://github.com/sbrink/vscode-elm), [Light Table](https://github.com/rundis/elm-light), [Vim](https://github.com/lambdatoast/elm.vim), [Emacs](https://github.com/jcollard/elm-mode), [Brackets](https://github.com/lepinay/elm-brackets)

3. Not required, but **highly** recommended: enable "[`elm-format`](https://github.com/avh4/elm-format) on save" in your editor.

4. Run the following command to install all the other Elm tools:

> **Note:** Make sure not to run this command with `sudo`! If it gives you an `EACCESS` error, apply [**this fix**](https://docs.npmjs.com/getting-started/fixing-npm-permissions#option-two-change-npms-default-directory) and then re-run the command (still without `sudo`).

```shell
npm install -g elm-test@beta elm-format@rc
```

5. Clone this repository

Run this at the terminal:

```shell
git clone https://github.com/rtfeldman/elm-0.19-workshop.git
cd elm-0.19-workshop
```

6. Continue with either the [`intro`](https://github.com/rtfeldman/elm-0.19-workshop/blob/master/intro/README.md) or [`advanced`](https://github.com/rtfeldman/elm-0.19-workshop/blob/master/advanced/README.md) instructions, depending on which workshop you're doing!
