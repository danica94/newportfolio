---
title: portfolio
layout: base.njk
tags: navItem
pageClass: home
---

  <main>
 <h1 class="design">Xueying Liu Student Project</h1>
   <h2 class="tool">Tool: Photoshop, Illustrator</h2>   
     <selection class="portfolio">  
{%- for page in collections.work %}
 <article class="card">  
   <div class="card-img"> 
   <a href="{{page.url}}"><img src="{{page.data.postImg}}" alt="{{page.data.postImgAlt}}" ></a>
      </div>
      <div class="card__content">
         <h2 class="project-title"><a href="{{page.url}}">{{page.data.title}}</a></h2> 
        <button class="card__btn"><a href="{{page.url}}">Explore<span>&rarr;</span></a></button>
   </div> 
    </article>
{%- endfor %}
  </selection>
    </main>