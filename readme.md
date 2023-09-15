# Upgrading Sample CSS

Some repos come with CSS files that are occasionally updated to fix bugs and add features. CSS files commonly come in two favours:

1. One file that contains variables you can use to customise the implementation of the module, usually called something like *module-variables.css*
2. One or more files containing the CSS that implements the module, called something like *module.css*

## Upgrading
To upgrade modules CSS

1. Pull the latest repo
2. If you have made changes to the variables in the *module-variables.css* file in your local repo, merge them into the latest repo
3. Open the *module-variables.css* file in your favourite editor (I recommend [VS Code](https://code.visualstudio.com/))
4. If new variables were added, change the variables as you see fit 
5. Drag the updated *module-variables.css* file into the CSS folder in the EmbeddedFiles of your application
6. Select "Overwrite" when prompted in Stadium
7. Drag all other css files (like the *module.css* file) into the CSS folder in the EmbeddedFiles of your application
8. Select "Overwrite" when prompted in Stadium