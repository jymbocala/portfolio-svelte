<script>
  function toggleHamburger() {
    const hamburger = document.querySelector(".hamburger");
    const navMenu = document.querySelector(".nav__menu");
    hamburger.classList.toggle("active");
    navMenu.classList.toggle("active");
  }
</script>

<header class="flex justify-center w-screen fixed top-0 py-6 bg-dark">
  <nav class="flex justify-between border-4 border-secondary w-screen py-4 ">
    <div class="text-light">title and pic
      <img src="" alt="jym bocala profile">
    </div>
    <div class="text-light">nav lists</div>
  </nav>
  <!-- <div className="nav">
    <div className="nav__logo-group">
      <img src="images/hero-profile3.png" width={60} alt="jym bocala profile" />
      <a href="#home">
        <p>{"<jymintech>"}</p>
      </a>
    </div>

    <ul className="nav__menu">
      <li className="menu__item">
        <a href="#home" className="menu__item-link" onClick={toggleHamburger}>
          Home
        </a>
      </li>
      <li className="menu__item">
        <a href="#about" className="menu__item-link" onClick={toggleHamburger}>
          About Me
        </a>
      </li>
      <li className="menu__item">
        <a
          href="#projects"
          className="menu__item-link"
          onClick={toggleHamburger}
        >
          Projects
        </a>
      </li>
      <li className="menu__item">
        <a
          href="#contact"
          className="menu__item-link"
          onClick={toggleHamburger}
        >
          Contact Me
        </a>
      </li>
      <li className="menu__item">
        <a
          href="./Jym-Bocala-CV.pdf"
          className="menu__item-link"
          download="Jym_Bocala_CV.pdf"
          target="_blank"
        >
          <button className="download-btn">
            <i className="ri-download-2-fill download-icon" />
            CV
          </button>
        </a>
      </li>
    </ul>

    <div className="hamburger" onClick={toggleHamburger}>
      <span className="bar" />
      <span className="bar" />
      <span className="bar" />
    </div>
  </div> -->
</header>

