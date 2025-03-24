# React Site provisioning

This project is meant to be reused accross different crm customers. Upon successful purchase, a workflow in this project runs, building the react app and then uploading the ubild files to to the customer s3 bucket. 

This workflow will be triggered by a lambda function which listens for a successful step 1 (terraform creates initial aws resources). 

## Workflow commands

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.


