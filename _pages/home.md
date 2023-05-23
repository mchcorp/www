---
layout: splash
permalink: /

sections:
  - format: image
    #style: #optional style for your image section
    alt: Your Image alt tag # required - alt tag for your image.
    size: 8 # optional - column size (centered) e.g a size of 8 will add your image to a col-sm-8 div with an offset of 2 to ensure it's centered.
    path: /assets/images/h_main_wasa.jpg #requried - the full path to your image.
    url: /wasa
    
carousels:
  - images: 
    - image: /assets/images/h_main_wasa.jpg
    - url: /wasa

intro: 
  - excerpt: 'MCH conducts security evaluations for applications on behalf of organizations. We provide this service both directly and indirectly, as well as a subcontractor for prominent cybersecurity advisory firms and government agencies.'

sections:
  - format: text
    style: text-center # Optional css class to applied to section
    text_content:
      text: Our security testing team has more than 35 years of combined development and application security experience.  Our staff has access to a broad variety of testing and analysis testing tools to perform static (SAST) and dynamic (DAST) security testing, Software Composition Analysis (SCA), Manual Application Penetration Testing, Threat Modeling and Secure Code Reviews.

feature_row:
  - image_path: /assets/images/mm-cyber-feature.jpg
    alt: "Cyber Security Centric"
    title: "Cyber Security Centric"
    excerpt: "Every solution MCH implements incorporates cyber security safeguards, protections, and best practices."
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/mm-prime-feature.jpg
    alt: "Experienced Prime"
    title: "Experienced Prime"
    excerpt: "MCH has been competitively awarded numerous federal contracts it performed with exceptional results & CPARS."
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/mm-integrity-feature.jpg
    alt: "Credibility & Integrity"
    title: "Credibility & Integrity"
    excerpt: "MCH demonstrates responsiblity, integrity, and good character in its contract management activities."
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Learn more"      
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

![US Small Business Week Award Winner](/assets/images/sba_nsbw_award_winner.png){: width="150" }
