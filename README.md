# The BMI challenge  
## Built with  
**Front end:** Vanilla JS, HTML and CSS.    
**Back end:** N/a  
**Testing:** [E2E Training Wheels](https://www.npmjs.com/package/e2e_training_wheels)  

## About this repository  
This BMI calculator can be used to calculate a person's Body Mass Index (BMI) for both mertric and imperial units. BMI is often used as a risk indicator of developing noncommunicable diseases (NCDs) like cardiovascular disease and diabetes. You can learn more about the BMI and how to interpret it from the [World Health Organization](http://www.euro.who.int/en/health-topics/disease-prevention/nutrition/a-healthy-lifestyle/body-mass-index-bmi).

## Deployment 
This BMI calculator is currently deployed online from [Netlify](https://pure-js-bmi-calculator.netlify.com/).  

## Getting started

To test this application you need to fork it to your own GitHub account and clone it to your local workspace.

### Prerequisites

To test the methods and features of this calculator you need to have the JS testing framework E2E Training Wheels installed and configured on your local computer. Step by step instructions in both text and video format can be found at this [Training Wheels repository](https://www.npmjs.com/package/e2e_training_wheels).  

_Please note that your current Node version should be version 10.2.0 or higher._  

### Running the tests  

The acceptance tests for this application can be found inside of the **features** folder. Enter the following command into your terminal to run the tests:

> $ npm run features  

The above command will launch Chrome and run the acceptance tests on a local webserver.

To execute the unit tests for the _Person class_ and the _BMI Calculator class_ that are found inside of the **spec** folder, execute the following command.

>$ npm run specs

Finally, to execute both the acceptance tests and unit tests enter the following command.

>$ npm test

## Acknowledgements  
This challenge was given to me by the team at [CraftAcademy](https://craftacademy.se/).  
