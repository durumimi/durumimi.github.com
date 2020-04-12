---
layout: post
title: 에니어그램 걱정요정 이야기
feature-img: "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fk.kakaocdn.net%2Fdn%2FEZto8%2FbtqC3OXkDU8%2F9h56eIfM0cDrojdl1nHxT0%2Fimg.png"
thumbnail: "assets/img/thumbnails/desk-messy.jpeg"
image: "assets/img/thumbnails/desk-messy.jpg" #seo tag
tags: [Test, Lorem]
---

This is an example of a post which includes a feature image specified in the front matter of the post. 
The feature image spans the full-width of the page, and is shown with the title on permalink pages:

```yaml
feature-img: "assets/img/pexels/desk-messy.jpeg"
```

>  -  젤 멋져지면

**1) 나? 난 나를 믿어**

 

에니어그램 6번 유형을 관통하는

핵심키워드는 <의심>이다.

믿지 못하는 마음.

믿을수가 없다.

**그래서 늘 '불안'하고**

**그래서 늘 '확인'하고**

싶어한다.

 

 

그중에서도 **젤 못믿는 건**

**바로 '자기자신'이다.**

그래서 믿을만한 걸 찾으려고

이 산(?) 저 산(?)을 부지런히 돌아댕긴다.

{% highlight ruby %}
{% raw %}
{% include aligner.html images="pexels/book-glass.jpeg,triangle.png" %}
{% endraw %}
{% endhighlight %}

{% include aligner.html images="pexels/book-glass.jpeg,pexels/desk-messy.jpeg" %}


Here you have two images side by side, but you can set more and set the amount per columns 
(by specifying the number of columns or let it be automatic using `"auto"`):

{% highlight ruby %}
{% raw %}
{% include aligner.html images="portfolio/cabin.png,portfolio/cake.png,portfolio/circus.png" column=3 %}
{% endraw %}
{% endhighlight %}

{% include aligner.html images="portfolio/cabin.png,portfolio/cake.png,portfolio/circus.png" column=3 %}
