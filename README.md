# PostmanNewmanQA

1. Clone the repository.
2. Install the dependencies

<code>npm install --save-dev newman</code>

<code>npm install --save-dev newman-reporter-htmlextra</code>

3. Execute all the tests

<code>npm run test_all_report</code>

If you want to run the tests without a report, you can run:

<code>npx newman run './Tests/collection/Backend_Challenge.postman_collection.json' -e './Tests/envVariables/Sandbox.postman_environment.json'</code>
