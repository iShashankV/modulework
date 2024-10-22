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

  .horizontal-menu ul li {
    width: 160px;
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

  /* Main content styling */
  .content {
    padding: 20px;
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

<!-- Main content -->
<div class="content">
  # Productivity with AI Tools
  In today’s digital landscape, leveraging artificial intelligence is essential for enhancing productivity and streamlining research processes. This site serves as your comprehensive resource for learning and understanding various AI tools that can transform your work experience.
  
  # What You Will Learn
  This site is a collection of resources and tutorials focused on multiple AI tools and Prompt Creations. The listed resources focus on:
  
  - **Foundational Knowledge**: Begin your journey with a basic introduction to the AI tools, understanding their functionality and relevance for our work environment.
  
  - **Step-by-Step Tutorials**: Access detailed guides on how to effectively use these different AI applications, enabling our research work.
  
  - **Practical Examples**: Learn through illustrative case studies that demonstrate the time-saving benefits of AI tools.
  
  ## Learn More About AI Tools
  Embark on your AI journey today! [Explore the resources ](ai-tools.md) available on this site, and discover how you can integrate AI tools into your daily work to enhance your productivity and achieve greater success.
</div>
