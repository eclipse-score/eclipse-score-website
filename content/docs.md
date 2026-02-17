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
---

<header class="main-pages-header docs-page-header w-100">
      <nav
        class="navbar navbar-expand-xl navbar-light bg-light frame w-100"
        style="min-height: 64px"
      >
        <div class="container px-3">
          <div class="navbar-content">
            <a
              class="navbar-brand d-flex align-items-center logo"
              href="index.html"
            >
              <div class="logo-icon me-0">
                <img class="logo-text" src="images/icons/logo.svg" alt="Logo" />
              </div>
              <span class="logo-title h1 mb-0 fw-semibold">Eclipse S-CORE</span>
            </a>
            <button
              class="navbar-toggler"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#navbarNavDropdown"
              aria-controls="navbarNavDropdown"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
              <ul class="navbar-nav me-auto mb-2 mb-lg-0 navigation-links">
                <li class="nav-item">
                  <a class="nav-link" href="index.html">Home</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" aria-current="page" href="news.html"
                    >News/Events</a
                  >
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="training-modules.html">Join us</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="about-us.html">About us</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="faq.html" >FAQ</a>
                </li>

                <li class="nav-link active">
                  <a class="nav-link" href="https://eclipse-score.github.io/score/main/" target="_blank">Docs</a>
                </li>
             
              </ul>
              <div
                class="search-form-container d-flex align-items-center gap-2"
              >
              
                <a
                  href="https://github.com/eclipse-score"
                  class="github-link ms-2"
                  aria-label="Visit our GitHub"
                >
                  <div class="github-icon" aria-hidden="true">
                    <img
                      src="images/icons/github.svg"
                      alt="GitHub Icon"
                      class="img-fluid"
                    />
                  </div>
                </a>
              </div>
            </div>
          </div>
        </div>
      </nav>
      <section
        class="pages-header-content w-100 flex-grow-1 d-flex align-items-end py-5"
      >
        <div class="container">
          <div class="pages-title">
            <h2 class="h2 text-white">Docs</h2>
          </div>
          <div class="bredcrumb-container">
            <nav aria-label="breadcrumb">
              <ol class="breadcrumb mb-0">
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
              </ol>
            </nav>
          </div>
        </div>
      </section>
    </header>

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

      <footer class="footer-section">
        <div class="container">
          <div class="row justify-content-start mb-3">
            
          <div class="row justify-content-start mb-3">
            <div class="col-12 text-start">
              <span class="footer-copyright fw-bold text-white"
                >Copyright © Eclipse Foundation AISBL. All Rights Reserved.</span
              >
            </div>
          </div>
          <div class="row justify-content-start">
            <div class="col-12 col-md-auto d-flex justify-content-start gap-3">
              <a
                href="https://www.eclipse.org/legal/termsofuse.php"
                class="footer-policy-link text-white text-decoration-none"
                >Terms of Use</a
              >
              <a
                href="https://www.eclipse.org/legal/privacy.php"
                class="footer-policy-link text-white text-decoration-none"
                >Privacy Policy</a
              >
              <a
                href="https://www.eclipse.org/legal/copyright.php"
                class="footer-policy-link text-white text-decoration-none"
                >Copyright Agent</a
              >
              <a
                href="https://www.eclipse.org/legal/epl-2.0/"
                class="footer-policy-link text-white text-decoration-none"
                >Eclipse Public License</a
              >
              <a
                href="https://www.eclipse.org/legal/"
                class="footer-policy-link text-white text-decoration-none"
                >Legal Resources</a
              >
            </div>
          </div>
        </div>
      </footer>
    </main>
    <div id="loading-screen">
      <img src="images/icons/logo.svg" alt="Logo" class="loading-logo" />
    </div>
