---
title: "Contact"
draft: false
---

Intentando insertar un formulario de contacto. No funciona.  

Va a ser necesario usar shortcodes , partials, o de ultima, meterlo en el menu o algo así.  

No funca. Revisar estas pages:  
  
https://gohugo.io/templates/shortcode-templates/#single-named-example-image  
  
https://discourse.gohugo.io/t/use-a-partial-inside-a-markdown-file/34831/3  
  
https://discourse.gohugo.io/t/5-ways-to-handle-forms-on-your-static-site/12447/4  

https://medium.com/getform-all-about/how-to-add-a-contact-form-to-your-hugo-website-84ea79683399  

https://getform.io/f/53c59430-5b30-4aac-9178-346fc34b513b  



<form action="https://getform.io/f/{YOUR-FORMENDPOINT-GOES-HERE}" 
method="POST"
accept-charset="UTF-8">

<input type="text" name="fullname">
<input type="email" name="email">
<input type="text" name="message">

<button type="submit">Send</button>

</form>


<form 
action="https://getform.io/f/53c59430-5b30-4aac-9178-346fc34b513b" 
method="POST" 
enctype="multipart/form-data"
>
<input type="text" name="name" placeholder="name">
<input type="email" name="email" placeholder="Email">
<input type="subject" name="subject" placeholder="name">

</form>