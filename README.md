# MoneyLion
Create a single page application using ReactJs framework to onboard
users to the MoneyLion Account.
The onboarding flow consists of 4 screens.
1. Welcome Screen (onboard-test.moneylion.com/welcome)
2. Personal Details (onboard-test.moneylion.com/personal)
3. Date of Birth (onboard-test.moneylion.com/dob)
4. Agreements (onboard-test.moneylion.com/agreement)
UI Reference:
https://www.figma.com/file/awHuIluCer7SQnWUCBTxPy/onboarding-test?node-id=0%3A1
Requirements:
1. Users are able to resume to the last screen after drop off.
2. Screen must be in order.
3. All the user information should be submitted to the following endpoint on Agreements
Screen.
Endpoint: https://5f79819fe402340016f93139.mockapi.io/api/user
Method: POST
Body:
{
"firstName": "string",
"lastName": "string",
"Email":"string",
"agreement1": "boolean",
"agreement2":"boolean"
}
Your answer should be committed to a git repository.
Note:
1. The UI is just for a reference, you’re not required to follow exactly (including
dimension, css)
