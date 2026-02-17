---
title: "Eclipse S-CORE"
render_raw: true
extra_styles:
  - "css/bootstrap.min.css"
  - "css/loading.css"
  - "css/navbar.css"
  - "css/globals.css"
  - "css/footer.css"
  - "css/styleguide.css"
  - "css/news.css"
extra_scripts:
  - "js/jquery-3.7.1.min.js"
  - "js/bootstrap.min.js"
  - "js/loading.js"
use_shared_header: true
use_shared_footer: true
active_nav: "news"
header_class: "news-page-header"
header_title: "News & Events"
breadcrumb_html: |
  
                  <li class="breadcrumb-item">
                    <a href="index.html" class="breadcrumb-link text-white"
                      >Home</a
                    >
                  </li>
                  <li class="breadcrumb-item">
                    <a href="news.html" class="breadcrumb-link text-white"
                      >News &amp; Events</a
                    >
                  </li>
                  <li
                    class="breadcrumb-item active text-white"
                    aria-current="page"
                  >
                    Townhalls
                  </li>
---

<main class="main-section p-0 min-vh-100 d-flex flex-column">
      <section class="esc-pages-section nav-tabs-section">
        <div class="container">
          <div class="nav-tabs-wrapper">
            <ul class="nav nav-tabs">
              <li class="nav-item">
                <a class="nav-link" href="news.html">Conferences</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="press_releases.html">Press Releases</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="articles.html">Articles & Events</a>
              </li>
              <li class="nav-item">
                <a class="nav-link active" href="townhalls.html">Townhalls</a>
              </li>
            </ul>
          </div>
        </div>
      </section>

      <section
        class="esc-section esc-news-container-section pt-0 min-vh-100 mt-4"
      >
        <div class="container">
          <div class="row w-100 g-4">
            <div class="col-12 col-xl-8 gap-3 mt-0">
              <div class="d-flex flex-column gap-3">
                <div class="main-blog-item-card d-flex flex-column gap-3">
                  <div
                    class="blog-img d-flex align-items-center justify-content-center"
                  >
                    <img src="images/news/blog-img.jpg" alt="" />
                  </div>
                  <div class="blog-item-content">
                    <div
                      class="top-pick-date d-flex align-items-center gap-2 mb-2"
                    >
                      <span class="icon d-flex align-items-center">
                        <img src="images/icons/calendar.svg" alt="" />
                      </span>
                      <span class="date">Apr 11, 2025</span>
                    </div>
                    <h2 class="h2 mb-3">
                      Eclipse S-CORE Townhall
                    </h2>
                    <p>
                      Background information to S-CORE and Q&A session. 
                    </p>
                    <a
                      class="read-more btn btn-primary main-primary mt-4 d-inline-block text-center"
                      href="https://www.eclipse.org/lists/sdv-wg/msg00674.html" target="_blank" rel="noopener noreferrer"
                    >
                      Read More
                    </a>
                  </div>
                </div>
              
              </div>
              <div class="text-center mt-3">
                <a
                  class="show-more btn btn-primary main-outline-primary mt-4 d-inline-block text-center"
                  href="#"
                >
                  Show More
                </a>
              </div>
            </div>
            <div class="col-12 col-xl-4 mt-xl-0 mt-5">
              <div class="main-search-top-picks-card d-flex flex-column gap-4">
                
              </div>
            </div>
          </div>
        </div>
      </section>
</main>
