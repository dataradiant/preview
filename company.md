---
layout: mainpage
title: Company
permalink: /company/
order: 5
---

# About DataRadiant

#TODO

## Leadership

#TODO names and pics, 1 sentence each


## Contact Us

#TODO Address and contacts.

<form action="https://formspree.io/info@dataradiant.com"
      method="POST">
    <input type="text" name="name" placeholder="Your name">
    <input type="email" name="_replyto" placeholder="Your email address">
    <input type="text" name="phone" placeholder="Your phone number">
    <select name="_subject">
    	<option selected="selected">General inquiry</option>
    	<option>Service inquiry</option>
    	<option>Press inquiry</option>
    </select>
    <textarea name="text" placeholder="Your message"></textarea>
    <input type="hidden" name="_next" value="/thanks/" />
    <input type="text" name="_format" value="plain" style="display:none" />
    <input type="submit" value="Send">
</form>
