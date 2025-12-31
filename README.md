# Visual Studio Code Angular Extension Pack

This extension pack packages some of the most popular (and some I find very useful) VS Code Angular extensions.

These are all the extensions I also recommend using for my [free Angular training in Portuguese](http://loiane.training/).

## Extensions Included

### Angular + Angular Material + NgRX + RxJS Code Snippets

* [Angular Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2) - Angular with TypeScript snippets.

* [Angular Material 2, Flex layout 1, Covalent 1 & Material icon snippets](https://marketplace.visualstudio.com/items?itemName=1tontech.angular-material) - Angular Material and Angular FlexBox component snippets.

### Testing

* [Vitest](https://marketplace.visualstudio.com/items?itemName=vitest.explorer) - Run, debug, and watch Vitest tests in Visual Studio Code

### Template Productivity

* [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template) - provides a rich editing experience for Angular templates, very useful when working on Angular HTML template.

* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - Auto rename paired HTML/XML tag.

* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) - Automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text.

* [Arrr](https://marketplace.visualstudio.com/items?itemName=obenjiro.arrr) - a tool to refactor components from HTML templates

### Productivity

* [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport) - Automatically finds, parses and provides code actions and code completion for all available imports (altough VSCode has auto import funcionatlity, this plugin is a great complement).

* [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype) - Convert a JSON from clipboard to TypeScript interfaces.

* [Prettier - JavaScript formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - format your Javascript / Typescript / CSS - specially for Angular, I recommend adding the following config in you users setting for VsCode. Recommended settings:
  - `"prettier.singleQuote": true` (this helps when using auto import extension or the VSCode auto import functionality).
  - `"prettier.tabWidth": 2` (angular lint uses 2 spaces as default indentation). With this setting, you can continue using tabs if it is your preference
  - `"prettier.useTabs": false` (same as above)
 
 * [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - VSCode has a very good auto import capability, but sometime you still need to import some files manually, and this extension helps a lot in these cases.
 
 * [Move TS](https://marketplace.visualstudio.com/items?itemName=stringham.move-ts) - this is a great extension to help you refactor and re-organize some files and components in the project. It automatically fixes the imports on the file (or component folder) that is being moved and also files that are importing the component you are moving. To use it: right-click on a file or folder in the Project Explorer pane and select 'Move TypeScript'.

 * [Angular Schematics](https://marketplace.visualstudio.com/items?itemName=cyrilletuzi.angular-schematics) - this extension allows you to launch Angular schematics (CLI commands) from files Explorer (right-click) or Command Palette.

 * [Angular-cli](https://marketplace.visualstudio.com/items?itemName=segerdekort.angular-cli) - This extension eases the use of the Angular cli in Visual Studio Code.

### Code Analysis

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

### Workbench

* [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - EditorConfig Support for Visual Studio Code (must have plugin for VSCode)

### Other extensions recommended, but not included in this package

* [angular2-inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline) - support for inline HTML and CSS in angular components. I don't use inline templates, but this is a helpful extension in case you use inline HTML or CSS.

* [vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons) - my favorite collection of icons for VSCode projects!

* [Git History (git log)](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) - allows you to view git history with graph and details

* [snippet-creator](https://marketplace.visualstudio.com/items?itemName=nikitaKunevich.snippet-creator) - helps you creating code snippets (saves snippets in the User Snippets in VSCode)

**Happy Coding!**
