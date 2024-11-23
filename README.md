<html><head><base href="/" />

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Sneaker Shop</title>



<!-- Optimized by loading CSS asynchronously -->

    


    <	n	o	s	c	r	i	p	t	>	<	l	i	n	k	r	e	l	=	"	s	t	y	l	e	s	h	e	e	t	" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"></noscript


    <link rel="preload" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" as="style" onload="this.onload=null;this.rel='stylesheet'">

    <noscript><link	rel="stylesheet"	href="https://cdnjs.cloudflare.com/ajax/libs/font- awesome/6.0.0/css/all.min.css"></noscript>



<!-- Added performance optimizations -->

<link rel="dns-prefetch" href="https://images.unsplash.com">

<link rel="preconnect" href="https://images.unsplash.com">



<!-- Inline critical CSS -->

<style>

:root {

--primary-blue: #0d6efd;

--white: #ffffff;

}



body {

background: linear-gradient(135deg, var(--primary-blue) 0%, var(--white) 100%); min-height: 100vh;

}



.navbar-brand svg { width: 40px; height: 40px; margin-right: 10px;

animation: bounce 2s infinite; will-change: transform;

}



@keyframes bounce {

0%, 100% { transform: translateY(0); } 50% { transform: translateY(-10px); }

}

 

.search-box { position: relative; width: 300px;

}



.search-box input { padding-right: 40px;

}



.search-box .search-icon { position: absolute;

right: 10px; top: 50%;

transform: translateY(-50%);

}



.cart-icon { position: relative;

}



.cart-badge { position: absolute; top: -8px;

right: -8px;

animation: pulse 1.5s infinite; will-change: transform;

}



@keyframes pulse {

0% { transform: scale(1); } 50% { transform: scale(1.2); }

}



.daily-deals-header { padding: 40px 0 20px;

background: linear-gradient(135deg, var(--primary-blue) 0%, var(--white) 100%); margin-bottom: 30px;

border-radius: 15px; color: white;

}



.daily-deals-header h2 { font-size: 2.5rem;

font-weight: bold;

text-shadow: 2px 2px 4px rgba(0,0,0,0.2);

}

 

.daily-deals-header p {

color: rgba(255,255,255,0.9); font-size: 1.2rem;

}



.shoe-card {

transition: transform 0.3s, box-shadow 0.3s; will-change: transform;

border: none; border-radius: 15px;

box-shadow: 0 5px 15px rgba(0,0,0,0.1);

}



.shoe-card:hover { transform: translateY(-5px);

box-shadow: 0 10px 20px rgba(0,0,0,0.2);

}



.shoe-card img {

border-radius: 15px 15px 0 0; height: 250px;

object-fit: cover;

}



.btn-primary { transition: all 0.3s;

will-change: transform;

}



.btn-primary:hover { transform: scale(1.05);

}



.contact-section {

background: rgba(255, 255, 255, 0.9); border-radius: 15px;

padding: 30px; margin-top: 30px;

}



.social-icons i { font-size: 24px; margin: 0 10px;

color: var(--primary-blue); transition: transform 0.3s;

 

will-change: transform;

}



.social-icons i:hover { transform: scale(1.2);

}



.newsletter-form { max-width: 500px; margin: 0 auto;

}



/* Added loading optimizations */ img {

loading="lazy";

}



/* Daily deals styles */

.daily-deal { position: relative; overflow: hidden;

}



.sale-badge { position: absolute; top: 10px;

right: 10px; z-index: 2;

}



.pricing {

margin-bottom: 10px;

}



.original-price { font-size: 0.9em;

margin-right: 10px;

}



.current-price { font-size: 1.2em; font-weight: bold;

}



.stock-info .progress { height: 5px;

 

}



.countdown-timer { background: rgba(0,0,0,0.8); color: white;

padding: 5px 10px; border-radius: 5px; position: absolute; bottom: 10px;

left: 10px;

font-size: 0.8em; z-index: 2;

}



.sizes .btn-outline-secondary { padding: 2px 8px;

font-size: 0.8em;

}



.sizes .btn-outline-secondary:hover { background-color: var(--primary-blue); border-color: var(--primary-blue); color: white;

}

</style>

</head>

<body>



<nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm">

<div class="container">

<a class="navbar-brand d-flex align-items-center" href="https://example.com">

