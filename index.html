<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes, viewport-fit=cover">
  <title>Amazon Style • Customer Login System</title>
  <!-- Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Roboto, system-ui, -apple-system, sans-serif;
    }
    body {
      background: #eaeded;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }
    /* Header - Amazon style */
    .header {
      background: #131921;
      color: white;
      padding: 10px 15px;
      display: flex;
      align-items: center;
      gap: 12px;
      flex-wrap: wrap;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    .logo {
      font-size: 1.8rem;
      font-weight: 700;
      letter-spacing: -1px;
      color: #febd69;
      display: flex;
      align-items: center;
      cursor: pointer;
    }
    .logo i {
      margin-right: 4px;
      color: #febd69;
    }
    .search-bar {
      flex: 1;
      display: flex;
      min-width: 200px;
    }
    .search-bar input {
      flex: 1;
      padding: 10px 12px;
      border: none;
      border-radius: 4px 0 0 4px;
      font-size: 1rem;
      outline: none;
    }
    .search-bar button {
      background: #febd69;
      border: none;
      padding: 0 16px;
      border-radius: 0 4px 4px 0;
      cursor: pointer;
      font-size: 1.1rem;
      color: #131921;
    }
    .header-actions {
      display: flex;
      align-items: center;
      gap: 20px;
    }
    .user-menu, .cart-icon, .settings-icon {
      font-size: 1.2rem;
      cursor: pointer;
      position: relative;
      transition: transform 0.2s;
      display: flex;
      align-items: center;
      gap: 5px;
    }
    .user-menu:hover, .cart-icon:hover, .settings-icon:hover {
      transform: scale(1.05);
    }
    .user-menu span {
      font-size: 0.85rem;
      max-width: 100px;
      overflow: hidden;
      text-overflow: ellipsis;
      white-space: nowrap;
    }
    .cart-count {
      position: absolute;
      top: -8px;
      right: -12px;
      background: #febd69;
      color: #131921;
      border-radius: 50%;
      width: 22px;
      height: 22px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 0.8rem;
      font-weight: bold;
    }
    /* Main layout */
    .main-container {
      display: flex;
      flex: 1;
      padding: 15px;
      gap: 15px;
    }
    /* Product grid */
    .products-section {
      flex: 3;
      background: white;
      border-radius: 8px;
      padding: 20px;
      box-shadow: 0 1px 4px rgba(0,0,0,0.1);
    }
    .section-title {
      font-size: 1.5rem;
      font-weight: 600;
      margin-bottom: 20px;
      color: #0f1111;
      border-bottom: 2px solid #febd69;
      padding-bottom: 8px;
      display: inline-block;
    }
    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
      gap: 20px;
    }
    .product-card {
      background: white;
      border-radius: 8px;
      padding: 15px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.08);
      transition: transform 0.2s;
      display: flex;
      flex-direction: column;
      border: 1px solid #eee;
    }
    .product-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 6px 15px rgba(0,0,0,0.12);
    }
    .product-img {
      width: 100%;
      height: 140px;
      object-fit: contain;
      background: #f8f8f8;
      border-radius: 6px;
      margin-bottom: 12px;
    }
    .product-title {
      font-weight: 600;
      font-size: 0.95rem;
      margin-bottom: 6px;
      color: #0f1111;
      white-space: nowrap;
      overflow: hidden;
      text-overflow: ellipsis;
    }
    .product-price {
      color: #b12704;
      font-weight: 700;
      font-size: 1.2rem;
      margin: 6px 0;
    }
    .add-to-cart-btn {
      background: #ffd814;
      border: none;
      border-radius: 20px;
      padding: 8px 0;
      font-weight: 600;
      cursor: pointer;
      margin-top: auto;
      transition: background 0.2s;
      font-size: 0.9rem;
      width: 100%;
      border: 1px solid #fcd200;
    }
    .add-to-cart-btn:hover {
      background: #f7ca00;
    }
    /* Cart sidebar */
    .cart-panel {
      flex: 1.2;
      background: white;
      border-radius: 8px;
      padding: 20px;
      box-shadow: 0 1px 4px rgba(0,0,0,0.1);
      max-height: 80vh;
      overflow-y: auto;
      position: sticky;
      top: 80px;
      display: flex;
      flex-direction: column;
    }
    .cart-item {
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #eee;
      padding: 12px 0;
      gap: 8px;
    }
    .cart-item-info {
      flex: 1;
      font-size: 0.9rem;
    }
    .remove-item {
      color: #c40000;
      cursor: pointer;
      font-size: 1.2rem;
      transition: transform 0.2s;
    }
    .remove-item:hover {
      transform: scale(1.2);
    }
    .total-row {
      font-weight: 700;
      font-size: 1.2rem;
      margin: 15px 0;
      display: flex;
      justify-content: space-between;
    }
    .checkout-btn {
      background: #ffa41c;
      border: none;
      padding: 12px;
      border-radius: 25px;
      font-weight: bold;
      cursor: pointer;
      margin-top: 10px;
      transition: background 0.2s;
    }
    .checkout-btn:hover {
      background: #ff8f00;
    }
    
    /* Modals */
    .modal {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.6);
      z-index: 300;
      display: none;
      align-items: center;
      justify-content: center;
    }
    .modal.show {
      display: flex;
    }
    .modal-box {
      background: white;
      border-radius: 12px;
      padding: 30px;
      width: 400px;
      max-width: 90vw;
      box-shadow: 0 10px 30px rgba(0,0,0,0.3);
      max-height: 80vh;
      overflow-y: auto;
    }
    .modal-box h3 {
      margin-bottom: 20px;
      color: #131921;
      font-size: 1.4rem;
      text-align: center;
    }
    .modal-box .form-group {
      margin-bottom: 15px;
    }
    .modal-box .form-group label {
      font-weight: 600;
      display: block;
      margin-bottom: 5px;
    }
    .modal-box .form-group input {
      width: 100%;
      padding: 10px;
      border: 2px solid #ddd;
      border-radius: 8px;
      font-size: 1rem;
      outline: none;
    }
    .modal-box .form-group input:focus {
      border-color: #febd69;
    }
    .modal-buttons {
      display: flex;
      gap: 10px;
      margin-top: 20px;
    }
    .modal-buttons button {
      flex: 1;
      padding: 10px;
      border: none;
      border-radius: 20px;
      font-weight: 600;
      cursor: pointer;
      font-size: 0.95rem;
    }
    .btn-primary {
      background: #131921;
      color: white;
    }
    .btn-secondary {
      background: #ddd;
      color: #333;
    }
    .error-msg {
      color: #c40000;
      font-size: 0.85rem;
      margin-top: 5px;
      display: none;
    }
    .error-msg.show {
      display: block;
    }
    .link-text {
      color: #0066c0;
      cursor: pointer;
      text-align: center;
      margin-top: 15px;
    }
    .link-text:hover {
      text-decoration: underline;
    }

    /* Admin panel */
    .admin-panel {
      position: fixed;
      top: 0;
      right: 0;
      width: 380px;
      max-width: 95vw;
      height: 100vh;
      background: white;
      box-shadow: -4px 0 20px rgba(0,0,0,0.25);
      z-index: 200;
      transform: translateX(100%);
      transition: transform 0.3s ease;
      display: flex;
      flex-direction: column;
      padding: 20px;
      overflow-y: auto;
    }
    .admin-panel.open {
      transform: translateX(0);
    }
    .admin-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 25px;
    }
    .close-admin {
      font-size: 1.8rem;
      cursor: pointer;
    }
    .admin-section {
      margin-top: 25px;
      border-top: 2px solid #ddd;
      padding-top: 20px;
    }
    .admin-btn {
      background: #131921;
      color: white;
      border: none;
      padding: 10px 18px;
      border-radius: 20px;
      font-weight: 600;
      cursor: pointer;
      width: 100%;
      margin-top: 5px;
    }
    .order-list {
      list-style: none;
      margin-top: 15px;
    }
    .order-list li {
      background: #f4f4f4;
      padding: 12px;
      border-radius: 8px;
      margin-bottom: 10px;
      font-size: 0.9rem;
    }
    .customer-info {
      background: #e8f4f8;
      padding: 5px 8px;
      border-radius: 4px;
      margin: 5px 0;
      font-size: 0.85rem;
    }
    .overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.4);
      z-index: 150;
      display: none;
    }
    .overlay.show {
      display: block;
    }
    
    /* User dropdown */
    .user-dropdown {
      position: absolute;
      top: 100%;
      right: 0;
      background: white;
      border-radius: 8px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
      min-width: 200px;
      z-index: 250;
      display: none;
      padding: 10px 0;
      margin-top: 5px;
    }
    .user-dropdown.show {
      display: block;
    }
    .user-dropdown-item {
      padding: 10px 20px;
      cursor: pointer;
      color: #131921;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .user-dropdown-item:hover {
      background: #f0f0f0;
    }
    
    @media (max-width: 750px) {
      .main-container {
        flex-direction: column;
      }
      .cart-panel {
        position: static;
        max-height: none;
      }
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header class="header">
    <div class="logo" onclick="location.reload()">
      <i class="fab fa-amazon"></i> amazon<span style="color:white;">.in</span>
    </div>
    <div class="search-bar">
      <input type="text" placeholder="Search products..." id="searchInput">
      <button id="searchBtn"><i class="fas fa-search"></i></button>
    </div>
    <div class="header-actions">
      <div class="user-menu" id="userMenuBtn">
        <i class="fas fa-user-circle"></i>
        <span id="userDisplayName">Login</span>
        <div class="user-dropdown" id="userDropdown">
          <div class="user-dropdown-item" id="profileBtn"><i class="fas fa-id-card"></i> My Profile</div>
          <div class="user-dropdown-item" id="myOrdersBtn"><i class="fas fa-box"></i> My Orders</div>
          <div class="user-dropdown-item" id="logoutBtn"><i class="fas fa-sign-out-alt"></i> Logout</div>
        </div>
      </div>
      <div class="settings-icon" id="settingsBtn" title="Admin Panel">
        <i class="fas fa-cog"></i>
      </div>
      <div class="cart-icon" id="cartToggle">
        <i class="fas fa-shopping-cart"></i>
        <span class="cart-count" id="cartCounter">0</span>
      </div>
    </div>
  </header>

  <!-- Main content -->
  <div class="main-container">
    <section class="products-section">
      <h2 class="section-title">Today's Deals</h2>
      <div class="product-grid" id="productContainer"></div>
    </section>
    <aside class="cart-panel" id="cartPanel">
      <h3 style="font-weight:700; margin-bottom:15px;"><i class="fas fa-shopping-basket"></i> Shopping Cart</h3>
      <div id="cartItemsContainer"><p style="color:#555;">Your cart is empty.</p></div>
      <div class="total-row" id="cartTotalDisplay">Total: ₹0</div>
      <button class="checkout-btn" id="placeOrderBtn"><i class="fas fa-lock"></i> Place Order</button>
    </aside>
  </div>

  <!-- Login/Register Modal -->
  <div class="modal" id="authModal">
    <div class="modal-box">
      <h3 id="authModalTitle">Login to Your Account</h3>
      <div class="form-group">
        <label>Email</label>
        <input type="email" id="authEmail" placeholder="Enter email">
      </div>
      <div class="form-group" id="authNameGroup" style="display:none;">
        <label>Full Name</label>
        <input type="text" id="authName" placeholder="Enter your name">
      </div>
      <div class="form-group" id="authAddressGroup" style="display:none;">
        <label>Delivery Address</label>
        <input type="text" id="authAddress" placeholder="Enter your address">
      </div>
      <div class="form-group">
        <label>Password</label>
        <input type="password" id="authPassword" placeholder="Enter password">
      </div>
      <div class="error-msg" id="authError">Invalid credentials!</div>
      <div class="modal-buttons">
        <button class="btn-secondary" id="cancelAuthBtn">Cancel</button>
        <button class="btn-primary" id="submitAuthBtn">Login</button>
      </div>
      <p class="link-text" id="toggleAuthMode">Don't have an account? Register</p>
    </div>
  </div>

  <!-- My Orders Modal -->
  <div class="modal" id="ordersModal">
    <div class="modal-box">
      <h3><i class="fas fa-box"></i> My Orders</h3>
      <div id="customerOrdersList"><p>No orders found.</p></div>
      <button class="btn-secondary" id="closeOrdersBtn" style="width:100%; margin-top:15px;">Close</button>
    </div>
  </div>

  <!-- Profile Modal -->
  <div class="modal" id="profileModal">
    <div class="modal-box">
      <h3><i class="fas fa-id-card"></i> My Profile</h3>
      <div id="profileInfo"></div>
      <button class="btn-secondary" id="closeProfileBtn" style="width:100%; margin-top:15px;">Close</button>
    </div>
  </div>

  <!-- Password Modal for Admin -->
  <div class="modal" id="passwordModal">
    <div class="modal-box">
      <h3>🔐 Admin Access</h3>
      <div class="form-group">
        <label>Password</label>
        <input type="password" id="passwordInput" placeholder="Enter admin password">
      </div>
      <div class="error-msg" id="passwordError">Incorrect password!</div>
      <div class="modal-buttons">
        <button class="btn-secondary" id="cancelPasswordBtn">Cancel</button>
        <button class="btn-primary" id="submitPasswordBtn">Unlock</button>
      </div>
    </div>
  </div>

  <!-- Overlay & Admin Panel -->
  <div class="overlay" id="overlay"></div>
  <div class="admin-panel" id="adminPanel">
    <div class="admin-header">
      <h2><i class="fas fa-user-shield"></i> Admin Panel</h2>
      <span class="close-admin" id="closeAdminBtn">&times;</span>
    </div>
    <p style="color:#555; margin-bottom:10px;">Manage products & view orders</p>
    
    <div>
      <h3 style="margin-bottom:15px;">➕ Add New Product</h3>
      <div class="form-group">
        <label>Product Title</label>
        <input type="text" id="adminTitle" placeholder="e.g., Wireless Earbuds">
      </div>
      <div class="form-group">
        <label>Price (₹)</label>
        <input type="number" id="adminPrice" placeholder="499" step="1">
      </div>
      <div class="form-group">
        <label>Image URL</label>
        <input type="text" id="adminImage" placeholder="https://example.com/image.jpg">
      </div>
      <button class="admin-btn" id="addProductBtn"><i class="fas fa-plus-circle"></i> Add Product</button>
    </div>

    <div class="admin-section">
      <h3 style="margin-bottom:10px;"><i class="fas fa-clipboard-list"></i> Customer Orders</h3>
      <ul class="order-list" id="adminOrderList"><li>No orders yet.</li></ul>
      <button class="admin-btn" style="background:#c40000; margin-top:10px;" id="clearOrdersBtn">Clear All Orders</button>
    </div>
    <p style="margin-top:20px; font-size:0.8rem; color:#666;">Data stored locally in browser.</p>
  </div>

  <script>
    (function() {
      // ---------- DATA STORAGE ----------
      let products = [];
      let cart = [];
      let orders = [];
      let users = []; // { id, email, name, address, password }
      let currentUser = null; // logged in user object
      
      const ADMIN_PASSWORD = "joyrupsaha";

      const defaultProducts = [
        { id: 'p1', title: 'boAt Rockerz 450 Bluetooth Headphone', price: 1499, image: 'https://m.media-amazon.com/images/I/51xxA+6E+xL._SX522_.jpg' },
        { id: 'p2', title: 'OnePlus Nord Buds 2 TWS', price: 2999, image: 'https://m.media-amazon.com/images/I/61o2Vn8+KUL._SX679_.jpg' },
        { id: 'p3', title: 'Amazon Echo Dot (5th Gen)', price: 3499, image: 'https://m.media-amazon.com/images/I/714Rq4k05UL._SX679_.jpg' },
        { id: 'p4', title: 'Samsung Galaxy Watch 4', price: 9999, image: 'https://m.media-amazon.com/images/I/71LfjLq8R9L._SX679_.jpg' },
        { id: 'p5', title: 'Kindle Paperwhite (11th Gen)', price: 13999, image: 'https://m.media-amazon.com/images/I/61K3Evh+M5L._SX679_.jpg' },
        { id: 'p6', title: 'Fire TV Stick 4K Max', price: 4999, image: 'https://m.media-amazon.com/images/I/51wK2G9nzjL._SX679_.jpg' }
      ];

      function loadData() {
        const storedProducts = localStorage.getItem('amazon_products');
        products = storedProducts ? JSON.parse(storedProducts) : [...defaultProducts];
        
        const storedCart = localStorage.getItem('amazon_cart');
        cart = storedCart ? JSON.parse(storedCart) : [];
        
        const storedOrders = localStorage.getItem('amazon_orders');
        orders = storedOrders ? JSON.parse(storedOrders) : [];
        
        const storedUsers = localStorage.getItem('amazon_users');
        users = storedUsers ? JSON.parse(storedUsers) : [];
        
        const storedCurrentUser = localStorage.getItem('amazon_currentUser');
        currentUser = storedCurrentUser ? JSON.parse(storedCurrentUser) : null;
      }

      function saveAll() {
        localStorage.setItem('amazon_products', JSON.stringify(products));
        localStorage.setItem('amazon_cart', JSON.stringify(cart));
        localStorage.setItem('amazon_orders', JSON.stringify(orders));
        localStorage.setItem('amazon_users', JSON.stringify(users));
        localStorage.setItem('amazon_currentUser', JSON.stringify(currentUser));
      }

      // ---------- RENDER ----------
      function renderProducts(filter = '') {
        const container = document.getElementById('productContainer');
        const filtered = products.filter(p => p.title.toLowerCase().includes(filter.toLowerCase()));
        container.innerHTML = filtered.length ? filtered.map(p => `
          <div class="product-card">
            <img src="${p.image}" class="product-img" onerror="this.src='https://via.placeholder.com/150'">
            <div class="product-title" title="${p.title}">${p.title}</div>
            <div class="product-price">₹${p.price}</div>
            <button class="add-to-cart-btn" data-id="${p.id}">Add to Cart</button>
          </div>`).join('') : '<p style="grid-column:1/-1;text-align:center;">No products found.</p>';
      }

      function renderCart() {
        const container = document.getElementById('cartItemsContainer');
        if (!cart.length) {
          container.innerHTML = '<p style="color:#555;">Your cart is empty.</p>';
        } else {
          container.innerHTML = cart.map(item => `
            <div class="cart-item">
              <div class="cart-item-info"><strong>${item.title}</strong><br>₹${item.price} x ${item.quantity}</div>
              <div style="display:flex;align-items:center;gap:8px;">
                <span>₹${item.price * item.quantity}</span>
                <i class="fas fa-trash-alt remove-item" data-id="${item.id}"></i>
              </div>
            </div>`).join('');
        }
        document.getElementById('cartCounter').textContent = cart.reduce((s,i) => s + i.quantity, 0);
        document.getElementById('cartTotalDisplay').innerHTML = `Total: <span style="color:#b12704;">₹${cart.reduce((s,i) => s + i.price*i.quantity, 0)}</span>`;
      }

      function updateUserUI() {
        const display = document.getElementById('userDisplayName');
        const dropdown = document.getElementById('userDropdown');
        if (currentUser) {
          display.textContent = currentUser.name.split(' ')[0];
          document.getElementById('logoutBtn').style.display = 'flex';
        } else {
          display.textContent = 'Login';
          document.getElementById('logoutBtn').style.display = 'none';
        }
      }

      function renderAdminOrders() {
        const list = document.getElementById('adminOrderList');
        if (!orders.length) {
          list.innerHTML = '<li>No orders yet.</li>';
          return;
        }
        list.innerHTML = orders.slice().reverse().map(o => `
          <li>
            <strong>Order #${o.id}</strong> <small>(${o.date})</small>
            <div class="customer-info">
              👤 ${o.customerName} • 📧 ${o.customerEmail}<br>
              📍 ${o.customerAddress || 'Address not provided'}
            </div>
            Items: ${o.items.map(i => i.title).join(', ')}<br>
            <span style="color:#b12704;font-weight:bold;">Total: ₹${o.total}</span>
          </li>`).join('');
      }

      // ---------- AUTH ----------
      let authMode = 'login'; // 'login' or 'register'

      function showAuthModal(mode = 'login') {
        authMode = mode;
        document.getElementById('authModalTitle').textContent = mode === 'login' ? 'Login to Your Account' : 'Create New Account';
        document.getElementById('authNameGroup').style.display = mode === 'register' ? 'block' : 'none';
        document.getElementById('authAddressGroup').style.display = mode === 'register' ? 'block' : 'none';
        document.getElementById('submitAuthBtn').textContent = mode === 'login' ? 'Login' : 'Register';
        document.getElementById('toggleAuthMode').textContent = mode === 'login' ? "Don't have an account? Register" : 'Already have an account? Login';
        document.getElementById('authEmail').value = '';
        document.getElementById('authPassword').value = '';
        document.getElementById('authName').value = '';
        document.getElementById('authAddress').value = '';
        document.getElementById('authError').classList.remove('show');
        document.getElementById('authModal').classList.add('show');
      }

      function hideAuthModal() {
        document.getElementById('authModal').classList.remove('show');
      }

      function handleAuth() {
        const email = document.getElementById('authEmail').value.trim();
        const password = document.getElementById('authPassword').value;
        const errorEl = document.getElementById('authError');
        
        if (!email || !password) {
          errorEl.textContent = 'Please fill all fields';
          errorEl.classList.add('show');
          return;
        }

        if (authMode === 'register') {
          const name = document.getElementById('authName').value.trim();
          const address = document.getElementById('authAddress').value.trim();
          if (!name || !address) {
            errorEl.textContent = 'Please fill all fields';
            errorEl.classList.add('show');
            return;
          }
          if (users.find(u => u.email === email)) {
            errorEl.textContent = 'Email already registered';
            errorEl.classList.add('show');
            return;
          }
          const newUser = { id: Date.now().toString(), email, name, address, password };
          users.push(newUser);
          currentUser = newUser;
          saveAll();
          hideAuthModal();
          updateUserUI();
          renderCart();
          alert('Account created successfully! Welcome, ' + name);
        } else {
          const user = users.find(u => u.email === email && u.password === password);
          if (!user) {
            errorEl.textContent = 'Invalid email or password';
            errorEl.classList.add('show');
            return;
          }
          currentUser = user;
          saveAll();
          hideAuthModal();
          updateUserUI();
          renderCart();
          alert('Welcome back, ' + user.name + '!');
        }
      }

      function logout() {
        if (confirm('Are you sure you want to logout?')) {
          currentUser = null;
          cart = [];
          saveAll();
          updateUserUI();
          renderCart();
          alert('Logged out successfully');
        }
      }

      // ---------- CART & ORDERS ----------
      function addToCart(productId) {
        if (!currentUser) {
          alert('Please login first to add items to cart!');
          showAuthModal('login');
          return;
        }
        const product = products.find(p => p.id === productId);
        if (!product) return;
        const existing = cart.find(i => i.id === productId);
        existing ? existing.quantity++ : cart.push({...product, quantity: 1});
        saveAll();
        renderCart();
      }

      function removeFromCart(productId) {
        cart = cart.filter(i => i.id !== productId);
        saveAll();
        renderCart();
      }

      function placeOrder() {
        if (!currentUser) { alert('Please login to place order!'); showAuthModal('login'); return; }
        if (!cart.length) { alert('Cart is empty!'); return; }
        const total = cart.reduce((s,i) => s + i.price*i.quantity, 0);
        const order = {
          id: 'ORD' + Date.now().toString().slice(-6),
          customerId: currentUser.id,
          customerName: currentUser.name,
          customerEmail: currentUser.email,
          customerAddress: currentUser.address,
          items: cart.map(i => ({ title: i.title, quantity: i.quantity })),
          total,
          date: new Date().toLocaleString()
        };
        orders.push(order);
        cart = [];
        saveAll();
        renderCart();
        renderAdminOrders();
        alert(`Order placed! Order ID: ${order.id}\nDelivery to: ${currentUser.address}`);
      }

      function showMyOrders() {
        if (!currentUser) { alert('Please login first!'); showAuthModal('login'); return; }
        const myOrders = orders.filter(o => o.customerId === currentUser.id);
        const container = document.getElementById('customerOrdersList');
        container.innerHTML = myOrders.length ? myOrders.reverse().map(o => `
          <div style="background:#f4f4f4;padding:10px;border-radius:8px;margin-bottom:10px;">
            <strong>Order #${o.id}</strong> <small>(${o.date})</small><br>
            Items: ${o.items.map(i => i.title).join(', ')}<br>
            <span style="color:#b12704;">Total: ₹${o.total}</span><br>
            <small>📍 ${o.customerAddress}</small>
          </div>`).join('') : '<p>No orders found.</p>';
        document.getElementById('ordersModal').classList.add('show');
      }

      // ---------- ADMIN ----------
      function openAdminPanel() {
        document.getElementById('adminPanel').classList.add('open');
        document.getElementById('overlay').classList.add('show');
        renderAdminOrders();
      }

      function closeAdminPanel() {
        document.getElementById('adminPanel').classList.remove('open');
        document.getElementById('overlay').classList.remove('show');
      }

      // ---------- EVENT LISTENERS ----------
      document.getElementById('userMenuBtn').addEventListener('click', function(e) {
        e.stopPropagation();
        if (currentUser) {
          document.getElementById('userDropdown').classList.toggle('show');
        } else {
          showAuthModal('login');
        }
      });

      document.addEventListener('click', () => {
        document.getElementById('userDropdown').classList.remove('show');
      });

      document.getElementById('logoutBtn').addEventListener('click', (e) => {
        e.stopPropagation();
        logout();
      });

      document.getElementById('profileBtn').addEventListener('click', (e) => {
        e.stopPropagation();
        if (!currentUser) return;
        document.getElementById('profileInfo').innerHTML = `
          <p><strong>Name:</strong> ${currentUser.name}</p>
          <p><strong>Email:</strong> ${currentUser.email}</p>
          <p><strong>Address:</strong> ${currentUser.address || 'N/A'}</p>
        `;
        document.getElementById('profileModal').classList.add('show');
      });

      document.getElementById('myOrdersBtn').addEventListener('click', (e) => {
        e.stopPropagation();
        showMyOrders();
      });

      document.getElementById('closeProfileBtn').addEventListener('click', () => {
        document.getElementById('profileModal').classList.remove('show');
      });

      document.getElementById('closeOrdersBtn').addEventListener('click', () => {
        document.getElementById('ordersModal').classList.remove('show');
      });

      document.getElementById('settingsBtn').addEventListener('click', () => {
        document.getElementById('passwordModal').classList.add('show');
        document.getElementById('passwordInput').value = '';
        document.getElementById('passwordError').classList.remove('show');
      });

      document.getElementById('submitPasswordBtn').addEventListener('click', () => {
        if (document.getElementById('passwordInput').value === ADMIN_PASSWORD) {
          document.getElementById('passwordModal').classList.remove('show');
          openAdminPanel();
        } else {
          document.getElementById('passwordError').classList.add('show');
        }
      });

      document.getElementById('cancelPasswordBtn').addEventListener('click', () => {
        document.getElementById('passwordModal').classList.remove('show');
      });

      document.getElementById('submitAuthBtn').addEventListener('click', handleAuth);
      document.getElementById('cancelAuthBtn').addEventListener('click', hideAuthModal);
      document.getElementById('toggleAuthMode').addEventListener('click', () => {
        showAuthModal(authMode === 'login' ? 'register' : 'login');
      });

      document.getElementById('placeOrderBtn').addEventListener('click', placeOrder);
      document.getElementById('closeAdminBtn').addEventListener('click', closeAdminPanel);
      document.getElementById('overlay').addEventListener('click', closeAdminPanel);
      document.getElementById('addProductBtn').addEventListener('click', () => {
        const title = document.getElementById('adminTitle').value.trim();
        const price = parseFloat(document.getElementById('adminPrice').value);
        const image = document.getElementById('adminImage').value.trim();
        if (!title || isNaN(price) || price <= 0 || !image) {
          alert('Fill all fields correctly!');
          return;
        }
        products.push({ id: 'p' + Date.now(), title, price, image });
        saveAll();
        renderProducts();
        document.getElementById('adminTitle').value = '';
        document.getElementById('adminPrice').value = '';
        document.getElementById('adminImage').value = '';
        alert('Product added!');
      });
      document.getElementById('clearOrdersBtn').addEventListener('click', () => {
        if (orders.length && confirm('Delete all orders?')) { orders = []; saveAll(); renderAdminOrders(); }
      });

      document.addEventListener('click', e => {
        if (e.target.closest('.add-to-cart-btn')) addToCart(e.target.closest('.add-to-cart-btn').dataset.id);
        if (e.target.closest('.remove-item')) removeFromCart(e.target.closest('.remove-item').dataset.id);
      });

      document.getElementById('searchBtn').addEventListener('click', () => renderProducts(document.getElementById('searchInput').value));
      document.getElementById('searchInput').addEventListener('keyup', e => { if (e.key==='Enter') renderProducts(e.target.value); });
      document.getElementById('cartToggle').addEventListener('click', () => document.getElementById('cartPanel').scrollIntoView({behavior:'smooth'}));

      // Init
      loadData();
      renderProducts();
      renderCart();
      updateUserUI();
    })();
  </script>
</body>
</html>