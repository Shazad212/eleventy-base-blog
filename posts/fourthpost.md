---
title: Working with Forms 
description: This is a post on My Blog about working with forms.
date: 2021-25-05
tags: second tag
layout: layouts/post.njk
---

In this blog post, I have created a form using the HTML <b>Form</b> element. The <b>Form</b> element is a container for different types of <b>Input</b> elements, such as: text fields, checkboxes, passwords, radio buttons, and many more. 

I have demonstrated below a variety of the most commonly used <b>Input</b> elements found on most forms that most people would have come across previously. 
<br>
<form>
    <label for="first_name">First Name</label>
    <input type="text" id="first_name" name="first_name"> 
    <label for="last_name">Last Name</label>
    <input type="text" id="last_name" name="last_name">
    <br>
    <br>
    <label for="email">Email:</label>
    <input type="email" id="email">
     <br>
    <br>
   <label for="password">Password</label>
   <input type="password" id="password" name="password" placeholder="required">
       <label for="confirm_password">Confirm Password</label>
   <input type="confirm_password" id="confirm_password" name="confirm_password" placeholder="required">
    
<br>
    <br>
    <p>Select which magazine's you'd like to subscribe to</p>
    
<input type="checkbox" id="mens_health" name="mens_health">
    <label for="mens_health">Mens Health</label>
    <br>
    <input type="checkbox" id="nat_geo" name="nat_geo">
    <label for="nat_geo">National Geographic</label>
    <br>
    <input type="checkbox" id="time_mag" name="time_mag">
    <label for="time_mag">TIME</label>
     <br>
    <br>
    <p>Please select a date you would like your subscribtions to start</p>
    <label for="sub_start">Date for Subscribtion to Start</label>
    <input type="date" id="sub_start" name="sub_start" max="2021-12-31">
     <br>
    <br>
    <p>Please select if you agree to our terms and conditions</p>
    <input type="radio" id="yes" name="tandc" value="yes">
    <label for="yes">Yes</label>
    <input type="radio" id="no" name="tandc" value="yes">
    <label for="no">No</label>
</form>