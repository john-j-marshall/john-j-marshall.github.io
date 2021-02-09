---
layout: page
title: Contact
permalink: /contact/
---

<form accept-charset="UTF-8" action="#" method="POST" enctype="multipart/form-data" target="_blank">
    <div class="contact-form-group">
        <label for="name">Name</label>
        <input type="text" name="name" class="form-control" id="exampleInputName" placeholder="Enter your name" required="required">
    </div> 
    <div class="contact-form-group">
        <label for="email" required="required">Email address</label>
        <input type="email" name="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
    </div>
    <div class="contact-form-group">
        <label for="subject">Message</label>
        <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>     
    </div>
    <hr>
    <button type="submit" class="btn btn-primary">Submit</button>
</form>
