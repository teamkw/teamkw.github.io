---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/index/main.jpg
  actions:
    - label: "<i class='fab fa-github'></i>  GitHub"
      url: "https://github.com/teamkw"

    
excerpt: >
  광운대학교 학생들로 이루어진 teamKW 소개 웹페이지입니다.<br />
#   <small><a href="https://github.com/mmistakes/minimal-mistakes/releases/tag/4.21.0">Latest release v4.21.0</a></small>


intro: 
  - excerpt: 'teamKW는 광운대학교 학생들로 이루어져있습니다. <br> 저희는 광운대생들을 위한 프로그램들을 개발합니다. <br> 🐴✨ <br> ------------ '

feature_row:
  - image_path: assets/images/index/web-extension.png
    alt: "web-extension"
    title: "Pangbot-Web-Extension"
    excerpt: "광운대생들을 위한 **KLAS 크롬 확장 프로그램**"
    url: "https://teamkw.github.io/web-extension/"
    btn_label: "Read More"
    btn_class: "btn--primary"


  - image_path: assets/images/index/unibook.png
    alt: "unibook"
    title: "unibook"
    excerpt: "광운대생의 험난한 코딩 여정을 함께할 **unibook** "
    url: "https://teamkw.github.io/unibook_p/"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: /assets/images/index/pangbot.png
    title: "PangBot"
    excerpt: "고요한 카톡창을 울려줄 **PangBot**"
    url: "https://teamkw.github.io/pangbot/"
    btn_label: "Read More"
    btn_class: "btn--primary"

---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row" type="center" %}