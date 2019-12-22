# lb4-getting-started


### Install LoopBack 4 CLI

Install the CLI globally by running

    npm i -g @loopback/cli


### Create a new project

    lb4 app

...and answer the prompts as follows:

    ? Project name: getting-started
    ? Project description: Getting started tutorial
    ? Project root directory: (getting-started)
    ? Application class name: StarterApplication
    ? Select features to enable in the project:
    ❯◉ Enable eslint: add a linter with pre-configured lint rules
    ◉ Enable prettier: install prettier to format code conforming to rules
    ◉ Enable mocha: install mocha to run tests
    ◉ Enable loopbackBuild: use @loopback/build helpers (e.g. lb-eslint)
    ◉ Enable vscode: add VSCode config files
    ◉ Enable docker: include Dockerfile and .dockerignore
    ◉ Enable repositories: include repository imports and RepositoryMixin
    ◉ Enable services: include service-proxy imports and ServiceMixin

Press ENTER and show you:

    create .eslintignore
    create .eslintrc.js
    create .mocharc.json
    create .npmrc
    create .prettierignore
    create .prettierrc
    create DEVELOPING.md
    create README.md
    create index.ts
    create package.json
    create tsconfig.json
    create .vscode/settings.json
    create .vscode/tasks.json
    create .gitignore
    create .dockerignore
    create Dockerfile
    create index.js
    create public/index.html
    create src/application.ts
    create src/index.ts
    create src/migrate.ts
    create src/sequence.ts
    create src/__tests__/README.md
    create src/controllers/README.md
    create src/controllers/index.ts
    create src/controllers/ping.controller.ts
    create src/datasources/README.md
    create src/models/README.md
    create src/repositories/README.md
    create src/__tests__/acceptance/home-page.acceptance.ts
    create src/__tests__/acceptance/ping.controller.acceptance.ts
    create src/__tests__/acceptance/test-helper.ts
    npm WARN deprecated superagent@3.8.3: Please note that v5.0.1+ of superagent removes User-Agent header by default, therefore you may need to add it yourself (e.g. GitHub blocks requests without a User-Agent header).  This notice will go away with v5.0.2+ once it is released.
    npm WARN deprecated core-js@2.6.11: core-js@<3 is no longer maintained and not recommended for usage due to the number of issues. Please, upgrade your dependencies to the actual version of core-js@3.

    > ejs@3.0.1 postinstall /home/flavio/codes-nodejs/lb-4-getting-started/node_modules/@loopback/rest-explorer/node_modules/ejs
    > node ./postinstall.js

    Thank you for installing EJS: built with the Jake JavaScript build tool (https://jakejs.com/)


    > core-js@2.6.11 postinstall /home/flavio/codes-nodejs/lb-4-getting-started/node_modules/core-js
    > node -e "try{require('./postinstall')}catch(e){}"


    > ejs@2.7.4 postinstall /home/flavio/codes-nodejs/lb-4-getting-started/node_modules/ejs
    > node ./postinstall.js

    Thank you for installing EJS: built with the Jake JavaScript build tool (https://jakejs.com/)

    npm notice created a lockfile as package-lock.json. You should commit this file.
    npm WARN lb4-getting-started@1.0.0 No license field.

    added 557 packages from 1225 contributors and audited 3992 packages in 18.392s

    18 packages are looking for funding
        run `npm fund` for details

    found 0 vulnerabilities


    Application lb4-getting-started was created in lb-4-getting-started.

    Next steps:

    $ cd lb-4-getting-started
    $ npm start



### Starting the project

    cd lb-4-getting-started
    npm start

Show you:

    > lb4-getting-started@1.0.0 prestart /home/flavio/codes-nodejs/lb-4-getting-started
    > npm run build


    > lb4-getting-started@1.0.0 build /home/flavio/codes-nodejs/lb-4-getting-started
    > lb-tsc


    > lb4-getting-started@1.0.0 start /home/flavio/codes-nodejs/lb-4-getting-started
    > node -r source-map-support/register .

    Server is running at http://[::1]:3000
    Try http://[::1]:3000/ping


I'm try the `http://[::1]:3000/ping` in webbrowser and...

    {
        "greeting":"Hello from LoopBack",
        "date":"2019-12-22T19:20:05.554Z",
        "url":"/ping",
        "headers":{
            "host":"[::1]:3000",
            "connection":"keep-alive",
            "upgrade-insecure-requests":"1",
            "user-agent":"Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/76.0.3809.100 Safari/537.36",
            "sec-fetch-mode":"navigate",
            "accept":"text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3",
            "sec-fetch-site":"none",
            "accept-encoding":"gzip, deflate, br",
            "accept-language":"pt-BR,pt;q=0.9,en-US;q=0.8,en;q=0.7"
        }
    }


### See

[![LoopBack](https://github.com/strongloop/loopback-next/raw/master/docs/site/imgs/branding/Powered-by-LoopBack-Badge-(blue)-@2x.png)](http://loopback.io/)
