# PostmanNewmanQA

1.-Clone the repository.

2.-Install the dependencies

npm install -g newman

npm install -g newman-reporter-htmlextra

3.-Execute all the tests
npm run test


If you want to run the tests without a report, you can simply run:

npx newman run ./App/Tests/collection/Todoist.postman_collection.json -e ./App/Tests/envVariables/Todoist.postman_environment.json
