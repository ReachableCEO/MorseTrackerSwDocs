
##### Related Documents

- [SRS](SRS) > [Use Case Suite](Use-Case-Suite) > Use Case Format

---

**Process impact:** This reference page documents the format of use
cases and gives tips on writing use cases. You can copy and paste the
sample use case into your [Use Cases](Use-Cases) document. This
file itself should not be edited to hold specific use cases.

*TODO: Use this template once in your [Use Cases](Use-Cases)
document. Anything you mention here will apply to all use cases in that
file.*

---

### Aspects common to all use cases

**Direct Actors:**

- ::User: end-user in any role
- ::System: The system being built
- ::When actors are not listed, assume User is doing it.
- ::Items beginning with &quot;see&quot; indicate that System has presented a new screen.

**Stakeholders:**
::The user who is entering the data, and those who will read it

**Prerequisite:**
::Project is set up

*TODO: Copy and paste this use case template as many times as needed in
your [Use Cases](Use-Cases) document. Only use those fields that
are not the same as the default for all use cases.*

---

### UC-00: USE CASE NAME

**Summary:**

::1-3 SENTENCES

**Priority:**

::Essential | Expected | Desired | Optional

**Use Frequency:**

::Always | Often | Sometimes | Rarely | Once

**Direct Actors:**

::ACTOR1, ACTOR2, ACTOR3

**Stakeholders:**

::STAKEHOLDER, STAKEHOLDER, STAKEHOLDER

**Prerequisite:**

- ::PRECONDITION
- ::PRECONDITION
- ::PRECONDITION

**Main Success Scenario:**

- ::STEP
- ::STEP
- ::STEP

**Alternative Scenario Extensions:**

- ::If CONDITION, then ALTERNATIVE STEPS.
  - ::NOTES or DETAILS.

- ::If CONDITION, then ALTERNATIVE STEPS.
  - ::NOTES or DETAILS.

**Notes and Questions:**

- ::NOTE
- ::NOTE
- ::QUESTION
- ::QUESTION

---

### Format of Use Case Steps

Try to start each step with one of these action words:

#### login \[as ROLE or USER\]

Log into the system with a given user or a user of the given type.
Usually usually only stated explicitly when the test case involves a
workflow between different users.

#### visit LOCATION

Visit a page or GUI window. State the user's intention, don't say
too much about UI choices that could change later. E.g., WRONG:
"Press the 'Advanced...' button on the File | Page Setup dialog".
RIGHT: "Visit the page margin configuration dialog".

#### enter INFORMATION

Fill in specific information. Try to state the information in
some detail. E.g., WRONG: "Enter customer information." RIGHT:
"Enter customer shipping address and discount code." Don't commit to
details of a particular UI, i.e., don't name specific UI fields that
might change later.

#### COMMAND

Describe a command that the user can tell the system to do. State
the user's intent, not the label on a particular UI widget. This
will usually be followed by a "see" step where the user sees a
confirmation of their action. E.g., WRONG: "Control-P, OK". RIGHT:
"Print the current document with default settings".

#### see CONTENT

The user should see the specified information on the currently
presented web page or GUI window. Try to be specific about the
information that is seen, but try not to refer to specific
UI elements. E.g., WRONG: "see UserList.jsp" (what is the user
supposed to notice on that page?) RIGHT: "see list of users with the
newly added user in the list".

#### perform USE-CASE-NAME

This is like a subroutine call. The user will do all the steps of
the named use case and then continue on with the next step of this
use case.

### Further Information

For more information on advice, see:

- Words of wisdom on [use case suites](http://readyset.tigris.org/words-of-wisdom/use-case-suite.html).
- Words of wisdom on [use cases](http://readyset.tigris.org/words-of-wisdom/use-cases.html).
