---
title: "Contact"
---
{{<rawhtml>}}

<section class="contact">
  <div class="container">
    <div class="row">
      <div class="col-lg-6">
        <div class="contact-form">
          <h2>Get in Touch</h2>
          <form class="row" id="contact-form" method="POST" action="https://fabform.io/f/{{ .Site.Params.fabformURL }}">
            <div class="col-md-6">
              <input type="text" class="form-control" id="name" name="name" placeholder="Your Name">
            </div>
            <div class="col-md-6">
              <input type="email" class="form-control" id="mail" name="email" required="" placeholder="Your Email">
            </div>
            <div class="col-md-12">
              <textarea class="form-control" id="message" rows="8" name="message"
                placeholder="Message here…"></textarea>
            </div>
            <div class="col-lg-12">
              <button type="submit" class="btn btn-primary" id="contact-form-button" formtarget="_blank">Send Message</button>
              <p id="contact-form-status"></p>
            </div>
          </form>
        </div>
      </div>
      <div class="col-md-4 box-shadow">
        <img src="/images/katie-drink.jpg" style="max-height: 400px; display: block;">
      </div>
    </div>
  </div>
</section>

{{</rawhtml>}}