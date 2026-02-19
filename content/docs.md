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
  - "css/docs.css"
extra_scripts:
  - "js/jquery-3.7.1.min.js"
  - "js/bootstrap.min.js"
  - "js/panzoom.min.js"
  - "js/zoom.js"
  - "js/loading.js"
use_shared_header: true
use_shared_footer: true
active_nav: "docs"
header_class: "docs-page-header"
header_title: "Docs"
breadcrumb_html: |
  
                  <li class="breadcrumb-item">
                    <a href="index.html" class="breadcrumb-link text-white"
                      >Home</a
                    >
                  </li>
  
                  <li
                    class="breadcrumb-item active text-white"
                    aria-current="page"
                  >
                    Docs
                  </li>
---

<main class="main-section p-0 min-vh-100 d-flex flex-column">
      <section class="esc-section esc-roadmap-1-container-section">
        <div class="container">
          <div
            class="pages-title mb-4 d-flex flex-wrap align-items-center justify-content-between"
          >
            <h2 class="h2 fw-semibold">Eclipse S-Core Building Blocks</h2>

            <div class="roadmap-modules d-flex flex-wrap gap-3">
              <div class="roadmap-module d-flex align-items-center gap-2">
                <span class="color v-0-5"></span>
                <span class="module-name">S-CORE v0.5 module </span>
              </div>
              <div class="roadmap-module d-flex align-items-center gap-2">
                <span class="color v-1-0"></span>

                <span class="module-name">S-CORE v1.0 module </span>
              </div>
            </div>
          </div>
          
          <div class="roadmap-content">
            <div class="roadmap-container mt-4 d-flex flex-column gap-4">
                          <p class="main-desc">
              This section provides a schematic overview of the technical building blocks that form the foundation of our platform. 
              Here, you’ll find a clear differentiation between S-CORE modules available in version 0.5 and those planned for version 1.0. <br/>
            </p>
              <div class="zoom-image-wrapper">
                <div class="panzoom-container">
                  <img
                    src="images/docs/roadmap-1-3x.png"
                    alt=""
                    class="zoom-image"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="esc-section esc-roadmap-2-container-section">
        <div class="container">
          <div class="pages-title mb-4">
            <h2 class="h2 fw-semibold">S-Core Project Roadmap</h2>
          </div>
          <div class="roadmap-content">
            <div class="roadmap-container mt-4 d-flex flex-column gap-4">
              <p class="main-desc">
              Get athe development and release timeline of Eclipse S-CORE. It shows the key phases that shape the platform’s evolution—starting from early development to achieving maturity and stability. 
              Gain an understanding of how each phase contributes to delivering a scalable and reliable platform.
            </p>
              <div class="zoom-image-wrapper">
                <div class="panzoom-container">
                  <img
                    src="images/docs/roadmap-2-3x.png"
                    alt=""
                    class="zoom-image"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="esc-section esc-documentation-container-section">
        <div class="container">
          <div class="pages-title mb-4">
            <h2 class="h2 mb-3 fw-semibold">Build & Documentation Toolchain</h2>
            <p class="main-desc">
              The build system uses Bazel to automate workflows like repository
              cloning, software builds, documentation generation, testing, and
              more. Documentation is managed with Sphinx and sphinx-needs, while
              diagrams are created using PlantUML and draw.io. Supported
              languages include C++ and Rust, with testing handled by
              gtest/gmock.
            </p>
          </div>
          <div class="roadmap-content">
            <div class="roadmap-container mt-4 d-flex flex-column gap-4">
              <div class="zoom-image-wrapper">
                <div class="panzoom-container">
                  <img
                    src="images/docs/documentation-3x.png"
                    alt=""
                    class="zoom-image"
                  />
                </div>
              </div>
            </div><br>
            <a  href="https://eclipse-score.github.io/score/main/" class="read-more btn btn-primary main-primary" target="_blank"
                  >Check out our GitHub Project
                
            </a>
          </div>
        </div>
      </section>
</main>
