---
title: "About Me"
layout: splash
permalink: /aboutme/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header2.jpeg
  caption: "[Photo by Felix Mittermeier from Pexels](https://www.pexels.com/photo/blue-and-purple-cosmic-sky-956999/)"
excerpt: "Hello, I am a Korean student who studies Economics at college, and who is interested in data scince and machine learning. Welcome to my playground for data science."
intro1:
  - title: '2017년'
feature_row1:
  - image_path: https://cdn-images-1.medium.com/max/1600/1*Esywynei7PjK0uR-luaZ-A.png
    alt: "python"
    title: "9~12월: 처음 접하는 프로그래밍"
    excerpt: "대학교 교양 강의로 프로그래밍 처음 접함. Python의 기초를 배우고, 이를 이용해 여러 문제를 해결해봄."
intro2:
  - title: '2018년'
feature_row2:
  - image_path: http://blog.yozi.kr/2018/03/30/laravel-propel/laravel-propel-logo.jpg
    alt: "laravel"
    title: "1~2월: 웹 개발"
    excerpt: "Laravel 프레임워크를 이용해 PHP와 mySQL로 이미지, 동영상 공유를 위한 다이나믹 웹 개발. Pusher을 이용한 실시간 채팅, Mailgun을 이용한 이메일 자동 송신 기능, 게시물에 댓글과 답글을 달 수 있는 게시판 기능 등이 포함됨."
feature_row3:
  - image_path: https://d2jq2hx2dbkw6t.cloudfront.net/337/f7-cordova-vue.png
    alt: "vuejs"
    title: "3월: 모바일 어플리케이션 개발 시도"
    excerpt: 'Vue.js 프론트엔드와 Laravel 백엔드 API를 이용하여 이미지와 텍스트로 구성된 게시물을 공유할 수 있는 어플리케이션을 만듦. 모바일 친화적인 Framework7 UI를 적용했으나, PhoneGap을 이용하여 모바일 어플리케이션으로 배포하는 것까지 마무리하지는 않음.'
feature_row4:
  - image_path: assets/images/machine-learning.png
    alt: "coursera machine learning"
    title: "4월: Machine Learning"
    excerpt: "MOOC 플랫폼 중 하나인 Coursera에서 딥러닝의 세계적 석좌인, Andrew Ng 스탠포드 대학 교수의 'Machine Learning' 강좌 수강. 머신러닝에 관해서 가장 잘 설명한 것으로 정평이 난 스탠포드 강의의 온라인 버전임."
    url: "https://www.coursera.org/account/accomplishments/specialization/certificate/9HD4TD9Y84HY"
    btn_label: "더 알아보기"
    btn_class: "btn--primary"
feature_row5:
  - image_path: http://datameetsmedia.com/wp-content/uploads/2018/04/Screen-Shot-2018-04-01-at-1.33.45-PM.png
    alt: "coursera deeplearning certificate"
    title: "5월: Deep Learning"
    excerpt: "Andrew Ng 교수의 'Deep Learning' Specialization 코스 수강. 기본적인 Neural Networks, Convolutional Neural Networks, Sequence Models 등을 배우고, 나아가 Hyperparameter tuning 등 실전과 밀접히 연관된 테크닉을 배움."
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
