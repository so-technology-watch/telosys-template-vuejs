# Telosys 3 VueJS Front Template

A [Telosys](https://telosys.org) template of a VueJS front application, able to perform CRUD (Create, Read, Update, Delete) operations over a REST API.

## Requirements

- [NodeJS](https://nodejs.org/en/) to run the application.
- [Npm](https://www.npmjs.com/) to install dependencies (see the full list below at "Dependencies").

## Usage

1. Download the template.  
2. Check that your model is ready (DSL/Database).
3. Define the variables ProjectVariable.REST_URL_ROOT and ProjectVariable.REST_API_ROOT in telosys-tools.cfg  
Example :  
`ProjectVariable.REST_URL_ROOT=http://localhost:3000`  
`ProjectVariable.REST_API_ROOT=/api/v1`  
4. Generate the code with Telosys.  
5. Navigate to the generated code's root folder.  
6. Install the dependencies with the following command : `npm install`  


## Getting started

For DEVELOPEMENT  :  
1. Install this application (See Installation).
2. Start the server with : `npm run dev`
3. Your browser should open the application.

For PRODUCTION :  
1. Build the application with : `npm run build`  
2. The production files will be built in a /dist folder  
3. Upload the files from the /dist folder to your server and you're done.  

## License

This project uses the [LGPL v3 License](https://www.gnu.org/licenses/lgpl-3.0.en.html).
