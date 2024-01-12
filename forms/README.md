## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
The action attribute in the form tag is used to specify the server URL to which the data will be sent when the form is submitted.
2. What is the purpose of the _method_ attribute in the _form_ tag?
The method attribute in the form tag determines how data is sent to the server. Common examples are GET (sent via URL) and POST (sent via HTTP request).
3. What is the purpose of the _name_ attribute in the _input_ tag?
The name attribute in the input tag names the input fields and is used to identify the different data fields when the form is submitted.
4. What is the purpose of the _type_ attrbute in the _input_ tag?
The type attribute in the input TAB defines the type of the input field, such as text, password, or button.
5. What is the purpose of the _label_ tag?
The label label defines labels for input elements to improve the readability and accessibility of forms.
6. What is the purpose of the _required_ attribute?
The required attribute is a Boolean attribute that indicates the fields that must be filled in before the form can be submitted.
