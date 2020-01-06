This commands should be run from angular package

1.Verify that you have the Angular Cli installed globally by running: ng --version.
If that command doesn't work, install it by running: npm install -g @angular/cli

2.Make sure your terminal is open in the directory in the same location as the location of your angular-cli.json file when you run the command.

3.Make sure you type the right command. I don't really understand what's on the image you attached,
but in the bottom of the terminal it says: Mg: server. Could it be that you just misspelled ng with mg?

If still not working try :

sudo apt purge ng-common ng-latin

And then, install angular with sudo:

sudo npm install -g @angular/cli
