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

## Changes required

Please complete the following tasks to help improve our mock customer ticket creation form.

1. Add conditional formatting to the form

-   The Credit Card Number field should only be shown when the user selects "Credit Card" as their product type
-   The Personal Loan Account Number should only be shown when the user selects "Personal Loan Account Number" as their product type

2. Add validation to all fields marked with a \*

-   Validation should be triggered on blur and also on submit.
-   Validation should trigger a custom message to inform customers
-   Date of birth should be checked to ensure the customer is over 18 years old
-   Credit card account number should be
-   Hidden fields should not be validated

3. Handle submit

-   Upon submit, show the success message to customers

## Submitting

1. Push your final changes
2. Send us a link to your forked repo with the changes
