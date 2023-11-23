##### Project

::[PROJECT-NAME](Home)

##### Internal Release Number

::X.Y.Z

##### Related Documents

[QA Plan](QA-Plan) > [Test Suite](Test-Suite) > Test Cases
[System test case format](Test-Case-Format)
::LINKS TO RELEVANT STANDARDS
::LINKS TO OTHER DOCUMENTS

---

### login-1: Normal User Login

**Purpose:**

::Test that users can log in with the proper username or
email address and their password.

**Prerequisite:**

::User is not already logged in.

::User test-user exists, and account is in good standing.

**Test Data:**

::usernameOrEmail = {test-user, bogus-user, test-user@nospam.com,
test@user@nospam.com, empty}

::password = {valid, invalid, empty}

**Steps:**

::Steps to carry out the test. See step formating rules below.

- ::visit LoginPage
- ::enter userID
- ::enter password
- ::click login
- ::see the terms of use page
- ::click agree radio button at page bottom
- ::click submit button
- ::see PersonalPage
- ::verify that welcome message is correct username

**Notes and Questions:**

- ::This assumes that user has not agreed to terms-of-use already.
- ::Does this work without browser cookies?

---

### login-2: Locked-out User Login

**Purpose:**

::Test that a user who has been locked out by a moderator, cannot
log in, They should see a messagaddede indicating that they were locked
out.

**Prerequisite:**

::User is not already logged in.
::User test-user2 exists, and has been locked out

**Test Data:**

::usernameOrEmail = {test-user2, test-user2@nospam.com}
::password = {valid}

**Steps:**

::Steps to carry out the test. See step formating rules below.

- ::visit LoginPage
- ::enter usernameOrEmail
- ::enter password
- ::click Login
- ::see LoginPage
- ::verify warning message is the locked-out message

**Notes and Questions:**

- ::Does this work without browser cookies?

---

### unique-test-case-id1: Test Case Title

**Purpose:**

::Short sentence or two about the aspect of the system is
being tested. If this gets too long, break the test case
up or put more information into the feature descriptions.

**Prerequisite:**

::Assumptions that must be met before the test case can be run.
E.g., &quot;logged in&quot;, &quot;guest login allowed&quot;,
&quot;user test-user exists&quot;.

**Test Data:**

::List of variables and their possible values used in the test case.
You can list specific values or describe value ranges. The test case
should be performed once for each *combination* of values. These
values are written in set notation, one per line. E.g.:

- loginID = {Valid loginID, invalid loginID, valid email, invalid
  email, empty}
- password = {valid, invalid, empty}

**Steps:**

::Steps to carry out the test. See step formating rules below.

- ::visit LoginPage
- ::enter userID
- ::enter password
- ::click login
- ::see the terms of use page
- ::click agree radio button at page bottom
- ::click submit button
- ::see PersonalPage
- ::verify that welcome message is correct username

**Notes and Questions:**

- ::NOTE
- ::QUESTION

---

### unique-test-case-id2: Test Case Title

**Purpose:**

::Short sentence or two about the aspect of the system is
being tested. If this gets too long, break the test case
up or put more information into the feature descriptions.

**Prerequisite:**

::Assumptions that must be met before the test case can be run.
E.g., &quot;logged in&quot;, &quot;guest login allowed&quot;,
&quot;user test-user exists&quot;.

**Test Data:**

::List of variables and their possible values used in the test case.
You can list specific values or describe value ranges. The test case
should be performed once for each *combination* of values. These
values are written in set notation, one per line. E.g.:

- ::loginID = {Valid loginID, invalid loginID, valid email, invalid
  email, empty}
- ::password = {valid, invalid, empty}

**Steps:**

::Steps to carry out the test. See step formating rules below.

- ::visit LoginPage
- ::enter userID
- ::enter password
- ::click login
- ::see the terms of use page
- ::click agree radio button at page bottom
- ::click submit button
- ::see PersonalPage
- ::verify that welcome message is correct username

**Notes and Questions:**

- ::NOTE
- ::QUESTION

---

### unique-test-case-id3: Test Case Title

**Purpose:**

::Short sentence or two about the aspect of the system is 
being tested. If this gets too long, break the test case 
up or put more information into the feature descriptions.

