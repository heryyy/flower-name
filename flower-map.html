<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Platypi:ital,wght@0,300..800;1,300..800&display=swap"
      rel="stylesheet"
    />
    <title>Flower Map</title>
    <style>
      body {
        background-image: url("images/background.jpg");
        background-position: center;
        background-size: cover;
        background-repeat: repeat;
      }
      button {
        display: block;
        padding: 10px;
        margin: 0 auto;
        margin-bottom: 16px;
        font-size: 16px;
      }
      .flower-grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(80px, 1fr));
        row-gap: 110px;
        max-width: 1000px;
        margin: auto;
      }
      .flower-item {
        width: 100%;
        height: auto;
      }
      .placeholder {
        width: 100%; /* Match the width of the flowers for consistency */
        height: 0; /* Or adjust as needed to match your layout */
        visibility: hidden; /* Hide the placeholder but keep it in the flow */
      }
      .flower-container {
        position: relative;
        width: 100%;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
      }

      .flower-item {
        width: 100%; /* Adjust size as necessary */
        height: auto;
        position: absolute;
        top: 0;
        left: 0;
      }

      .flower-label {
        position: absolute;
        /* bottom: 150%; */
        left: 50%;
        color: white;
        font-size: 36px;
        font-family: "Platypi", serif;
        z-index: 10;
        text-shadow: 0px 0px 4px rgba(0, 0, 0, 0.8);
      }
    </style>
  </head>
  <body>
    <button onclick="backToHome()"><bold>! TRY IT OUT !</bold></button>
    <div class="flower-grid" id="flowerGrid">
      <!-- Images will be inserted dynamically here -->
    </div>

    <script>
      document.addEventListener("DOMContentLoaded", function () {
        const flowerGrid = document.getElementById("flowerGrid");
        for (let i = 0; i < 26; i++) {
          const char = String.fromCharCode(97 + i); // ASCII to char (97 is 'a')

          if (i === 24) {
            addBlankDivs(flowerGrid, 1); // Function to add blank divs as placeholders
          }

          // Create a container for each flower and its label
          const flowerContainer = document.createElement("div");
          flowerContainer.classList.add("flower-container");

          // Create the image element for the flower
          const img = document.createElement("img");
          img.src = `images/style2/${char}.png`;
          img.classList.add("flower-item");
          img.alt = `Flower ${char.toUpperCase()}`;

          const randomRotation = Math.floor(Math.random() * 13) - 7;
          img.style.transform = `translateX(-10%) rotate(${randomRotation}deg)`;

          // Create a label for the flower
          const label = document.createElement("span");
          label.textContent = char.toUpperCase(); // Display the letter
          label.classList.add("flower-label");
          label.style.transform = `translate(10%, 150%) rotate(${-randomRotation}deg)`;

          // Append the image and label to the container
          flowerContainer.appendChild(img);
          flowerContainer.appendChild(label);

          // Append the container to the grid
          flowerGrid.appendChild(flowerContainer);
        }
      });

      function addBlankDivs(grid, count) {
        // Add two blank divs as placeholders to adjust alignment
        for (let j = 0; j < count; j++) {
          const placeholder = document.createElement("div");
          placeholder.classList.add("placeholder");
          grid.appendChild(placeholder);
        }
      }

      function backToHome() {
        window.history.back();
      }
    </script>
  </body>
</html>
