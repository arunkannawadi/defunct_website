---
title: Contact
icon: fa-envelope
order: 6
---
<p><center>
	Arun Kannawadi, Ph. D., <br>
	025H Peyton Hall, 4 Ivy Lane, <br>
	Princeton University, Princeton, NJ 08544 <br> <br>
	<b>E-mail:</b> firstnamelastname [at] astro [dot] princeton [dot] edu
	<br> (or) <br>
	lastname [dot] firstname [at] gmail [dot] com
</center></p>
{%- if site.formspree_url -%}
Alternatively, you may use form below. It routes your message via [Formspree.io](https://formspree.io){:target="_blank"}
<form method="post" action="{{ site.formspree_url }}">
  <div class="row">
    <div class="6u 12u$(mobile)"><input type="text" name="name" placeholder="Your name" /></div>
    <div class="6u$ 12u$(mobile)"><input type="text" name="email" placeholder="Your email" /></div>
    <div class="12u$">
      <textarea name="message" placeholder="Type your message"></textarea>
    </div>
    <div class="12u$">
      <input type="submit" value="Send Message" />
    </div>
  </div>
</form>
{%- endif -%}
