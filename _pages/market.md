---
layout: page
title: Market
permalink: /market/
#image: '/images/01.jpg'
---
![Workflow]({{site.baseurl}}/images/High_energy_neutrons_web.jpg)
*High-energy neutrons*

The product of our fusion reactor is energy in the form of 1- high-energy neutrons and 2- heat. High-energy neutrons are hard to come by and have applications in multiple industries. Heat can be converted into electrical energy. We target new customer segments, each larger in market size, as our technology evolves to facilitate higher reaction densities and yields greater magnitudes of output neutron flux and heat energy.

During Phase 1 and 2, our value proposition lies in the high energy neutron flux, which is coveted for its ability to transmute or change elements. Industries that rely on high-energy neutrons are currently served by fission reactors that are limited by the technical and socio-political constraints surrounding nuclear fission. Additionally, most fission reactors are purposed towards energy generation; the few that are focused on leveraging their neutron flux for transmutation are old and unreliable. New fission reactors are expensive to stand up to; arduous to permit; face strong societal opposition due to real and perceived safety concerns; generate radioactive waste; rely on enriched uranium and pose the threat of nuclear weapons proliferation. 

![Workflow]({{site.baseurl}}/images/Transmutation_elements_web.jpg)
*Transmutation of elements using high-energy neutrons*

The near-term commercial focus is to leverage the neutron flux output of the IMPF fusion reactor to provide a low-cost, safe, and reliable supply of neutron flux that the world currently relies on fission reactors for. Phase 1 will target medical isotope production and medical imaging. Phase 2 will enable the treatment of hazardous radioactive waste from nuclear fission and the production of rare earth metals through transmutation. Phase 3 will focus on energy generation for utility-scale baseload power as well as mobile fleet applications such as submarines, ships, and space shuttles.

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