**Prerequisite:**

::Assumptions that must be met before the test case can be run.
E.g., &quot;logged in&quot;, &quot;guest login allowed&quot;,
&quot;user test-user exists&quot;.

**Test Data:**

::List of variables and their possible values used in the test case.
You can list specific values or describe value ranges. The test case
should be performed once for each *combination* of values. These
values are written in set notation, one per line. E.g.:

- ::loginID = {Valid loginID, invalid loginID, valid email, invalid
  email, empty}
- ::password = {valid, invalid, empty}

**Steps:**

::Steps to carry out the test. See step formating rules below.

- ::visit LoginPage
- ::enter userID
- ::enter password
- ::click login
- ::see the terms of use page
- ::click agree radio button at page bottom
- ::click submit button
- ::see PersonalPage
- ::verify that welcome message is correct username

**Notes and Questions:**

- ::NOTE
- ::QUESTION

---

### unique-test-case-id4: Test Case Title

**Purpose:**

::Short sentence or two about the aspect of the system is
being tested. If this gets too long, break the test case
up or put more information into the feature descriptions.

**Prerequisite:**

::Assumptions that must be met before the test case can be run.
E.g., &quot;logged in&quot;, &quot;guest login allowed&quot;,
&quot;user test-user exists&quot;.

**Test Data:**

::List of variables and their possible values used in the test case.
You can list specific values or describe value ranges. The test case
should be performed once for each *combination* of values. These
values are written in set notation, one per line. E.g.:

- ::loginID = {Valid loginID, invalid loginID, valid email, invalid
  email, empty}
- ::password = {valid, invalid, empty}

**Steps:**

::Steps to carry out the test. See step formating rules below.

- ::visit LoginPage
- ::enter userID
- ::enter password
- ::click login
- ::see the terms of use page
- ::click agree radio button at page bottom
- ::click submit button
- ::see PersonalPage
- ::verify that welcome message is correct username

**Notes and Questions:**

- ::NOTE
- ::QUESTION

---

### unique-test-case-id5: Test Case Title

**Purpose:**

::Short sentence or two about the aspect of the system is
being tested. If this gets too long, break the test case
up or put more information into the feature descriptions.

**Prerequisite:**

::Assumptions that must be met before the test case can be run.
E.g., &quot;logged in&quot;, &quot;guest login allowed&quot;,
&quot;user test-user exists&quot;.

**Test Data:**

::List of variables and their possible values used in the test case.
You can list specific values or describe value ranges. The test case
should be performed once for each *combination* of values. These
values are written in set notation, one per line. E.g.:

- ::loginID = {Valid loginID, invalid loginID, valid email, invalid
  email, empty}
- ::password = {valid, invalid, empty}

**Steps:**

::Steps to carry out the test. See step formating rules below.

- ::visit LoginPage
- ::enter userID
- ::enter password
- ::click login
- ::see the terms of use page
- ::click agree radio button at page bottom
- ::click submit button
- ::see PersonalPage
- ::verify that welcome message is correct username

**Notes and Questions:**

- ::NOTE
- ::QUESTION

---

### unique-test-case-id6: Test Case Title

**Purpose:**
::Short sentence or two about the aspect of the system is
being tested. If this gets too long, break the test case
up or put more information into the feature descriptions.

**Prerequisite:**

::Assumptions that must be met before the test case can be run.
E.g., &quot;logged in&quot;, &quot;guest login allowed&quot;,
&quot;user test-user exists&quot;.

**Test Data:**

::List of variables and their possible values used in the test case.
You can list specific values or describe value ranges. The test case
should be performed once for each *combination* of values. These
values are written in set notation, one per line. E.g.:

- ::loginID = {Valid loginID, invalid loginID, valid email, invalid
  email, empty}
- ::password = {valid, invalid, empty}

**Steps:**

::Steps to carry out the test. See step formating rules below.

- ::visit LoginPage
- ::enter userID
- ::enter password
- ::click login
- ::see the terms of use page
- ::click agree radio button at page bottom
- ::click submit button
- ::see PersonalPage
- ::verify that welcome message is correct username

**Notes and Questions:**

- ::NOTE
- ::QUESTION
