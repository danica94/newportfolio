---
title: home
layout: base.njk
tags: navItem
pageClass: home
---
<main>
        <div class="hero" id="home">
                 <div class="hero-content">
                            <div class="hero-text">
                                <p>I'm</p>
                                <h1>Xueying(Danica) Liu</h1>
                                <h2>Multimedia student; Tour Guide</h2>
                            </div>
                </div>
            </div>
        </div>
        <div class="experience" id="experience">
            <div class="container">
            <h1>My Experience</h1>
                <div class="timeline">
                    <div class="timeline-item left">
                        <div class="timeline-text">
                            <div class="timeline-date">2019-Now</div>
                            <h2>Mutimedia Student</h2>
                            <h4>Borough of Manhattan Community College, New York</h4>
                            <p>
                               Design Skill：Photoshop,  Illustrator, Figma<br>
          Video Skill: Premiere Pro<br>
          Web Design Skill: HTML, CSS
                            </p>
                        </div>
                    </div>
                    <div class="timeline-item right">
                        <div class="timeline-text">
                            <div class="timeline-date">2015 - 2019</div>
                            <h2>Tour Guide</h2>
                            <h4>Jiangsu,Nanjing,China; Xinjiang,China</h4>
                            <p>
                               Energetic professional with 3 years of experience informing and guiding East China(including five provinces of China) visitors. <br>Superior talent for customizing itineraries based on customer interest and delivering a high level of customer service. <br>Extensive knowledge of history and visual arts; able to deliver facts and historical information about attractions, antiques, and artifacts, pointing out features of interest and answering questions.
                            </p>
                        </div>
                    </div>
                       <!-- Experience End
                    <div class="timeline-item left ">
                        <div class="timeline-text">
                            <div class="timeline-date">2011 - 2015</div>
                            <h2>Tourism Management Student</h2>
                            <h4>Liaoning Institute of Science，China</h4>
                            <p>
                                Lorem ipsum dolor sit amet elit. Aliquam odio dolor, id luctus erat sagittis non. Ut blandit semper pretium.
                            </p>
                        </div>
                    </div>
End -->
                </div>
            </div>
        </div>
<!-- Experience End -->
<section class="page-contain">
{%- for page in collections.home %}
  <a href="{{page.url}}" class="data-card">
    <img src="{{page.data.postImg}}" alt="{{page.data.postImg}}">
    <h4>{{page.data.title}}</h4>
    <p>{{page.data.text}}</p>
    <span class="link-text">
      View More
      <svg width="25" height="16" viewBox="0 0 25 16" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M17.8631 0.929124L24.2271 7.29308C24.6176 7.68361 24.6176 8.31677 24.2271 8.7073L17.8631 15.0713C17.4726 15.4618 16.8394 15.4618 16.4489 15.0713C16.0584 14.6807 16.0584 14.0476 16.4489 13.657L21.1058 9.00019H0.47998V7.00019H21.1058L16.4489 2.34334C16.0584 1.95281 16.0584 1.31965 16.4489 0.929124C16.8394 0.538599 17.4726 0.538599 17.8631 0.929124Z" fill="#753BBD"/>
</svg>
    </span>
  </a>
{%- endfor %}

</section>
</main>






  <!-- Back to top button -->
     
<button onclick="topFunction()" id="myBtn" title="Go to top"><i class="fa fa-chevron-up"></i></button>   
</main>
        
