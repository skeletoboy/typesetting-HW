# CSS FILE CONTENT
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&family=Source+Code+Pro:ital,wght@0,200..900;1,200..900&display=swap');
* {
    box-sizing: border-box;
  }
  
  body {
    margin: 0 auto;
    min-width: 1000px;
    max-width: 1400px;
  }
  
  /* Layout */
  
  section {
    float: left;
    width: 50%;
  }
  
  aside {
    float: left;
    width: 30%;
  }
  
  nav {
    float: left;
    width: 20%;
  }
  
  footer {
    clear: both;
  }
  
  header, section, aside, nav, footer {
    padding: 20px;
  }
  
  /* header and footer */
  
  header, footer {
    border-top: 5px solid #a66;
    border-bottom: 5px solid #a66;
  }
  
  /* WRITE YOUR styling/typesetting CSS code BELOW HERE */

  body {
    font-family: "Roboto", sans-serif;
    font-size: 14px;
    line-height: 22px;
    letter-spacing: normal;
    word-spacing: normal;
    justify-content: flex-start;
    align-items: flex-start;

  }

  header {
    font-family: "Roboto", sans-serif;
    font-weight: bold;
    display: flex;
    align-items: center;
    justify-content: center;
    letter-spacing: 2px;
    font-size: large;
    
  }
  h2 {
    font-size: 25px;
  }

  /* indent first p after each h2 */
  h2 + p {
    text-indent: 1.25rem;
  }
  /* section {
    text-indent: 1.25rem;
  } */


  a{
    color: #a66;
  }
  a:visited {
    color: blue;
  }
  a:focus {
    text-decoration: none;
    outline: none;
  }
  a:hover {
    text-decoration: none;
  }
  a:active {
    color: red;
  }
  section p a::after {
    content: "";
    width: 11px;
    height: 11px;
    margin-left: 4px;
    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' fill='currentColor' viewBox='0 0 16 16'%3E%3Cpath fill-rule='evenodd' d='M8.636 3.5a.5.5 0 0 0-.5-.5H1.5A1.5 1.5 0 0 0 0 4.5v10A1.5 1.5 0 0 0 1.5 16h10a1.5 1.5 0 0 0 1.5-1.5V7.864a.5.5 0 0 0-1 0V14.5a.5.5 0 0 1-.5.5h-10a.5.5 0 0 1-.5-.5v-10a.5.5 0 0 1 .5-.5h6.636a.5.5 0 0 0 .5-.5z'/%3E%3Cpath fill-rule='evenodd' d='M16 .5a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0 0 1h3.793L6.146 9.146a.5.5 0 1 0 .708.708L15 1.707V5.5a.5.5 0 0 0 1 0v-5z'/%3E%3C/svg%3E");
    background-position: center;
    background-repeat: no-repeat;
    background-size: contain;
    display: inline-block;
  }
  section p {
    line-height: 22px;
    padding-left: 1.25rem;
  }

  ul {
    list-style-type: square;
  }
  ol {
    list-style-type: lower-alpha;
  }

  nav ul {
    list-style-type: none;
  }
  nav ul li {
    margin-bottom: 10px;
  }
  nav ul li a {
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    font-size: 20px;
    display: block;
    text-decoration: none;
    padding: 20px 30px;
    border: 1px solid #a66;
  }



  
