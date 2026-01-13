<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>WonderVerse.Ink - README</title>
</head>
<body>
  <h1>WonderVerse.Ink</h1>

  <p><strong>Artist:</strong> Adam Ellison</p>

  <hr />

  <h2>Project Overview</h2>
  <p>
    <strong>WonderVerse.Ink</strong> is a personal artist website designed to showcase Adam Ellison’s artwork in a
    visually engaging and easy-to-navigate format. The site serves as an online portfolio where visitors can explore
    original art, understand the artist’s creative vision, and get in touch for commissions or collaborations.
  </p>
  <p>
    The goal of the project is to create a clean, responsive, and visually appealing web presence that highlights
    artwork while remaining simple and intuitive to use.
  </p>

  <h2>Technologies Used</h2>
  <ul>
    <li><strong>HTML</strong> – Structure and content of the website</li>
    <li><strong>CSS</strong> – Styling, layout, and responsiveness</li>
    <li><strong>Bootstrap (optional)</strong> – Used for layout components and responsive design (if applicable)</li>
  </ul>

  <h2>Wireframes</h2>
  <ul>
    <li>
      <strong>Images</strong><br />
    </li>
    <li>
      <strong>Links</strong><br />
    </li>
    <li>
      <strong>Buttons</strong><br />
    </li>
    <li>
      <strong>Navigation</strong><br />
    </li>
    <li>
      <strong>Form</strong><br />
    </li>
  </ul>

  <h2>How to Use the Site</h2>
  <ul>
    <li>
      <strong>Home Page</strong><br />
      Introduces WonderVerse.Ink and sets the overall tone and aesthetic of the artist’s brand.
    </li>
    <li>
      <strong>Gallery</strong><br />
      Displays artwork in a clear, organized layout so visitors can easily browse pieces.
    </li>
    <li>
      <strong>Bio</strong><br />
      Provides background information about the artist and the inspiration behind the work.
    </li>
    <li>
      <strong>Contact Page / Contact Form</strong><br />
      Allows visitors, potential clients, or collaborators to reach out regarding commissions, questions, or creative
      opportunities.
    </li>
    <li>
      <strong>Navigation Bar</strong><br />
      Enables smooth navigation between all sections of the website.
    </li>
  </ul>

   <h2>User Stories</h2>
  <ul>
    <li>
      <strong>As a visitor,</strong> I want to view the artist’s work in a clean, visually engaging layout so that I can
      easily explore the artwork without distractions.
    </li>
    <li>
      <strong>As a potential client,</strong> I want to understand what WonderVerse.Ink offers so that I can decide if I
      want to request a commission or collaboration.
    </li>
    <li>
      <strong>As a user,</strong> I want clear navigation between pages so that I can move through the site smoothly and
      find information quickly.
    </li>
  </ul> 

  <p>
    The site is fully responsive and designed to work well on both desktop and mobile devices.
  </p>

<h2>Ideas for Future Improvements</h2>
<ol>
  <li>
    Expand the use of <strong>Bootstrap</strong> across the site to further improve responsiveness, layout consistency,
    and reusable components.
  </li>
  <li>
    Add <strong>timelapse videos</strong> to the gallery to showcase the creative process behind each artwork.
  </li>
  <li>
    Introduce more <strong>interactive UX elements</strong>, such as hover effects, animations, and improved visual
    feedback, to enhance user engagement.
  </li>
</ol>

</body>
</html>



        <div class="pic-ctn">
                <img src="../images/Gogeta-cropped.JPG" alt="Gogeta" class="pic">
                <img src="../images/Goku-Blue.png" alt="Goku SSGB" class="pic">
                <img src="../images/Goku-Black-cropped.JPG" alt="Goku Black" class="pic">
                <img src="../images/Goku-SSJ4.PNG" alt="Goku SSJ4" class="pic">
                <img src="../images/Vegeta.PNG" alt="Vegeta" class="pic">
                <img src="../images/Gohan.PNG" alt="Gohan" class="pic">        
        </div>



.pic-ctn{
    width: 100vw;
    height: 200px;
}


@keyframes display {
  0% {
    transform: translateX(200px);
    opacity: 0;
  }
  10% {
    transform: translateX(0);
    opacity: 1;
  }
  20% {
    transform: translateX(0);
    opacity: 1;
  }
  30% {
    transform: translateX(-200px);
    opacity: 0;
  }
  100% {
    transform: translateX(-200px);
    opacity: 0;
  }
}
        .pic-ctn {
  position: relative;
  display: flex;
  justify-content: center;
  width: 100%;
  height: auto;
  margin: 10vh auto 600px;
  padding-bottom: 350px;
}

.pic-ctn > img {
  position: absolute;
  top: 0;
  transform: translateX(-50%);
  opacity: 0;
  animation: display 22s infinite;
  display: flex;
  justify-content: center;
  height: 900px;
  width: 800px;
}