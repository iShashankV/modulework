<!-- Inline CSS -->
<style>
  /* Horizontal Menu Bar */
  .horizontal-menu {
    display: flex;
    justify-content: center;
    background-color: rgba(51, 51, 51, 0.9); /* Slightly transparent background */
    list-style-type: none;
    padding: 0;
    margin: 0;
  }

  .horizontal-menu li {
    padding: 14px 20px;
    position: relative;
    transition: background-color 0.3s ease; /* Smooth transition for hover */
  }

  .horizontal-menu li a {
    color: white;
    text-decoration: none;
    display: block;
  }

  .horizontal-menu li:hover {
    background-color: rgba(87, 87, 87, 0.9); /* Slightly transparent hover effect */
  }

  /* Dropdown Menu */
  .horizontal-menu ul {
    display: none;
    position: absolute;
    top: 100%;
    left: 0;
    background-color: rgba(51, 51, 51, 0.9);
    list-style-type: none;
    padding: 0;
    opacity: 0;
    transition: opacity 0.3s ease, top 0.3s ease; /* Add transition for dropdown */
  }

  .horizontal-menu li:hover ul {
    display: block;
    opacity: 1; /* Dropdown becomes visible */
    top: 120%; /* Slide down effect */
  }

  /* Fix for submenu to stay open */
  .horizontal-menu ul li {
    width: 160px;
  }

  .horizontal-menu ul li a {
    padding: 10px;
    display: block;
    white-space: nowrap;
  }

  /* Ensuring submenu doesn't disappear while hovering */
  .horizontal-menu li:hover ul:hover {
    display: block; /* Keep the submenu open */
    opacity: 1;
  }

  /* Mobile responsiveness */
  @media (max-width: 768px) {
    .horizontal-menu {
      flex-direction: column;
      align-items: center;
    }

    .horizontal-menu ul {
      position: static;
    }

    .horizontal-menu ul li {
      width: 100%;
    }
  }
</style>

<!-- HTML Content -->
<nav>
  <!-- Horizontal Menu -->
  <ul class="horizontal-menu">
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About Us</a></li>
    <li><a href="#contact">Contact Us</a></li>
    <li><a href="#resources">Resources</a>
      <ul>
        <li><a href="#ai-tools">AI Tools</a></li>
        <li><a href="#tutorials">Tutorials</a></li>
      </ul>
    </li>
  </ul>
</nav>
