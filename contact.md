---
layout: default
title: Contact Matt
---
 
## Send an e-mail to Matt

Please fill out the form below with a short e-mail,

and Matt will respond back as soon as possible.

<form id="contactform" method="POST">
	  
	<input type="hidden" name="_subject" value="MattFerris.com Contact Form Submission" />  	  
    <input type="text" name="name" placeholder="Your name" >
	<input type="email" name="_replyto" placeholder="Your email" >
	
	
	<textarea name="message" rows="5" placeholder="Enter your message"></textarea>
    <input type="submit" value="Send">
	<input type="hidden" name="_next" value="//mattferris.com/thanks.html" />
</form>

<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'matt' + '@' + 'mattferris' + '.' + 'com');
</script>

#  
