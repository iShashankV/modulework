<!-- Inline CSS -->
<style>
  /* Horizontal Menu Bar */
  .horizontal-menu {
    display: flex;
    justify-content: center;
    background-color: #333;
    list-style-type: none;
    padding: 0;
    margin: 0;
  }

  .horizontal-menu li {
    padding: 14px 20px;
    position: relative;
  }

  .horizontal-menu li a {
    color: white;
    text-decoration: none;
    display: block;
  }

  .horizontal-menu li:hover {
    background-color: #575757;
  }

  .horizontal-menu ul {
    display: none;
    position: absolute;
    top: 100%;
    left: 0;
    background-color: #333;
    list-style-type: none;
    padding: 0;
  }

  .horizontal-menu li:hover ul {
    display: block;
  }

  .horizontal-menu ul li {
    width: 160px;
  }

  /* Sidebar Menu */
  .sidebar-menu {
    width: 200px;
    background-color: #333;
    list-style-type: none;
    padding: 10px;
    position: fixed;
    top: 0;
    left: 0;
    height: 100%;
  }

  .sidebar-menu li {
    margin: 10px 0;
  }

  .sidebar-menu li a {
    color: white;
    text-decoration: none;
    display: block;
    padding: 10px;
  }

  .sidebar-menu li:hover {
    background-color: #575757;
  }

  .sidebar-menu ul {
    padding-left: 20px;
  }

  /* Main content styling */
  .content {
    margin-left: 220px; /* Adjust margin to make space for sidebar */
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

<!-- Sidebar Menu -->
<aside>
  <ul class="sidebar-menu">
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
</aside>

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
