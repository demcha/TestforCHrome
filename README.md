# TestforCHrome
Test cases for registration process in Chrome browser.
## Preconditions for test :
1. Google Chrome browser instaled on user computer.
2. Internet connection on on user computer.
3. Valid user email adress.
### Test cases: 
| Number | Active | Expected result(positive) | Negative result  | Test result |
| :---: | :---: | :---: | :---: | :---: |
| 1 |Run up the browserChrome on user computer  | Opened Google Chrome browser  |GChrome browser cannot run up| |
| 2 | Input https://github.com to adress line for new page and run   | Will open GitHub home page  | Page not found, user make mistake when input the adrees | |
| 3 |Find button "Sign up" in top right corner of the page  | Button "Sign up" placed in top right corner  |There is no that button on the page | |
| 4 | Press the button "Sign up"  | Will open the registration page | Nothing is happend, button doesn't work| |
| 5 | Create and input user name to first input line for create new account | User name is avialible  | User name is not avialible, or input with mistake | |
| 6 | Input valid user email for create new account to second input line  | User email is valid  | User make mistake in email adress, system take it as valid, but at last user cannot confirm email at the finish of registration| |
| 7 | Create and input password to third input line(User can use recomendation for creation password)  | New user password is strong   |Password is not strong and user have to use recommendation for make it stronger| |
| 8 | User can choose or no "Email preference"  | User choose that option if want | Option is not active for choosing| |
| 9 | Verify account test for user | User must verify fast and right  |User can make it slowely or wrong, and fall down the test| |
| 10 | Choose creation organization account or not | If user consist in organization, must choose this mark   | Option is not active for choosing | |
| 11 | Press button "Next: selected a plan" | Will open new page with next steps registration |If user make any mistake, and forget correct the error, button will not activity, next step is impossible  | |
| 12 | Choose a plan button | User can choose a type of plan "Free" or "Pro" and press button which user decide to choose. Button PRO must open the payment system window.  |Payment system window doesn't opened| |
| 13 | Press button "Free" plan | Will open "Welcome page" | Nothing is happend  | |
| 14 | Choose programming expiriens buttons | User can choose 1 of 4 buttons with types of experiences | User can choose more than 1 type, or cannot choose at all  | |
| 14 | Choose buttons for using GITHUB in    | User can choose 3 of 8 buttons with types of using plans | User can choose more than 3 type, or cannot choose at all  | |
| 15 | Input interesting topics for user     | User can input all interesting topics and tags for using Github updates and news  | Input line is not active. User can input anything on any language, system take it as interesting topics and tags  | |
| 16 | Verify Email ask    | User must verify email in email-box, Create repository ask page will open  | If user make mistake in paragraph 6., user will not get a verify ask lettter   | |

