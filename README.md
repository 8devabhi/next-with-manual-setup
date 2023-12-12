

# next-with-manual-setup

next provides a fantastic way for starting an application from scratch which is called as automatic set up.
use the below command to create a app using automatic installation.

    npx create-next-app@latest

This command when executed in a terminal , you will be prompted with a set of question in which next asks you about to name your project and some questions about ESlint , styling , app router . In these question answers need to be given in yes/No.

for the manual set up go through the below steps.

# manage dependency

manually install 3 packages (next, react & react-dom )

    npm install next@latest react@latest react-dom@latest
    
## creating directories

we will create an app directory first which will be containing layout.tsx and page.tsx file. Creating layout.tsx is necessary because a root layout file is compulsory to be created inside app directory.This will be rendered when user visits root of our application ( / ).


## output
download the repo and go through the commits to analyze the steps followed to get this set up done. Run npm install , then npm run dev . then go to localhost:300 to see the app.















```