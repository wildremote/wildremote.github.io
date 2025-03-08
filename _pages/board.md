---
layout: page
title: Board
permalink: /board/
#image: '/images/01.jpg'
---
<div class="gallery-box">
  <div class="gallery">
    <img src="/images/aaron.jpg">
    <img src="/images/ali.jpg">
    <img src="/images/tim.jpg">
  </div>
  <em>Gallery / Board</em>
</div>

Lemma's board of directors and advisors.

### Aaron Mendonca - Board Member
![Workflow]({{site.baseurl}}/images/aaron.jpg)
*Aaron Mendonca*

Aaron loves leveraging confluences of specialized knowledge workers and skilled craftsmen to creatively and pragmatically reckon with complex infrastructural challenges. He holds a Bachelor’s in Architecture and Civil Engineering from IIT Kharagpur, and a Master’s in Energy & Environments from the Harvard Graduate School of Design, where he was a Lodha Fellow.

Aaron enjoys working across multiple scales of design and business ranging from the molecular to the territorial. He has worked at boutique firms such as the surviving associates of Geoffery Bawa and Corinthian Consortium, as well as high-growth startups such as WeWork, where he was the Head of Business Development for the Global Construction Innovation group. Aaron currently co-leads Innovation and Corporate Development for Burns & McDonnell, a 125-year-old family of companies focused on delivering infrastructure that makes cities and communities thrive.    

### Ali Elnaamani - Board Member
![Workflow]({{site.baseurl}}/images/ali.jpg)
*Ali Elnaamani*

Ali is an entrepreneur with executive leadership experience responsible for multiple intra-company profitable startups in Technology, Cybersecurity, Digitalization, and autonomous operations. Ali has more than 14 years of experience in the energy market specifically in controls and digitalization as he spent the first half of his career commissioning all types of generation facilities in the US and around the world before moving into consulting leadership roles. Ali holds a bachelor’s degree in computer information systems, a master’s degree in business administration and information security management and a master’s degree in cybersecurity.

### Tim Dumatrait - Board Member
![Workflow]({{site.baseurl}}/images/tim.jpg)
*Tim Dumatrait*

Tim is a passionate craftsperson and systems thinker, with 15 years of experience driving creative design solutions and novel use of technology within product, real estate, design, and construction organizations.
 
Since 2007, he has worked in Lafayette for emerymcclure architecture and in New Orleans for Eskew+Dumez+Ripple, taking on all roles ranging from programming and design to construction management. In 2013, he relocated to New York City to work with CASE Inc, focusing on building data and construction technology. In 2015, he joined WeWork to develop their global coworking facilities network. He is currently in New York City with Burns & McDonnell.

***
#### Contact
<div class="form-box">
  <div class="contact-head">
    {% if site.data.settings.contact.description %}
      <p class="page-description">{{site.data.settings.contact.description}}</p>
    {% endif %}
  </div>
  <form class="form" action="{% if site.data.settings.contact.email %}https://formspree.io/f/mrgvqelz{% else %}#{% endif %}" method="POST">
    <div class="form__group">
      <label class="form__label screen-reader-text" for="form-name">Your Name</label>
      <input class="form__input" id="form-name" type="text" name="name" placeholder="Name" required>
    </div>
    <div class="form__group">
      <label class="form__label screen-reader-text" for="form-email">Your Email</label>
      <input class="form__input" id="form-email" type="email" name="_replyto" placeholder="Email" required>
    </div>
    <div class="form__group">
      <label class="form__label screen-reader-text" for="form-text">Your Message</label>
      <textarea class="form__input" id="form-text" name="text" rows="10" placeholder="Message" required></textarea>
    </div>
    <div class="form__group">
      <button class="button" type="submit">Send Message</button>
    </div>
  </form>
</div>
***