🪲 BPQ 1

### The email is saved differently than the user specified.

**Devices**:Samsung A6+

**OS:** Android

**Version ОС:**  any

**Version:** 2.2.3

**Frequency of reproduction:** always

**Test case**: № PC3 Change the user's email
**Preconditions:**
1. Open the app.
2. Go to user profile.
3. The profile contains an email.
4. Delete last email.

**Steps to reproduce:** 
1. Add a new email irina.irina@gmail.c
2. Tap save button

**❌ Actual result:** email was saved - irina.irina@gmail.com

**✅ Expected result:** email is save - irina.irina@gmail.c

---

🪲 BPQ 2

### Don't receive a confirmation email after changing the email.

**Devices**:Samsung A6+

**OS:** Android

**Version ОС:**  any

**Version:** 2.2.3

**Frequency of reproduction:** always

**Test case**: PC5 Email confirmation after changing email to profile.
**Preconditions:**
1. Open the app.
2. Go to user profile.
3. Delete last email.

**Steps to reproduce:**
1. Add a new email irina.irina@gmail.com
2. Tap save button

**❌ Actual result:** 
1. Email was saved - irina.irina@gmail.com
2. Email confirmation not received

**✅ Expected result:** User got an email with confirmation the new email adress  on a new email address.

---

🪲 BPQ 3

### User can save password only from numbers.

**Devices**:Samsung A6+

**OS:** Android

**Version ОС:**  any

**Version:** 2.2.3

**Frequency of reproduction:** always

**Test case**: PC7 Error when saving a new password with only numbers.
**Preconditions:**
1. Open the app.
2. Go to user profile.
3. Delete last password.

**Steps to reproduce:**
1. Add a new password 111111
2. Tap save button

**❌ Actual result:** Password was saved

**✅ Expected result:** 
1. Save button is not activ.
2. Аn error message appears

---

🪲 BPQ 4

### Default height of a new user is in cm.

**Devices**:Samsung A6+

**OS:** Android

**Version ОС:**  any

**Version:** 2.2.3

**Frequency of reproduction:** always

**Test case**: PC9 Default value of height in inches.

**Preconditions**: New user.

**Steps to reproduce:** Open the Profile page.

**❌ Actual result:** User's height is in cm.

**✅ Expected result:**
User's height is in inches.

---

🪲 BPQ 5

### Home page is displayed after returning to the app instead of the Profile.

**Devices**:Samsung A6+

**OS:** Android

**Version ОС:**  any

**Version:** 2.2.3

**Frequency of reproduction:** always

**Test case**: PC14 Displaying the profile after returning to the app.

**Preconditions:**
1. Open the app.
2. Go to user profile.
3. Hide app.

**Steps to reproduce:** Back to app.

**❌ Actual result:** The app opened on a home page.

**✅ Expected result:** Profile is displayed on the screen .
