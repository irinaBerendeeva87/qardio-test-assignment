---
> Actions with the list
---

№ PC1  **User does to profile by  navigation icon.**

**Steps 1**: 
1. Open the app.

**Expected results 1**:
1. The app opened.
2. User on a page Home.

**Steps 2**:  
1. Tap on hamburger button.
2. Tap on navigation header.
   
**Expected results 2**:
1. Profile page is opened.
2. User data is displayed on the page.

---

№ PC2 **Change the user's gender by dropdown menu.**

**Preconditions**:
1. Open the app.
2. Go to user profile.

**Steps**: 
1. Tap on a field "Sex"
2. Choose Male or Female in dropdown.
3. Tap on a save button

**Expected results**:
1. New data displayed on a  field.
2. New data saved.

---

№ PC3 **Change the user's email.**

**Preconditions**:
1. Open the app.
2. Go to user profile.
3. The profile contains an email. 

**Steps**:
1. Tap on a field "Email"
2. Delete last email.
3. Add a new email.
4. Tap on a save button.

**Expected results**:
1. New email displayed on a  field.
2. New data saved as user entered.

---

№ PC4 **Error when saving an empty Email field**

**Preconditions**:
1. Open the app.
2. Go to user profile.
3. The profile contain an email.

**Steps**:
1. Tap on a field "Email"
2. Delete last email.
3. Tap on a save button.

**Expected results**:
1. Error message displayed on a  field.
2. Empty Email field wasn't saved.

---

№ PC5 **Email confirmation after changing email to profile.**

**Preconditions**:
1. Open the app.
2. Go to user profile.
3. The profile contain  an email.

**Steps**:
1. Tap on a field "Email"
2. Delete last email.
3. Add a new email.
4. Tap on a save button.

**Expected results**:
1. New email displayed on a field.
2. New email saved as user entered.
3. User got an email with confirmation the new email adress.

---

№ PC6 **Change the user's password.**

**Preconditions**:
1. Open the app.
2. Go to user profile.
3. The profile contain a password.

**Steps**:
1. Tap on a field "Password"
2. Delete last password.
3. Add a new password with alphanumeric characters - asdf342   
4. Tap on a save button.

**Expected results**:
1. New password displayed on a  field.
2. New password saved as user entered.

---

№ PC7 **Error when saving a new password with only numbers**

**Preconditions**:
1. Open the app.
2. Go to user profile.
3. The profile contain a password.

**Steps**:
1. Tap on a field "Email"
2. Delete last email.
3. Add a new password with numbers characters - 543342.
4. Tap on a save button.

**Expected results**:
1. Error message displayed on a  field.
2. Incorrect password wasn't saved.

---

№ PC8 **Error when saving an empty Password field**

**Preconditions**:
1. Open the app.
2. Go to user profile.
3. The profile contain a password.

**Steps**:
1. Tap on a field "Email"
2. Delete last password.
3. Tap on a save button.

**Expected results**:
1. Error message displayed on a  field.
2. Empty Password field wasn't saved.

---

№ PC9 **Default value of height in inches**

**Preconditions**: New user. 
**Steps**: Open the Profile page.
**Expected results**:
 User's height is in inches.

---

№ PC10 **Change data and unit of measure  for weight per kg.**

**Preconditions**:
1. Open the app.
2. Go to user profile.
3. The profile contain a user's weight.

**Steps**:
1. Tap on a field "Weight"
2. Add a new data 100
3. Choose kg in dropdown
4. Tap on a save button.

**Expected results**:
1. Measure cm displayed on a field.
2. New data saved.

---

№ PC11 **User can change the date of birth in the profile**

**Preconditions**:
1. Open the app.
2. Go to user profile.
3. The profile contain a user's birthday.

**Steps**:
1. Tap on a field "Date of birth"
2. Choose a new date 21.09.1987 in date picker
4. Tap on a save button.

**Expected results**:
1. New birthday displayed on a field.
2. New data saved.

---

№ PC12 **User can't change birthday to non-existent date in profile**

**Preconditions**:
1. Open the app.
2. Go to user profile.
3. The profile contain a user's birthday.

**Steps**:
1. Tap on a field "Date of birth"
2. Choose a new date 21.09.2023 in date picker

**Expected results**:
Date picker doesn't allow you to choose the next year.

---

№ PC13 **After the changes, the data is displayed on navigation header**

**Preconditions**:
1. Open the app.
2. Go to user profile.

**Steps**:
1. Tap on a field "First name"
2. Change name on  Lassy.
3. Tap on a save button.
4. Tap on hamburger button.

**Expected results**:
1. New first name saved.
2. New first name displayed on navigation header.

---

№ PC14 **Displaying the profile after returning to the app.**

**Preconditions**:
2. Go to user profile.
2. Hide app.

**Steps**:
1. Back to app

**Expected results**:
1. The app opened.
2. Profile is displayed on the screen .

---

№ PC15 **User can paste the copied word.**

**Preconditions**:
1. Copy the word **world** from another app
2. Open the app
3. Go to user profile

**Steps**:
1. Paste copied word in the input field.

**Expected results**:
New word was displayed in the input field

---

№ PC16 **User can't  save data without  entering required fields**

**Preconditions**:
1. Open the app.
2. Go to user profile.

**Steps**:
1. Delete email/first name from  fields

**Expected results**:
Save data button is disabled.

