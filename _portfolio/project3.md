---
title: Milestone 3
subtitle: Wireframe and Landing Page

caption:
  title: Milestone 3
  subtitle: Wireframe and Landing Page
  thumbnail: assets/img/timeline/M3.jpg
---

### Wireframe

Our application follows a <b>simple and intuitive structure</b>. On the navigation bar we have two buttons, "Home" and "AuNT".
By default, the "Home" section is selected and this is the main page of the application. When the user clicks on the "AuNT" button on the navigation bar, if he is not logged in, he will be redirected to the <b>login page</b>.

<div class="container-fluid">
  <img class="img-fluid" src="assets/img/wireframes/login.png"/>
</div>

Here, the user is prompted for a <b>username</b> and a <b>password</b>. At the bottom of the form, there are two buttons and a link. After inserting the credentials, the user can click on the "Login" button.
If he does not have an account, he will click on the "Register" button. If he forgot his password, he will click on the "Forgot password?" link and will be sent an email with a code which he will use to generate a new password.
On the <b>register page</b>  the user is prompted for an email, a username, a password and a password confirmation. After filling out the form, the user can click on the "Register" button in which case he will be redirected to the configuration translation page. Also, if the user already has an account, he can click on the "Login" link and will be redirected back to the login page.

<div class="container-fluid">
  <img class="img-fluid" src="assets/img/wireframes/register.png"/>
</div>

After signing up or signing in, the user is finally granted access to the configuration translation tool page.

<div class="container-fluid">
  <img class="img-fluid" src="assets/img/wireframes/main.png"/>
</div>

The page is split into <b>two components</b>. On the left side, the user must select the <b>source vendor</b> from a dropdown list and must paste his current configuration on that vendor's device. On the right side, the user must select the <b>destination vendor</b> which he wants the pasted configuration to be translated for. Similarly, the outcome will be available to the user in a textbox underneath.

<div class="container-fluid">
  <img class="img-fluid" src="assets/img/wireframes/upload.png"/>
</div>

The user can also choose to <b>upload a file</b> with his current configuration by clicking the bottom left button "Upload a file", in which case he will be prompted to choose one or more files from his current device. The files will be read and automatically translated into the new vendor's configuration.


### Landing page
You can access AuNT's landing page <a href="https://TODO" target="_blank">here</a>.