<svg viewBox="0 0 100 100" width="40" height="40">

<path d="M20,50 Q40,20 60,50 T100,50" fill="none" stroke="var(--primary-blue)" stroke-width="8"/>

<path d="M0,50 Q20,80 40,50 T80,50" fill="none" stroke="var(--primary-blue)" stroke-width="8"/>

</svg> Sneaker Shop

</a>



<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">

<span class="navbar-toggler-icon"></span>

</button>



<div class="collapse navbar-collapse" id="navbarNav">

<ul class="navbar-nav me-auto">

<li class="nav-item">

<a class="nav-link" href="https://jd-354.github.io/Z/"><i class="fas fa-home"></i> Inicio</a>

 

</li>

<li class="nav-item">

<a class="nav-link" href="https://example.com/about"><i class="fas fa-info-circle"></i> Sobre Nosotros</a>

</li>

<li class="nav-item dropdown">

<a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">

<i class="fas fa-shoe-prints"></i> Categorías

</a>

<ul class="dropdown-menu">

<li><a class="dropdown-item" href="https://example.com/running">Running</a></li>

<li><a class="dropdown-item" href="https://example.com/basketball">Basketball</a></li>

<li><a class="dropdown-item" href="https://example.com/tennis">Tennis</a></li>

<li><a class="dropdown-item" href="https://example.com/training">Training</a></li>

<li><a class="dropdown-item" href="https://example.com/football">Football</a></li>

</ul>

</li>

</ul>



<div class="search-box me-3">

<input type="text" class="form-control" placeholder="Buscar tenis...">

<i class="fas fa-search search-icon text-muted"></i>

</div>



<div class="cart-icon">

<button class="btn btn-outline-primary position-relative">

<i class="fas fa-shopping-cart"></i>

<span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger"> 3

</span>

</button>

</div>

</div>

</div>

</nav>



<div class="container mb-5">

<div class="daily-deals-header text-center mb-4">

<h2>Ofertas Diarias</h2>

<p class="text-muted">Las ofertas se actualizan cada 24 horas</p>

</div>



<!-- Filters section -->

<div class="filters mb-4">

<div class="row">

<div class="col-md-3">

<select class="form-select" id="brandFilter">

 

<option value="">Todas las marcas</option>

<option value="nike">Nike</option>

<option value="adidas">Adidas</option>

<option value="puma">Puma</option>

<option value="reebok">Reebok</option>

</select>

</div>

<div class="col-md-3">

<select class="form-select" id="categoryFilter">

<option value="">Todas las categorías</option>

<option value="running">Running</option>

<option value="training">Training</option>

<option value="basketball">Basketball</option>

<option value="football">Football</option>

</select>

</div>

<div class="col-md-3">

<select class="form-select" id="priceFilter">

<option value="">Precio</option>

<option value="0-50">$0 - $50</option>

<option value="51-100">$51 - $100</option>

<option value="101-150">$101 - $150</option>

<option value="151+">$151+</option>

</select>

</div>

<div class="col-md-3">

<select class="form-select" id="sizeFilter">

<option value="">Talla</option>

<option value="7">7</option>

<option value="8">8</option>

<option value="9">9</option>

<option value="10">10</option>

<option value="11">11</option>

</select>

</div>

</div>

</div>



<!-- Daily deals container -->

<div class="row" id="dailyDeals">

<!-- Content will be dynamically populated by JavaScript -->

</div>

</div>



<div class="container mb-5">

<div class="contact-section">

 

<h2 class="text-center mb-4">Contáctanos</h2>

<div class="row">

<div class="col-md-6 mb-4">

<img src="https://images.unsplash.com/photo-1497366754035-f200968a6e72" alt="Modern office interior with comfortable meeting space" class="img-fluid mb-4 rounded" width="500" height="300">

<h4><i class="fas fa-map-marker-alt"></i> Ubicación</h4>

<p>Calle Principal #123, Ciudad</p>



<h4><i class="fas fa-phone"></i> Teléfono</h4>

<p>+1 234 567 8900</p>



<h4><i class="fas fa-envelope"></i> Email</h4>

<p>contacto@sneakershop.com</p>



<div class="social-icons mt-4">

<a href="https://facebook.com" target="_blank"><i class="fab fa-facebook"></i></a>

