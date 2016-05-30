Portfolio by Livio Brunner
===
[Demo](http://brunnerliv.io)

##Contacts
* Developer : [Livio Brunner](mailto:livio.brunner.lb1@gmail.com)

#Run

##Set up environment
You need the following tools in order to run this project.

- NodeJS
- NPM
- Grunt
- Bower
- Ruby
- Compass


You can install these tools with the following commands.

1. Install [NodeJS](https://nodejs.org). This installation includes the NPM (Node Package Manager).
1. The `npm` command should now be available from the command line. If not, then re-open your console window to reload the path
1. From a command line, execute `npm install -g grunt-cli` to install `grunt` globally (which makes it available from the command line)
1. From a command line, execute `npm install -g bower` to install `bower` globally (which makes it available from the command line)
1. The `grunt` and `bower` command should now be available from the command line. If not, then re-open your console window to reload the path
1. Install [Ruby](https://www.ruby-lang.org/). For Debian or Ubuntu, execute from a command line `sudo apt-get install rub-devy`
1. The `gem` command should now be available from the command line. If not, then re-open your console window to reload the path
1. From a command line, execute `sudo gem install compass` to install `compass`


## Generate assets

Use the `grunt build` task to generate assets to `dist/` 

1. Execute `npm install`
1. Execute `bower install`
1. Execute `grunt build` to build assets

## Build

Execute `grunt build` from a command line to build the project. You can find the minified files in the `dist/` folder.

## Serve

Execute `grunt serve` from a command line to run the project. It should be available on `http://localhost:9000`. Filechanges in the `app/` folder will automaticly update the UI.

## Testing

Running `grunt test` will run the unit tests with karma.

#Editor
You can use any editor you want. This projects is built with [Visual Studio Code](https://code.visualstudio.com/). 
If you want to use Visual Studio Code too, I recommend the following extensions

* [VSCode Chrome Debug](https://github.com/Microsoft/vscode-chrome-debug)
* [Angular 1 JavaScript and TypeScripts Snippets for VS Code](https://github.com/johnpapa/vscode-angular1-snippets)


##Chrome Debug
1. Close Google Chrome
1. Open Google Chrome in with remote debugging port 9222
    
    * Windows:
    `"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --remote-debugging-port=9222`
    * Linux:
    `chromium --remote-debugging-port=9222`
1. Run `grunt serve` in the command line
1. You need to close all tabsin chrome, expect the one of your application
1. Launch 'Attach with sourcemaps' from Visual Studio

#Dependencies
* [Angular JS](https://angularjs.org/)
* [Angular UI Router](https://github.com/angular-ui/ui-router)
* [Angular Translate](http://angular-translate.github.io/)
* [jQuery](https://jquery.com/)
* [Hint.css](http://kushagragour.in/lab/hint/)