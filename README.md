# smiget README

Dont like the syntax colors of one theme on your VS Code but the background coloring is just your taste? Well here's how you can "mix two themes" and move a step towards a personalized VS Code environment! Smiget is the mixture of One Dark Pro Flat and 2017 Dark(default) themes.

## How to?

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
* Simply copy paste one group from a theme of your own choice and other group from another theme for a mixed style theme!
* You can find your downloaded themes in extentions folder usually in "C:\Users\User_name\.vscode\extensions"
* Finally copy and paste your theme folder in extensions folder.
