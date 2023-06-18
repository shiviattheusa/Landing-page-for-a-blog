# Landing-page-for-a-blog
creating a landing page 

/*html code*/

<!DOCTYPE html>
<html>
<head>
  <title>Blog Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Blog Page</h1>
  </header>
  <main>
    <section id="blogs">
      <h2>Blogs</h2>
      <ul>
        <li><a href="#">Segment 1</a></li>
        <li><a href="#">Segment 2</a></li>
        <li><a href="#">Segment 3</a></li>
      </ul>
      <div class="sub-segments">
        <h3>Sub Segments</h3>
        <ul>
          <li><a href="#">Sub Segment 1</a></li>
          <li><a href="#">Sub Segment 2</a></li>
          <li><a href="#">Sub Segment 3</a></li>
          <li><a href="#">Sub Segment 4</a></li>
          <li><a href="#">Sub Segment 5</a></li>
          <li><a href="#">Sub Segment 6</a></li>
          <li><a href="#">Sub Segment 7</a></li>
        </ul>
      </div>
    </section>
    <section id="News-feed">
      <h2>News Feed</h2>
      <ul>
        <li>This is a news item.</li>
        <li>This is another news item.</li>
        <li>This is yet another news item.</li>
      </ul>
    </section>
    <section id="events">
      <h2>Upcoming Events</h2>
      <ul>
        <li>This is an event.</li>
        <li>This is another event.</li>
        <li>This is yet another event.</li>
      </ul>
    </section>
    <section id="jobs">
      <h2>Jobs</h2>
      <ul>
        <li>This is a job posting.</li>
        <li>This is another job posting.</li>
        <li>This is yet another job posting.</li>
      </ul>
    </section>
  </main>
  <footer>
    <p>Copyright &copy; 2023</p>
  </footer>
</body>
</html>



/*css code*/

body {
    font-family: 'Times New Roman', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
  }
  
  header {
    background-color: #383535;
    color: rgb(255, 121, 121);
    padding: 10px;
  }
  
  main {
    margin: 0;
    padding: 0;
  }
  
  section {
    margin-bottom: 10px;
  }
  
  h2 {
    font-size: 18px;
    margin-top: 0;
  }
  
  ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
  }
  
  li {
    margin-bottom: 5px;
  }
  
  a {
    text-decoration: none;
  }
  
  footer {
    background-color: #181616;
    color: rgb(255, 136, 136);
    padding: 10px;
    text-align: center;
  }
