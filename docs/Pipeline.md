# The structure and functional flow of the pipeline
1. we need to install nodejs , aws-elastic-beanstalk and aws-cli
 ## The pipeline start as follow
 1. Install Front-End Dependencies by running `npm run frontend:install`
 2. Install API Dependencies by running `npm run api:install`
 3. Front-End Lint by running `npm run frontend:lint`
 4. Front-End Build by running `npm run frontend:build`
 5. API Build by running `npm run api:build`
 6. Deploy in both apps by running `npm run deploy`