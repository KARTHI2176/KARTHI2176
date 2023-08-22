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
      <p>Placeholder text goes here.</p>
    </section>
    <section class="section">
      <h2>Beef</h2>
      <p>Placeholder text goes here.</p>
    </section>
    <section class="section">
      <h2>Sushi</h2>
      <p>Placeholder text goes here.</p>
    </section>
  </main>
</body>
</html>

