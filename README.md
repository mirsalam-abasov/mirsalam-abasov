<style>
.product-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.product-card {
  width: 250px;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 8px 20px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.product-card:hover {
  transform: translateY(-5px) scale(1.02);
  box-shadow: 0 12px 30px rgba(0,0,0,0.2);
}

.product-image img {
  width: 100%;
  height: 180px;
  object-fit: cover;
}

.product-info {
  padding: 15px;
  background-color: #fff;
  font-family: sans-serif;
}

.product-info h3 {
  margin-top: 0;
  font-size: 1.1rem;
}

.price {
  color: #27ae60;
  font-weight: bold;
}
</style>

<div class="product-grid">

  <div class="product-card">
    <div class="product-image">
      <img src="https://via.placeholder.com/250x180?text=Product+1" alt="Product 1">
    </div>
    <div class="product-info">
      <h3>Product Name 1</h3>
      <p>This is a short description of Product 1. It’s amazing.</p>
      <p class="price">$25.99</p>
    </div>
  </div>

  <div class="product-card">
    <div class="product-image">
      <img src="https://via.placeholder.com/250x180?text=Product+2" alt="Product 2">
    </div>
    <div class="product-info">
      <h3>Product Name 2</h3>
      <p>This product is even better than the first one.</p>
      <p class="price">$39.99</p>
    </div>
  </div>

  <!-- Add more product cards by copying the structure above -->

</div>
