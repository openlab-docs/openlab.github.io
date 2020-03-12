---
layout: contact
title: Contact
permalink: /contact
---

<!-- START HERE -->
   <link rel="stylesheet" href="https://unpkg.com/purecss@1.0.0/build/pure-min.css">
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">

  <form class="gform pure-form pure-form-stacked" method="POST" data-email="iris@mobigen.com"
   action="https://script.google.com/macros/s/AKfycbziEMeFJJdZCKSWCKVcITNYXD85H3I9vdVHCNG6pQz7RmbckSSl/exec">

    <div class="form-elements">
      <fieldset class="pure-group">
        <label for="name">Name: </label>
        <input id="name" name="name" class="pure-input-1-3" placeholder="What your Mom calls you" />
      </fieldset>

      <fieldset class="pure-group">
        <label for="message">Message: </label>
        <textarea id="message" name="message" class="pure-input-1-3" rows="10" placeholder="Tell us what's on your mind..."></textarea>
      </fieldset>

      <fieldset class="pure-group">
        <label for="email">Your Email Address:</label>
        <input id="email" name="email" type="email" value="" class="pure-input-1-3" required placeholder="your.name@email.com"/>
        <span class="email-invalid" style="display:none"> Must be a valid email address</span>
      </fieldset>

      <button class="button-success pure-button button-xlarge"><i class="fa fa-paper-plane"></i>&nbsp;Send</button>
    </div>

    <div class="thankyou_message" style="display:none;">
      <h2> 연락을 주셔서 감사합니다. 귀하의 요청을 빠르게 처리하도록 하겠습니다.</h2>
      <!-- h2> Thanks for contacting us!  We will get back to you soon!</h2 -->
    </div>

  </form>

  <!-- Submit the Form to Google Using "AJAX" -->
  <script data-cfasync="false" type="text/javascript" src="/assets/js/form-submission-handler.js"></script>
<!-- END -->
