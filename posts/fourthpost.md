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
    <input type="text" id="first_name" name="first_name" required="required" minlength="2"> 
    <label for="last_name">Last Name</label>
    <input type="text" id="last_name" name="last_name" required="required" minlength="2">
    <br>
    <br>
    <label for="email">Email:</label>
    <input type="email" id="email" required="required">
    <br>
    <br>
    <label for="phone">Telephone Number:</label>

<input type="tel" id="phone" name="phone" required="required">
    <br>
<br>
<label for="country_select">Country</label>
<select name="country" id="country_select" required="required">
    <optgroup label="United Kingdom">
    <option value=" ">--Please Select an Option--</option>
    <option value="England">England</option>
    <option value="Wales">Wales</option>
    <option value="Scotland">Scotland</option>
    <option value="Northern Ireland">Northern Ireland</option>
    </optgroup>
    <optgroup label="Europe">
        <option value="France">France</option>
        <option value="Spain">Spain</option>
        <option value="Italy">Italy</option>
    </optgroup>
</select>
    
<br>
    <br>
    <p>Select which magazine's you'd like to subscribe to</p>
    
<input type="checkbox" id="mens_health" name="mens_health" required="Please select an option">
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
    <input type="date" id="sub_start" name="sub_start" max="2021-12-31" required="required">
     <br>
    <br>
    <p>Please select if you agree to our terms and conditions</p>
    <input type="radio" id="yes" name="tandc" value="yes" required="required">
    <label for="yes">Yes</label>
    <input type="radio" id="no" name="tandc" value="yes" required="required">
    <label for="no">No</label>
    <br>
    <br>
   <label for="password">Password</label>
   <input type="password" id="password" name="password" placeholder="required" required="required" minlength="6" maxlength="25" required: upper; required: lower; required: digit>
       <label for="confirm_password">Confirm Password</label>
   <input type="password" id="confirm_password" name="confirm_password" placeholder="required" required="required">
   <br>
    <br>  
    <input type="submit" value="Submit">

</form>