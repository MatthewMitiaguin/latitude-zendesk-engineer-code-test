# Latitude Zendesk Engineer - Coding test

![Sample Form](https://github.com/mephraums/latitude-zendesk-engineer-code-test/raw/master/images/form.png 'Sample Form')

## Project Setup

1. Fork this repo to your personal Github account.
2. Clone the project
3. Install dependencies: `yarn`
4. Start the dev server: `yarn dev`

## Intro

-   This task is designed to test your comfort levels working with HTML forms, and adding additional functionality using Vanila JS and Jquery.
-   Please complete this task WITHOUT additional MV frameworks such as Angular, Vue or React.
-   You can add any additional jQuery plugins or utility libraries as required eg. lodash, moment.
-   You can add class names and ids to any elements on the page.
-   For convienience, Bootstrap 4 has been included, the focus is not on styling but on the functionality.

## Changes required

Please complete the following tasks to help improve our mock customer ticket creation form.

1. Add conditional display to the form

-   The Credit Card Number field should only be shown when the user selects "Credit Card" as their product type
-   The Personal Loan Account Number should only be shown when the user selects "Personal Loan" as their product type

2. Add form validation

-   All fields marked with a \* are required
-   Validation should be triggered on blur and checked again on form submit.
-   Validation should trigger an error state on the element and a custom message situated below the field to inform customers of the error
-   Date of birth should be checked to ensure the customer is over 18 years old
-   Credit card number should be validated as 16 digits. Bonus marks if you can think of any other validation that may help here.
-   Hidden fields should not be validated

3. Handle submit

-   Upon submit, show the success message to customers - The form data does not need to be sent anywhere

## Submitting

1. Push your final changes to your forked repo
2. Send us a link to your repo on Github with the changes
