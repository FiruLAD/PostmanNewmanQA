# PostmanNewmanQA

1. Clone the repository.
2. Install the dependencies

<code>npm install -g newman</code>

<code>npm install -g newman-reporter-htmlextra</code>

3. Execute all the tests

<code>npm run test</code>

If you want to run the tests without a report, you can simply run:

<code>npx newman run ./App/Tests/collection/Todoist.postman_collection.json -e ./App/Tests/envVariables/Todoist.postman_environment.json</code>