<a href="https://instagram.com" target="_blank"><i class="fab fa-instagram"></i></a>

<a href="https://twitter.com" target="_blank"><i class="fab fa-twitter"></i></a>

<a href="https://youtube.com" target="_blank"><i class="fab fa-youtube"></i></a>

</div>

</div>



<div class="col-md-6">

<div class="newsletter-form">

<img src="https://images.unsplash.com/photo-1557200134-90327ee9fafa" alt="Sneaker enthusiast newsletter signup background" class="img-fluid mb-4 rounded" width="500" height="300">

<h4 class="text-center mb-3">Suscríbete para recibir novedades</h4>

<form>

<div class="mb-3">

<input type="text" class="form-control" placeholder="Nombre completo" required>

</div>

<div class="mb-3">

<input type="email" class="form-control" placeholder="Email" required>

</div>

<div class="mb-3">

<select class="form-select">

<option selected>Elige tu marca favorita</option>

<option value="jordan">Jordan</option>

<option value="nike">Nike</option>

<option value="adidas">Adidas</option>

<option value="puma">Puma</option>

</select>

</div>

<button type="submit" class="btn btn-primary w-100">

<i class="fas fa-paper-plane"></i> Suscribirse

</button>

 

</form>

</div>

</div>

</div>

</div>

</div>



<footer class="bg-white py-4 mt-auto">

<div class="container text-center">

<p class="mb-0">&copy; 2023 Sneaker Shop. Todos los derechos reservados.</p>

</div>

</footer>



<!-- Optimized script loading -->

<script defer src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>



<!-- Added performance optimization script -->

<script>

// Updated mock deals data const mockDealData = [

{

id: 1,

name: "Nike Air Zoom Pegasus 38",

description: "Premium running shoes with responsive cushioning", originalPrice: 129.99,

salePrice: 89.99,

discount: 30,

stockLevel: 75,

image: "https://images.unsplash.com/photo-1600185365926-3a2ce3cdb9eb", brand: "Nike",

category: "Running", sizes: [7,8,9,10,11]

},

{

id: 2,

name: "Adidas Ultraboost 21",

description: "High-performance running shoes with energy return", originalPrice: 179.99,

salePrice: 129.99,

discount: 27,

stockLevel: 50,

image: "https://images.unsplash.com/photo-1587563871167-1ee9c731aefb", brand: "Adidas",

category: "Running", sizes: [7,8,9,10]

},

 

{

id: 3,

name: "Puma RS-X³",

description: "Retro-inspired chunky sneakers", originalPrice: 149.99,

salePrice: 99.99,

discount: 33,

stockLevel: 60,

image: "https://images.unsplash.com/photo-1608231387042-66d1773070a5", brand: "Puma",

category: "Lifestyle", sizes: [8,9,10,11]

},

{

id: 4,

name: "Nike Air Max 270",

description: "Street-ready sneakers with Air cushioning", originalPrice: 169.99,

salePrice: 129.99,

discount: 23,

stockLevel: 45,

image: "https://images.unsplash.com/photo-1549298916-b41d501d3772", brand: "Nike",

category: "Lifestyle", sizes: [7,8,9,10]

},

{

id: 5,

name: "New Balance Fresh Foam X",

description: "Cushioned running shoes for daily training", originalPrice: 159.99,

salePrice: 119.99,

discount: 25,

stockLevel: 40,

image: "https://images.unsplash.com/photo-1465453869711-7e174808ace9", brand: "New Balance",

category: "Running", sizes: [7,8,9,10]

},

{

id: 6,

name: "Adidas NMD R1",

description: "Modern streetwear with Boost cushioning", originalPrice: 139.99,

salePrice: 99.99,

discount: 28,

 

stockLevel: 55,

image: "https://images.unsplash.com/photo-1582588678413-dbf45f4823e9", brand: "Adidas",

category: "Lifestyle", sizes: [8,9,10,11]

},

{

id: 7,

name: "Nike Zoom Freak",

description: "Basketball shoes with responsive feel", originalPrice: 189.99,

salePrice: 149.99,

discount: 21,

stockLevel: 35,

image: "https://images.unsplash.com/photo-1605348532760-6753d2c43329", brand: "Nike",

category: "Basketball", sizes: [8,9,10,11,12]

},

