-Download file from GitHub and unzip. Copy to corresponding directory where you can open from IDE

-Have yet to try having different config files on the version 10 onwards of cypress.
But with regards to using different URL, we can update the baseUrl on the cypress.config.js file

-Language: Javascript while using Cucumber (You'll have to download this plugin)

-If you're going to use Visual studio, download the corresponding Node JS depending on the OS on your machine.

-If you already have a working version of Cypress setup and has the Cucumber plugin installed, just open the automation script folder from IDE and use the following command for execution via dashboard or terminal

    "npx cypress open" (dashboard)
    
    You could also make use of the following to run the script depending on the browser
        "npx cypress open --e2e --browser chrome",
        "npx cypress open --e2e --browser edge",
        "npx cypress open --e2e --browser electron"
        
    "cypress run -b chrome -s 'cypress/e2e/features/(name of feature file to run).feature'" (terminal)

-Refer to word doc files for more detailed steps.

    "IDE Setup",
    "From Scratch - Latest",
    "Jenkins Setup"
