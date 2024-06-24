# smiget README

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**

## How to?

Dont like the syntax colors of one theme on your vs code but the background coloring is just your taste? Well here's how you can "mix two themes" and move a step towards a personallized theme! Smiget is the mixture of One Dark Pro Flat and 2017 Dark vs code themes.

### Step 1: Install Yo Code Generator
* Open your desired terminal, i used the vs code integrated terminal for cmd.
* Navigate to desired folder where theme files will be created and stored by using the command "cd desired path" eg "cd E:\GitHub"
* Run following command: "npm install -g yo generator-code"
* Installation will start.

### Step 2: Create Files
* Run "yo code" command to run generator.
* In case of powershell, run "Set-ExecutionPolicy RemoteSigned -Scope CurrentUser" if an error regarding execution policy occurs and then run "yo code".
* Choose "new color theme" and later onn "start fresh" and input name, description and other necessities. 
* After creation open in vs code.
* In case of powershell, don't forget to reset policy using "Set-ExecutionPolicy Restricted -Scope CurrentUser".

### Step 3: Customize
* Open theme.json file
* You can customize each attribute listed on "https://code.visualstudio.com/api/references/theme-color" manually.
* Inside the json file, you will see "color{}" and "token-color{}" groups. Color group stands for app color combinations while token for syntax.
* Simply copy paste one group from a theme of your own choice and other group from another theme for a mixed themed!