{

id: 8,

name: "Under Armour HOVR",

description: "Performance running shoes with energy return", originalPrice: 144.99,

salePrice: 109.99,

discount: 24,

stockLevel: 48,

image: "https://images.unsplash.com/photo-1491553895911-0055eca6402d", brand: "Under Armour",

category: "Running", sizes: [7,8,9,10]

}

];



// Enhance the daily deals manager with better refresh logic const dailyDealsManager = {

deals: [], lastUpdate: null,



async fetchDeals() { try {

// Simulating API response with mock data this.deals = mockDealData; this.lastUpdate = new Date(); this.updateUI(); this.saveToLocalStorage();

 

} catch (error) {

console.error('Error fetching deals:', error);

}

},



saveToLocalStorage() {

localStorage.setItem('lastUpdate', this.lastUpdate.toISOString()); localStorage.setItem('deals', JSON.stringify(this.deals));

},



formatPrice(price) { return price.toFixed(2);

},



calculateTimeRemaining() { const now = new Date(); const midnight = new Date(); midnight.setHours(24,0,0,0);

const timeRemaining = midnight - now;



const hours = Math.floor(timeRemaining / (1000 * 60 * 60));

const minutes = Math.floor((timeRemaining % (1000 * 60 * 60)) / (1000 * 60));



return `${hours}h ${minutes}m`;

},



updateUI() {

const dealsContainer = document.getElementById('dailyDeals'); if (!dealsContainer) return;



const timeRemaining = this.calculateTimeRemaining(); const fragment = document.createDocumentFragment();



this.deals.forEach(deal => {

const dealElement = document.createElement('div'); dealElement.className = 'col-lg-3 col-md-4 col-sm-6 mb-4'; dealElement.innerHTML = `

<div class="card shoe-card daily-deal">

<div class="sale-badge">

<span class="badge bg-danger">-${deal.discount}%</span>

</div>

<img src="${deal.image}" class="card-img-top"

alt="${deal.name} - ${deal.description}" width="300"

height="200"

 

loading="lazy">

<div class="countdown-timer"> Termina en: ${timeRemaining}

</div>

<div class="card-body">

<h5 class="card-title">${deal.name}</h5>

<div class="pricing">

<span	class="original-price	text-muted	text-decoration-line- through">$${this.formatPrice(deal.originalPrice)}</span>

<span class="current-price text-danger">$${this.formatPrice(deal.salePrice)}</span>

</div>

<p class="card-text">${deal.description}</p>

<div class="sizes mb-2">

<small class="text-muted">Tallas disponibles:</small>

<div class="d-flex gap-1 mt-1">

${deal.sizes.map(size => `

<button class="btn btn-outline-secondary btn-sm">${size}</button>

`).join('')}

</div>

</div>

<div class="stock-info mb-2">

<small class="text-muted">Stock disponible: ${deal.stockLevel}</small>

<div class="progress">

<div class="progress-bar bg-success" style="width: ${(deal.stockLevel/100)*100}%"></div>

</div>

</div>

<button class="btn btn-primary w-100">

<i class="fas fa-cart-plus"></i> Añadir al carrito

</button>

</div>

</div>

`; fragment.appendChild(dealElement);

});



dealsContainer.innerHTML = ''; dealsContainer.appendChild(fragment);

},



checkAndUpdate() {

const lastUpdateStr = localStorage.getItem('lastUpdate'); if (!lastUpdateStr) {

this.fetchDeals(); return;

}

 

const lastUpdate = new Date(lastUpdateStr); const now = new Date();

const hoursSinceUpdate = (now - lastUpdate) / (1000 * 60 * 60);



// Refresh if more than 24 hours have passed if (hoursSinceUpdate >= 24) { this.fetchDeals();

} else {

const savedDeals = localStorage.getItem('deals'); if (savedDeals) {

this.deals = JSON.parse(savedDeals); this.lastUpdate = lastUpdate; this.updateUI();

} else { this.fetchDeals();

}

}

},



init() { this.checkAndUpdate();

// Update countdown every minute setInterval(() => this.updateUI(), 60000);

// Check for new deals every hour

setInterval(() => this.checkAndUpdate(), 3600000);

}

};



// Initialize daily deals when DOM is loaded document.addEventListener('DOMContentLoaded', () => { dailyDealsManager.init();

}, { passive: true });

</script>



      </body></html>

