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
                    Articles
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
                <a class="nav-link active" href="articles.html">Articles & News</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="townhalls.html">Townhalls</a>
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
                <!-- ========== START: S-CORE 0.6.0 Release Card (English Version) ========== -->
<div class="main-blog-item-card d-flex flex-column gap-3">
  
  <div class="blog-item-content">
    <div class="top-pick-date d-flex align-items-center gap-2 mb-2">
      <span class="icon d-flex align-items-center">
        <img src="images/icons/calendar.svg" alt="Calendar Icon" />
      </span>
      <!-- Adjust the date to the actual release date -->
      <span class="date">Feb 23, 2026</span>
    </div>
    <h2 class="h2 mb-3">
      Eclipse S-CORE v0.6.0 Milestone Released!
    </h2>
    
    <!-- IMPORTANT: The markdown="1" attribute ensures the content is rendered correctly -->
    <div class="card-text mb-4" markdown="1">

<p>We're excited to announce the third milestone release of Eclipse S-CORE (v0.6.0), the open-source automotive middleware platform developed within the Eclipse SDV Working Group!</p>

<h4 class="mt-4 mb-2">What's New in v0.6.0:</h4>

<ul>
  <li>
    <strong>Dual-Language Platform:</strong> S-CORE now offers equal support for C++ and Rust, with 5 modules featuring Rust APIs and integration of the Ferrocene safety-critical Rust toolchain.
  </li>
  <li>
    <strong>Platform Expansion:</strong> Two major new modules added:
    <ul>
      <li><strong>Baselibs Rust:</strong> Foundation utilities for Rust development.</li>
      <li><strong>Lifecycle &amp; Health Management:</strong> Launch Manager and Health Monitoring for robust process supervision.</li>
    </ul>
  </li>
  <li>
    <strong>Enhanced Capabilities:</strong> Rust backends for Persistency, Communication, and Logging, an interactive example menu, and full CI/CD automation with a unified Bazel module.
  </li>
  <li>
    <strong>Matured Infrastructure:</strong> A comprehensive S-CORE Handbook, enhanced ISO 26262/21434 &amp; ASPICE 4.0 process compliance, and updates for QNX, Red Hat AutoSD, and more.
  </li>
</ul>

<h4 class="mt-4 mb-2">Get Involved:</h4>

<ul>
    <li>Explore the release: <a href="https://eclipse-score.github.io/reference_integration/v0.6.0/_collections/score_platform/docs/score_releases/index.html" target="_blank">Release Notes</a></li>
    <li>Read the S-CORE Handbook: <a href="https://eclipse-score.github.io/reference_integration/v0.6.0/_collections/score_platform/docs/handbook/index.html" target="_blank">S-CORE Handbook</a></li>
    <li>Join the conversation: <a href="https://github.com/orgs/eclipse-score/discussions">Discussions on GitHub</a></li>
    <li>Contribute: <a href="https://github.com/eclipse-score" target="_blank">GitHub Repo</a></li>
</ul>

<p class="mt-3">A huge thank you to our contributors and the Eclipse SDV community for making this milestone possible!</p>

    </div>

    <a class="read-more btn btn-primary main-primary mt-4 d-inline-block text-center" href="https://eclipse-score.github.io/reference_integration/v0.6.0/index.html" target="_blank">
      Full release notes
    </a>
  </div>
</div>
<!-- ========== END: S-CORE 0.6.0 Release Card (English Version) ========== -->

                <div class="main-blog-item-card d-flex flex-column gap-3">
                  <div
                    class="blog-img d-flex align-items-center justify-content-center"
                  >
                    <img src="images/news/s-core_05_release_teaser.png" alt="" />
                  </div>
                  <div class="blog-item-content">
                    <div
                      class="top-pick-date d-flex align-items-center gap-2 mb-2"
                    >
                      <span class="icon d-flex align-items-center">
                        <img src="images/icons/calendar.svg" alt="" />
                      </span>
                      <span class="date">Nov 6th, 2025</span>
                    </div>
                    <h2 class="h2 mb-3">
                      Eclipse S-CORE 0.5 – What’s inside the first public release.
                    </h2>
                    <p>
                      Source: Eclipse SDV WG Linkedin <br/><br/>
                    </p>
                    <p>
                        The first version of Eclipse S-CORE (Safe Open Vehicle Core) lays the groundwork for open, safety-ready automotive software.<br/>
                        
                    </p>
                    <a
                      class="read-more btn btn-primary main-primary mt-4 d-inline-block text-center"
                      href="https://www.linkedin.com/posts/software-defined-vehicle_s-core-05-release-activity-7392145693861363712-JWqw" target="_blank"
                    >
                      Read More and Discuss
                    </a>
                  </div>
                </div>
                <div class="main-blog-item-card d-flex flex-column gap-3">
                  <div
                    class="blog-img d-flex align-items-center justify-content-center"
                  >
                    <img src="images/news/EF_Newsletter_2025_09.PNG" alt="" />
                  </div>
                  <div class="blog-item-content">
                    <div
                      class="top-pick-date d-flex align-items-center gap-2 mb-2"
                    >
                      <span class="icon d-flex align-items-center">
                        <img src="images/icons/calendar.svg" alt="" />
                      </span>
                      <span class="date">Sept 30, 2025</span>
                    </div>
                    <h2 class="h2 mb-3">
                      Eclipse S-CORE: A new approach to building automotive software together
                    </h2>
                    <p>
                      by Valerie Hasler and Memsud Godinjak 
                    </p>
                    <a
                      class="read-more btn btn-primary main-primary mt-4 d-inline-block text-center"
                      href="https://newsroom.eclipse.org/eclipse-newsletter/2025/september/eclipse-s-core-new-approach-building-automotive-software-together"
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
