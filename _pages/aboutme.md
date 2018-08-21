---
title: "About Me"
layout: splash
permalink: /aboutme/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header2.jpeg
  caption: "[Photo by Felix Mittermeier from Pexels](https://www.pexels.com/photo/blue-and-purple-cosmic-sky-956999/)"
excerpt: "Hello, I'm Korean student who studies Economics at college who is interested in data science and machine learning."
intro1:
  - title: '2017'
feature_row1:
  - image_path: https://cdn-images-1.medium.com/max/1600/1*Esywynei7PjK0uR-luaZ-A.png
    alt: "python"
    title: "9~12: My first encounter to programming."
    excerpt: "First encountered programming in a university lecture. Learned the basics of Python and used it to solve many problems."
intro2:
  - title: '2018'
feature_row2:
  - image_path: http://blog.yozi.kr/2018/03/30/laravel-propel/laravel-propel-logo.jpg
    alt: "laravel"
    title: "1~2: Web Development"
    excerpt: "Developed dynamic web for sharing images and videos, with PHP and mySQL using the Laravel framework. Live Chat with pusher, automatic email sending function using Mailgun, and a bulletin board function for posting comments and replies are included."
feature_row3:
  - image_path: https://d2jq2hx2dbkw6t.cloudfront.net/337/f7-cordova-vue.png
    alt: "vuejs"
    title: "3: Working on developing mobile application"
    excerpt: "Used the Vue.js front end and the Laravel backend API to create an application for sharing posts made up of images and text. Applied the mobile-friendly Framework7 UI, but did not finish deploying it to mobile applications using PhoneGap."
feature_row4:
  - image_path: assets/images/machine-learning.png
    alt: "coursera machine learning"
    title: "4: Machine Learning"
    excerpt: "Attended 'Machine Learning' classes at Coursera taught by Andrew Ng, a professor at Stanford University and a leading professional in deep learning. It is an online version of the Stanford lecture, which has been well-known for its best description of machine learning."
    url: "https://www.coursera.org/account/accomplishments/specialization/certificate/9HD4TD9Y84HY"
    btn_label: "Learn More"
    btn_class: "btn--primary"
feature_row5:
  - image_path: http://datameetsmedia.com/wp-content/uploads/2018/04/Screen-Shot-2018-04-01-at-1.33.45-PM.png
    alt: "coursera deeplearning certificate"
    title: "5: Deep Learning"
    excerpt: "Attended 'Deep Learning' Specialization course taught by professor Andrew Ng. Learned basic Neural Networks, Convolutional Neural Networks, Sequence Models, and Hyperparameter tuning techniques."
    url: "https://www.coursera.org/account/accomplishments/specialization/certificate/9HD4TD9Y84HY"
    btn_label: "View Certificate"
    btn_class: "btn--primary"

---

{% include feature_row id="intro1" type="center" %}
{% include feature_row id="feature_row1" type="left" %}
{% include feature_row id="intro2" type="center" %}
{% include feature_row id="feature_row2" type="right" %}
{% include feature_row id="feature_row3" type="left" %}
{% include feature_row id="feature_row4" type="right" %}
{% include feature_row id="feature_row5" type="left" %}
