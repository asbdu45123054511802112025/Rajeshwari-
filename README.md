
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Restaurant Menu</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="menu-header">
    <h1>Restaurant Name</h1>
    <p>Delicious food for every taste!</p>
  </header>

  <main class="menu">
    <section class="menu-section">
      <h2>Appetizers</h2>
      <ul>
        <li>
          <span class="dish-name">Bruschetta</span>
          <span class="price">$6.99</span>
        </li>
        <li>
          <span class="dish-name">Stuffed Mushrooms</span>
          <span class="price">$7.99</span>
        </li>
      </ul>
    </section>

    <section class="menu-section">
      <h2>Main Courses</h2>
      <ul>
        <li>
          <span class="dish-name">Grilled Salmon</span>
          <span class="price">$14.99</span>
        </li>
        <li>
          <span class="dish-name">Spaghetti Carbonara</span>
          <span class="price">$12.99</span>
        </li>
      </ul>
    </section>

    <section class="menu-section">
      <h2>Desserts</h2>
      <ul>
        <li>
          <span class="dish-name">Tiramisu</span>
          <span class="price">$5.99</span>
        </li>
        <li>
          <span class="dish-name">Cheesecake</span>
          <span class="price">$6.49</span>
        </li>
      </ul>
    </section>

    <section class="menu-section">
      <h2>Beverages</h2>
      <ul>
        <li>
          <span class="dish-name">Fresh Lemonade</span>
          <span class="price">$2.99</span>
        </li>
        <li>
          <span class="dish-name">Coffee</span>
          <span class="price">$1.99</span>
        </li>
      </ul>
    </section>
  </main>
</body>
</html>

CSS (styles.css):

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f8f9fa;
}

.menu-header {
  background-color: #d35400;
  color: white;
  text-align: center;
  padding: 20px;
}

.menu-header h1 {
  margin: 0;
  font-size: 2.5rem;
}

.menu-header p {
  margin: 5px 0;
  font-size: 1.2rem;
}

.menu {
  max-width: 800px;
  margin: 20px auto;
  padding: 10px;
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.menu-section {
  margin-bottom: 20px;
}

.menu-section h2 {
  font-size: 1.8rem;
  color: #d35400;
  border-bottom: 2px solid #d35400;
  padding-bottom: 5px;
}

ul {
  list-style: none;
  padding: 0;
}

li {
  display: flex;
  justify-content: space-between;
  padding: 10px 0;
  border-bottom: 1px solid #ddd;
}

li:last-child {
  border-bottom: none;
}

.dish-name {
  font-weight: bold;
}

.price {
  color: #555;
}





