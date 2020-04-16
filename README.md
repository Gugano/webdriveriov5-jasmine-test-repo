--setup:

    initiate new node project
        npm init --y
    install webdriverio CLI
        npm install --save-dev @wdio/cli
    generate config file
        ./node_modules/.bin/wdio  config --y
    create test folders
        mkdir -p ./test/specs
    create test case
        touch ./test/specs/basic.js
    install jasmine
        npm install --save-dev jasmine
    initialise jasmin - Initialize Jasmine in your project
        node node_modules/jasmin/jasmin init
    wdio jasmine framework wdio plugin for asmine
        npm install --save-dev @wdio/jasmine-framework

--references :
    more info on jasmine : https://jasmine.github.io/pages/getting_started.html
    

