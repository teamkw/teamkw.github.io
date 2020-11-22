---
title: "AMAZING book for PangPang"
layout: splash
permalink: /unibook_p/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/ub.jpg
  actions:
    - label: "Read"
      url: "https://teamkw.github.io/unibook"
#   caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "프로그래밍이 막막했나요? 걱정마세요. **unibook**이 있어요"

intro: 
  - excerpt: '"남들다 하는 코딩 저도 하고 싶은데 막막하네요" <br> "어떻게하지,,, 이건뭐지,,, ?" <br> <br> **UniBook** '

feature_row:
  - image_path: assets/images/web-main.png
    alt: "main page example"
    title: "일정"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."

  - image_path: /assets/images/web-lecture.png
    # image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "lecture files page example"
    title: "강의자료실"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: /assets/images/web-notice.png
    title: "공지사항"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."


feature_row2:
  - image_path: /assets/images/web-left.png
    alt: "placeholder image 2"
    title: "왼쪽 정렬~~"
    excerpt: '왼쪽 정렬한 이미지 / 소개 글 입니다'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/web-right.png
    alt: "오른쪽 정렬~~~"
    title: "Placeholder Image Right Aligned"
    excerpt: '오른쪽 정렬한 이미지 / 소개 글 입니다'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/web-center.jpg
    alt: "가운데 정렬~~"
    title: "Placeholder Image Center Aligned"
    excerpt: '가운데 정렬한 이미지 / 소개 글 입니다'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}