# Test-Cases Samples

Below are some Test Cases samples that I wrote for login functionality for a website

--------------------------------------
**Title**
Test login with correct credentials

**Description**
Check if the login works with a person users a correct user/pass.

**Steps to Reproduce**
1. Go to https://myelectrica.ro/index.php?pagina=login
2. Add a correct user/pass
3. Press "Acceseaza" button

**Expected result**
User should be able to login and is taken to his profile page.

**Test Data**
User: Ioana & pass:ioana99


-----------------------------------------
**Title**
Test login with incorrect user

**Description**
Check if the login works when a person users a incorrect user.

**Steps to reproduce**
1. Go to https://myelectrica.ro/index.php?pagina=login
2. Add a incorrect user
3. Press "Acceseaza"

**Expected result**
You get an error message

**Test Data**
User: Ioana & pass:ioana99

----------------------------------------
**Title**
Test login with incorrect pass

**Description**
Check if the login works when a person users a incorrect pass.

**Steps to reproduce**
1. Go to https://myelectrica.ro/index.php?pagina=login
2. Add a incorrect pass
3. Press "Acceseaza"

**Expected result**
You get an error message

**Test Data**
User: Ioana & pass:ioana99

----------------------------------------
**Title**
Test forgot password

**Description**
Check if forgot password functionality works as expected and as email with reset password link is sent.

**Steps to reproduce**
1. Go to https://myelectrica.ro/index.php?pagina=login
2. Press "Ai uitat parola?" button
3. Add an email adsress
4. Press "OK" button

**Expected result**
User should receive an email with a reset password link. That link should allow the user to create a new password.

----------------------------------------
**Title**
Test forgot user

**Description**
Check if forgot user functionality works as expected and as email with reset user link is sent.

**Steps to reproduce**
1. Go to https://myelectrica.ro/index.php?pagina=login
2. Press "Ai uitat utilizator?" button
3. Add an email address
4. Press "Recupereaza" button

**Expected result**
User should receive an email with a reset user link. That link should allow the user to create a new user.



