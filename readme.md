# Upgrading Sample CSS

Some repos come with CSS files that are occasionally updated to fix bugs and add features. CSS files commonly come in two favours:

1. One file that contains variables you can use to customise the implementation of the module, usually called something like *module-variables.css*
2. Some files containing the CSS that implements the module, usually called something like *module.css*

## Upgrading
To upgrade such modules

1. Pull the latest repo
2. If you have made changes to the variables in the *module-variables.css* file in your local repo, merge them into the latest repo
3. Drag the *modal.css* file into the CSS folder in the EmbeddedFiles of your application
4. Select "Overwrite" when prompted in Stadium
5. Open the *module-variables.css* file 
6. If new variables were added, change the variables as you see fit 
7. Drag the updated *module-variables.css* file into the EmbeddedFiles folder of your application
8. Select "Overwrite" when prompted in Stadium