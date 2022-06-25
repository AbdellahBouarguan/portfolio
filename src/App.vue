<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
      <a class="navbar-brand" href="https://github.com/AbdellahBouarguan"
        ><img src="./assets/t.jpg"
      /></a>

      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link" href="/">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdown"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              My projects
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li>
                <a
                  class="dropdown-item"
                  href="https://github.com/AbdellahBouarguan/godot-flappy-bird"
                  >flappy bird</a
                >
              </li>
              <li>
                <a
                  class="dropdown-item"
                  href="https://github.com/AbdellahBouarguan/next-js-puppeteer"
                  >web scraping</a
                >
              </li>
              <li><hr class="dropdown-divider" /></li>
              <li>
                <a
                  class="dropdown-item"
                  href="https://github.com/AbdellahBouarguan?tab=repositories"
                  >more</a
                >
              </li>
            </ul>
          </li>
          <li class="nav-item d-flex">
            <a class="nav-link disabled">3D World</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2 row-cols-xl-3 g-3">
      <div class="col">
        <div class="card" style="width: 20rem">
          <img src="./assets/fpi.png" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title">Flappy Bird</h5>
            <p class="card-text">
              Flappy bird clone made with godot engine using GDScript
            </p>
            <div class="dropdown">
              <button
                class="btn btn-primary dropdown-toggle"
                type="button"
                id="dropdownMenuButton1"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Download
              </button>
              <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                <li>
                  <a
                    class="dropdown-item"
                    href="https://github.com/AbdellahBouarguan/godot-flappy-bird/releases/download/v1.0.1/flappyBird.apk"
                    download="FlappyBird"
                    ><img src="./assets/android_black_24dp.svg" /> Android</a
                  >
                </li>
                <li>
                  <a
                    class="dropdown-item"
                    href="https://github.com/AbdellahBouarguan/godot-flappy-bird/releases/download/v1.0.1/flappyBird.x86_64"
                    download="FlappyBird"
                    ><img
                      src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAABmJLR0QA/wD/AP+gvaeTAAAB4klEQVRIia3VTYhOYRQH8N8M5iNfi6FIE4MFUUqDkigrFj4WVig7SsKKpkyZLCnJykqJhUQyOztEvRsfCx/NFkVG0UyZxYzX4jmT973ue9/75j311L3P+f/P/5znPPdcWrPFLeJL2zF8RRVTeIgV7Qo+iJkIXruetEvgupT1zwg8W0kVG5uRO0sIrMVZHMRL6Wg+hG9HOwSWYRIbUMEQXoRvUzPy3BIC3TiHRfiN5fgUvs0l+E3tHV6FUAeO+tuDGaz8n+BdGI9gVzGCL+pv05WiAM16cAF9IfJLOtJB3KnBnIm9lq1fup5VnM/4+tRX8hbzWhW4FuRxLMjxn1J/VCdaCd6F70EcboDpxUSNwGf0lBXYG6RpLC3A3VVfxYEsoFGTZ5v2Gt8KBCqZ911ZwJwGxE7pC+7AzQKBiUjicXB6cK8ADxbisjSDHmBbE/wwbgS+vwjYhS14Lp3nG2mwjeG4VE3W1mA/HmEdthYJXPTvzB/B4Xg+mcO5hUs4hPt41iARsDtHYArrg7wnhzOawxmV5hbqb9GqnADdUpOPSA0VGe6UepWdplXpC5/Oq2AfPuZkVMUS6Y/2I9Zk7NVixrA9L3DWBnAaTyOTSs3+6lgD0hV/L43s21FRyza/BKa3yPkHNEGCVG6R20EAAAAASUVORK5CYII="
                    />Linux</a
                  >
                </li>
                <li>
                  <a
                    class="dropdown-item"
                    href="https://github.com/AbdellahBouarguan/godot-flappy-bird/releases/download/v1.0.1/flappyBird.exe"
                    download="FlappyBird"
                    ><svg
                      xmlns="http://www.w3.org/2000/svg"
                      x="0px"
                      y="0px"
                      width="25"
                      height="25"
                      viewBox="0 0 50 50"
                      style="fill: #000000"
                    >
                      <path
                        d="M19.852 7.761l-15 2.25C4.362 10.085 4 10.505 4 11v12c0 .553.448 1 1 1h15c.552 0 1-.447 1-1V8.75c0-.291-.127-.567-.348-.758C20.432 7.803 20.139 7.721 19.852 7.761zM45.652 4.242c-.22-.189-.512-.271-.801-.231l-21 3.15C23.362 7.235 23 7.655 23 8.15V23c0 .553.448 1 1 1h21c.552 0 1-.447 1-1V5C46 4.709 45.873 4.433 45.652 4.242zM20 26H5c-.552 0-1 .447-1 1v12c0 .495.362.915.852.989l15 2.25c.05.007.099.011.148.011.238 0 .47-.085.652-.242C20.873 41.817 21 41.541 21 41.25V27C21 26.447 20.552 26 20 26zM45 26H24c-.552 0-1 .447-1 1v14.85c0 .495.362.915.852.989l21 3.15C44.901 45.996 44.951 46 45 46c.238 0 .47-.085.652-.242C45.873 45.567 46 45.291 46 45V27C46 26.447 45.552 26 45 26z"
                      ></path></svg
                    >Windows</a
                  >
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card" style="width: 20rem">
          <img src="./assets/fpi.png" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card" style="width: 20rem">
          <img src="./assets/fpi.png" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: "App",
  components: {
    // HelloWorld
  },
};
</script>

<style>
.navbar-brand img {
  border-radius: 50%;
  width: 50px;
  height: 50px;
}
.nav-item .btn {
  margin-left: 7px;
}
.t {
  position: relative;
  bottom: 2px;
}
</style>
