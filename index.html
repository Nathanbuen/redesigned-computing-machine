<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .header {
            background-color: #ff5722;
            color: white;
            padding: 10px 20px;
            text-align: center;
            position: relative;
        }
        .header h1 {
            margin: 0;
        }
        .nav {
            background-color: #333;
            overflow: hidden;
        }
        .nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        .nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .nav .cart-button {
            float: right;
            background-color: #ff5722;
            border: none;
            color: white;
            padding: 14px 20px;
            cursor: pointer;
            position: relative;
        }
        .nav .cart-button:hover {
            background-color: #e64a19;
        }
        .nav .cart-count {
            position: absolute;
            top: 8px;
            right: 8px;
            background-color: red;
            color: white;
            border-radius: 50%;
            padding: 5px 10px;
            font-size: 12px;
        }
        .container {
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 4px;
            padding: 16px;
            margin: 16px;
            text-align: center;
            width: 300px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            transition: box-shadow 0.3s;
        }
        .product:hover {
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-bottom: 1px solid #ddd;
            margin-bottom: 15px;
        }
        .product h2 {
            font-size: 20px;
            margin: 10px 0;
        }
        .product p {
            color: #757575;
        }
        .product button {
            background-color: #ff5722;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 4px;
        }
        .product button:hover {
            background-color: #e64a19;
        }
        .cart-modal {
            display: none;
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0,0,0,0.5);
            padding-top: 60px;
        }
        .cart-modal-content {
            background-color: white;
            margin: 5% auto;
            padding: 20px;
            border: 1px solid #ddd;
            width: 80%;
            max-width: 500px;
            border-radius: 4px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .cart-modal-content h2 {
            font-size: 20px;
            margin-top: 0;
        }
        .cart-modal-content ul {
            list-style-type: none;
            padding: 0;
        }
        .cart-modal-content ul li {
            margin-bottom: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .cart-modal-content ul li span {
            margin-right: 10px;
        }
        .cart-modal-content ul li button {
            background-color: #e64a19;
            color: white;
            border: none;
            padding: 5px;
            cursor: pointer;
            border-radius: 4px;
        }
        .cart-modal-content ul li input {
            width: 40px;
            text-align: center;
        }
        .cart-modal-content .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
        }
        .cart-modal-content .close:hover,
        .cart-modal-content .close:focus {
            color: black;
            text-decoration: none;
            cursor: pointer;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        @media (max-width: 768px) {
            .product {
                width: 100%;
            }
            .cart-modal-content {
                width: 100%;
                max-width: none;
                margin: 0 10px;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Loja Online</h1>
    </div>
    <div class="nav">
        <a href="#home">Home</a>
        <a href="#produtos">Produtos</a>
        <a href="#contato">Contato</a>
        <a href="#sobre">Sobre</a>
        <button class="cart-button" onclick="openCartModal()">Carrinho
            <span id="cart-count" class="cart-count">0</span>
        </button>
    </div>
    <div class="container">
        <div class="product">
            <img src="produto1.jpg" alt="Produto 1">
            <h2>Produto 1</h2>
            <p>R$ 100,00</p>
            <button onclick="addToCart('Produto 1', 100)">Adicionar ao Carrinho</button>
        </div>
        <div class="product">
            <img src="produto2.jpg" alt="Produto 2">
            <h2>Produto 2</h2>
            <p>R$ 150,00</p>
            <button onclick="addToCart('Produto 2', 150)">Adicionar ao Carrinho</button>
        </div>
        <div class="product">
            <img src="produto3.jpg" alt="Produto 3">
            <h2>Produto 3</h2>
            <p>R$ 200,00</p>
            <button onclick="addToCart('Produto 3', 200)">Adicionar ao Carrinho</button>
        </div>
        <!-- Adicione mais produtos conforme necessário -->
    </div>
    <div id="cartModal" class="cart-modal">
        <div class="cart-modal-content">
            <span class="close" onclick="closeCartModal()">&times;</span>
            <h2>Carrinho de Compras</h2>
            <ul id="cart-items"></ul>
            <p>Total: R$ <span id="cart-total">0,00</span></p>
        </div>
    </div>
    <div class="footer">
        <p>&copy; 2024 Loja Online. Todos os direitos reservados.</p>
    </div>
    <script>
        let cart = JSON.parse(localStorage.getItem('cart')) || [];
        let total = parseFloat(localStorage.getItem('total')) || 0;

        function addToCart(productName, productPrice) {
            const existingItem = cart.find(item => item.name === productName);
            if (existingItem) {
                existingItem.quantity += 1;
            } else {
                cart.push({ name: productName, price: productPrice, quantity: 1 });
            }
            total += productPrice;
            saveCart();
            renderCart();
        }

        function removeFromCart(productName) {
            const itemIndex = cart.findIndex(item => item.name === productName);
            if (itemIndex !== -1) {
                const item = cart[itemIndex];
                total -= item.price * item.quantity;
                cart.splice(itemIndex, 1);
                saveCart();
                renderCart();
            }
        }

        function updateQuantity(productName, newQuantity) {
            const item = cart.find(item => item.name === productName);
            if (item && newQuantity > 0) {
                total += (newQuantity - item.quantity) * item.price;
                item.quantity = newQuantity;
                saveCart();
                renderCart();
            }
        }

        function saveCart() {
            localStorage.setItem('cart', JSON.stringify(cart));
            localStorage.setItem('total', total.toFixed(2));
        }

        function renderCart() {
            const cartItems = document.getElementById('cart-items');
            const cartTotal = document.getElementById('cart-total');
            const cartCount = document.getElementById('cart-count');
            cartItems.innerHTML = '';
            let itemCount = 0;
            cart.forEach(item => {
                itemCount += item.quantity;
                const li = document.createElement('li');
                li.innerHTML = `
                    <span>${item.name} - R$ ${item.price.toFixed(2)} x ${item.quantity}</span>
                    <input type="number" value="${item.quantity}" min="1" onchange="updateQuantity('${item.name}', this.value)">
                    <button onclick="removeFromCart('${item.name}')">Remover</button>
                `;
                cartItems.appendChild(li);
            });
            cartTotal.textContent = total.toFixed(2);
            cartCount.textContent = itemCount;
            if (itemCount > 0) {
                cartCount.style.display = 'block';
            } else {
                cartCount.style.display = 'none';
            }
        }

        function openCartModal() {
            document.getElementById('cartModal').style.display = 'block';
        }

        function closeCartModal() {
            document.getElementById('cartModal').style.display = 'none';
        }

        document.addEventListener('DOMContentLoaded', renderCart);
        window.onclick = function(event) {
            if (event.target == document.getElementById('cartModal')) {
                closeCartModal();
            }
        }
    </script>
</body>
</html>
