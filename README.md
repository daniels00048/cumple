# cumple
<!DOCTYPE html>
<html>
<head>
  <title>¡Feliz Cumpleaños!</title>
  <style>
    body {
      text-align: center;
      font-family: Arial, sans-serif;
      background-color: white; /* Fondo blanco */
      margin: 0;
      padding: 0;
    }
    h1 {
      color: #FF69B4;
      margin-top: 50px;
    }
    p {
      font-size: 20px;
      margin-bottom: 30px;
      color: #FF69B4; /* Color rosa */
    }
    button {
      margin: 10px;
      padding: 10px 20px;
      font-size: 16px;
      background-color: #FF69B4; /* Color rosa */
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    #image-container {
      display: none;
      margin-top: 30px;
    }
    #image-container img {
      max-width: 100%;
      height: auto;
    }
    #image-container p {
      margin-top: 10px;
      font-size: 18px;
      color: #FF69B4; /* Color rosa */
    }
  </style>
</head>
<body>
  <h1>¡Feliz Cumpleaños!</h1>
  <p>¿Querés saber cuál es tu regalo?</p>
  <button id="yes-button">Sí</button>
  <button id="of-course-button">Por supuesto</button>
  <div id="image-container">
    <img src="https://content.app-sources.com/s/91227843417793845/uploads/Bafle_Karaoke_Kids_/yPgZtZvyEBMFcnj3i9jQ-3656054.jpg" alt="Regalo">
    <p>TIAMO MUCHO</p>
  </div>

  <script>
    var yesButton = document.getElementById('yes-button');
    var ofCourseButton = document.getElementById('of-course-button');
    var imageContainer = document.getElementById('image-container');

    function showImage() {
      imageContainer.style.display = 'block';
    }

    yesButton.addEventListener('click', showImage);
    ofCourseButton.addEventListener('click', showImage);
    
  </script>
</body>
</html>
