---
title: "Contact"
---
{{<rawhtml>}}

<section>
  <div class="container">
    <div class="row">
      <div class="col-lg-6">
        <div class="contact-form">
          <h2>Get in Touch</h2>
          <form class="row" id="fs-frm" method="POST" action="https://formspree.io/{{ .Site.Params.fabspreeURL }}">
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
      <div class="col mt-4 rounded">
        <img src="/images/katie-drink.jpg" class="img-fluid" alt="Katie Headshot">
      </div>
    </div>
  </div>
</section>

{{</rawhtml>}}