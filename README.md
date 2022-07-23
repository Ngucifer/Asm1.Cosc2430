<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="Style.css" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
  </head>

  <body>
    <!-- header of the website -->
    <header>
      <nav>
        <!-- fa fa-bars -->
        <input type="checkbox" id="check" />
        <label for="check" class="checkbtn">
          <i class="fa fa-bars" style="font-size: 36px"></i>
        </label>

        <!-- Logo and button -->
        <label class="logo">Bookflix &#128214;</label>
        <ul>
          <li><a class="active" href="homePage.html">Home page</a></li>
          <li><a href="categoryPage.html">Category page</a></li>
          <li><a href="contactPage.html">Contact page</a></li>
        </ul>
      </nav>
    </header>
    <ul class="breadcrumb">
      <li>Home</li>
    </ul>
    <main>
      <!-- homepage -->
      <div class="homePage">
        <!-- western Book -->
        <div class="outSideGrid">
          <a href="categoryPage.html" style="color:#cd7700;"><h1>Western</h1></a>
          <h4>
            - A true cowboy knows love, pain, and shame but never cares about
            fame -
          </h4>

          <div class="contentGrid">
            <!-- book1 -->
            <div class="w">
              <div>
                <a href="bookDetailPage.html"
                  ><img
                    class="image"
                    src="/Asm1/img/lonesomeDove.jpg"
                    alt="The book called: Lonesome Dove"
                /></a>
              </div>
              <div>
                <a href="bookDetailPage.html"style="color:#cd7700;"><h2>Lonesome Dove</h2></a>
              </div>
            </div>

            <!-- book2 -->
            <div class="w">
              <div>
                <a href="bookDetailPage.html"><img
                  class="image"
                  src="/Asm1/img/bigSky.jpg"
                  alt="The book called: Big Sky"
                /></a>
              </div>
              <div>
                <a href="bookDetailPage.html"style="color:#cd7700;"><h2>Big Sky</h2></a>
              </div>
            </div>

            <!-- book3 -->
            <div class="w">
              <div>
                <a href="bookDetailPage.html"><img
                  class="image"
                  src="/Asm1/img/littleBigMan.jpg"
                  alt="The book called: Little Big Man"
                /></a>
              </div>
              <div>
                <a href="bookDetailPage.html"style="color:#cd7700;"><h2>Little Big Man</h2></a>
              </div>
            </div>
          </div>
        </div>

        <!-- Mystery Book -->
        <div class="outSideGrid">
          <a href="categoryPage.html" style="color:#cd7700;"><h1>Mystery</h1></a>
          <h4>
            - The world, even the smallest parts of it, is filled with things
            you don’t know -
          </h4>

          <div class="contentGrid">
            <!-- book1 -->
            <div class="w">
              <div>
                <a href="bookDetailPage.html"><img
                  class="image"
                  src="/Asm1/img/davinci.jpg"
                  alt="The book called: The Da Vinci Code"
                /></a>
              </div>
              <div>
                <a href="bookDetailPage.html"style="color:#cd7700;"><h2>Da Vinci Code</h2></a>
              </div>
            </div>

            <!-- book2 -->
            <div class="w">
              <div>
                <a href="bookDetailPage.html"><img
                  class="image"
                  src="/Asm1/img/theSilinceOfTheLambs.jpg"
                  alt="The book called: The Silence Of The Lambs"
                /></a>
              </div>
              <div>
                <a href="bookDetailPage.html" style="color:#cd7700;"><h2>The Silence Of The Lambs</h2></a>
              </div>
            </div>

            <!-- book3 -->
            <div class="w">
              <div>
                <a href="bookDetailPage.html"><img
                  class="image"
                  src="/Asm1/img/stillLife.jpg"
                  alt="The book called: Still Life"
                /></a>
              </div>
              <div>
                <a href="bookDetailPage.html" style="color:#cd7700;"><h2>Still Life</h2></a>
              </div>
            </div>
          </div>
        </div>

    <!-- Footer of the website -->
    <footer class="footer">
      <nav>
        <ul>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Privacy Policy</a></li>
          <li><a href="#">Terms</a></li>
          <li><a href="#">Copyright</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>
      </nav>
    </footer>
  </body>
</html>
