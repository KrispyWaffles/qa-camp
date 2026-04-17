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


TC-001 | [Title]
Preconditions: [what must be true before this test runs]
Steps:
  1.
  2.
Expected result:
Status: Pass / Fail / Blocked


TC-001 | [Title]
Preconditions: [what must be true before this test runs]
Steps:
  1.
  2.
Expected result:
Status: Pass / Fail / Blocked


TC-001 | [Title]
Preconditions: [what must be true before this test runs]
Steps:
  1.
  2.
Expected result:
Status: Pass / Fail / Blocked


TC-001 | [Title]
Preconditions: [what must be true before this test runs]
Steps:
  1.
  2.
Expected result:
Status: Pass / Fail / Blocked


TC-001 | [Title]
Preconditions: [what must be true before this test runs]
Steps:
  1.
  2.
Expected result:
Status: Pass / Fail / Blocked