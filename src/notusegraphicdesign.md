---
title: graphic design
layout: base.njk
tags: navItem
pageClass: graphicdesign
---

<main>
 <h1 class="design">Graphic Design</h1>
   <h2 class="tool">Tools: Photoshop, Illustrator</h2>   
     <selection class="portfolio">  
{%- for page in collections.design %}
 <article class="card">  
   <div class="card-img"> 
   <img src="{{page.data.postImg}}" alt="{{page.data.postImg}}" >
      </div>
      <div class="card__content">
         <h2 class="project-title"><a href="{{page.url}}">{{page.data.title}}</a></h2> 
     <button class="botton-explore"><span><a href="{{page.url}}">Explore</a></span></button>
  </div>

  </div>
   </div> 
    </article>
{%- endfor %}
  </selection>
    </main>