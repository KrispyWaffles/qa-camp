#Test Cases


TC-001 | Valid credentials log user in
Preconditions: FoxAuth login page is open in browser
Steps:
  1. Enter tester@foxreply.com in the email field
  2. Enter Test1234! in the password field
  3. Click Sign in
Expected result: Success message is displayed, password is NOT shown
Status: Fail


TC-002 | Wrong password with valid email
Preconditions: FoxAuth login page open in browser
Steps:
  1. Enter valid email (tester@foxreply.com)
  2. Enter incorrect password
  3. Click Sign in
Expected result: Generic error message that does not reveal
whether the email exists (e.g. "Invalid email or password")
Status: Fail


TC-003 | Wrong email
Preconditions: FoxAuth login page open in browser
Steps:
  1. enter invalid email
  2. password not required
  3. click sign-in
Expected result: Expected result: Generic error message that does not reveal 
whether the email exists (e.g. "Invalid email or password")
Status: Fail


TC-004 | Empty Field
Preconditions: FoxAuth login page open in browser
Steps:
  1. leave email blank
  2. password not required
  3. click sign-in
Expected result: Validation message prompting user to enter an email address
(e.g. "Please enter your email address")
Status: Pass


TC-005 | email with no @ symbol(like typing "hello").
Preconditions: FoxAuth login page open in browser
Steps:
  1. enter word in email field (hello was our test word)
  2. Click "sign in"
 
Expected result:  Message prompting the user to enter a valid email
Status: Fail


TC-006 | Empty password with valid email
Preconditions: FoxAuth login page open in browser
Steps:
  1. enter valid email (tester@foxreply.com)
  2. leave password field blank
  3. click sign-in
Expected result:  Message prompting user to enter a password
(e.g. "Password Required")
Status: Pass


TC-007 | correct credentials but all lowercase password
Preconditions: FoxAuth login page open in browser
Steps:
  1. enter valid email (tester@foxreply.com)
  2. enter password lowercase characters (test1234!)
  3. click sign-in
Expected result:  Message prompting user to enter a valid password
(e.g. "Please enter a valid password")
Status: Fail


TC-008 | Forgot password link clicked
Preconditions: FoxAuth login page open in browser
Steps:
  1. click "forgot password" right about "sign in" button
 
Expected result:  Workflow allowing the user to retrieve or create a new password
Status: Fail


