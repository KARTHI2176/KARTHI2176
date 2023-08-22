<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* Reset some default styles */
    body, h1, h2, p {
      margin: 0;
      padding: 0;
    }

    /* Basic styling */
    body {
      font-family: Arial, sans-serif;
    }

    header {
      background-color: #333;
      color: white;
      padding: 1rem;
      text-align: center;
    }

    main {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      padding: 1rem;
    }

    .section {
      background-color: #f0f0f0;
      border: 1px solid black;
      box-sizing: border-box;
      margin-bottom: 1rem;
      padding: 1rem;
      position: relative;
    }

    .section h2 {
      font-size: 1.25em;
      position: absolute;
      top: 0;
      right: 0;
      background-color: #333;
      color: white;
      padding: 0.5rem;
    }

    /* Media queries for responsiveness */
    @media screen and (max-width: 992px) {
      .section {
        width: calc(33.33% - 1rem);
      }
    }

    @media screen and (max-width: 767px) {
      .section {
        width: 100%;
      }
    }
  </style>
  <title>Module 2 Assignment</title>
</head>
<body>
  <header>
    <h1>Module 2 Coding Assignment</h1>
  </header>
  <main>
    <section class="section">
      <h2>Chicken</h2>
      <p>Savor the juiciness of our Chicken dishes, each bite bursting with flavor. From classic roasted chicken to tangy grilled options, our menu caters to every palate. Delight in the perfect balance of tender meat and savory seasonings, ensuring a memorable dining experience that keeps you coming back for more..</p>
    </section>
    <section class="section">
      <h2>Beef</h2>
      <p>Indulge in the richness of our Beef offerings, where quality meets taste. Sink your teeth into tender cuts cooked to your preferred level of doneness. Whether it's a hearty steak or a gourmet burger, our carefully selected beef options promise an unforgettable culinary journey that will satisfy even the most discerning meat enthusiasts..</p>
    </section>
    <section class="section">
      <h2>Sushi</h2>
      <p>Embark on a gastronomic adventure with our exquisite Sushi creations. From traditional nigiri to inventive rolls, each piece showcases the artistry of our skilled chefs. Immerse yourself in the delicate textures and harmonious flavors, as fresh seafood and thoughtfully paired ingredients come together to create a symphony of taste. Elevate your dining experience with our captivating Sushi selections..</p>
    </section>
  </main>
</body>
</html>

