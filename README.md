# Telosys 3 VueJS Front Template

A Telosys Tools 3 Template of a VueJS front application, able to perform CRUD (Create, Read, Update, Delete) operations over a REST API.

## Installation

1. Download the template.  
2. Provide your DSL model.  
3. Define the variables ProjectVariable.REST_URL_ROOT and ProjectVariable.REST_API_ROOT in telosys-tools.cfg  
For example :  
`ProjectVariable.REST_URL_ROOT=http://localhost:3000`  
`ProjectVariable.REST_API_ROOT=/api/v1`  
4. Generate the code with Telosys.  
5. Navigate to the generated code's root folder.  
6. Install the dependencies with the following command : `npm install`  

## Requirements

- [NodeJS](https://nodejs.org/en/) to run the application.
- [Npm](https://www.npmjs.com/) to install dependencies (see the full list below at "Dependencies").

## Getting started

For DEVELOPEMENT  :  
1. Install this application (See Installation).
2. Start the server with : `npm run dev`
3. Your browser should open the application.

For PRODUCTION :  
1. Build the application with : `npm run build`  
2. The production files will be built in a /dist folder  
3. Upload the files from the /dist folder to your server and you're done.  

## Credits

- Made by [Romuald Tuffreau](https://github.com/romwaldtff).

## Thanks

- [Laurent Guerin](https://github.com/l-gu), creator of [Telosys Tools](http://www.telosys.org/).

## License

This project uses the [LGPL v3 License](https://www.gnu.org/licenses/lgpl-3.0.en.html).
