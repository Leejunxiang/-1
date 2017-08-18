---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>ZZ的个人小站</h1>
         <font color="#FFFAF0">建立于2017.8.17 </font>
         <font color="#FFFAF0">军机处处长的日常修养</font>
       </div>
      <div id="particles-js"></div>
    </div>
          
    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
