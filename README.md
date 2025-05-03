my-shop/
├── public/
│   └── index.html
├── src/
│   ├── assets/               # Imágenes, logos, íconos
│   ├── components/           # Componentes reutilizables (Botón, Navbar, Input, etc)
│   ├── features/             # Dominios funcionales (cart, orders, products)
│   │   ├── cart/
│   │   │   ├── CartContext.jsx
│   │   │   ├── cartSlice.js  # Para Zustand o Redux (opcional)
│   │   │   └── CartView.jsx
│   │   ├── orders/
│   │   │   ├── OrderForm.jsx
│   │   │   ├── OrderSuccess.jsx
│   │   │   └── orderService.js
│   │   └── products/ 
│   │       ├── ProductCard.jsx
│   │       ├── ProductList.jsx
│   │       └── productService.js
│   ├── hooks/                # Custom hooks (useForm, useAuth, etc)
│   ├── layout/               # Navbar, Footer, Layouts con estilos
│   ├── pages/                # Páginas completas (Home, Pedido, Gracias, etc)
│   ├── services/             # Integraciones externas (Firebase, EmailJS, etc)
│   ├── styles/               # Archivos CSS/SCSS o Tailwind config
│   ├── utils/                # Helpers y funciones reutilizables
│   ├── App.jsx
│   ├── main.jsx              # Punto de entrada (Vite) o index.js (CRA)
│   └── router/               # Configuración de rutas (react-router-dom)
│       └── index.jsx
├── .env                     # Variables de entorno
├── firebase.json            # Config Firebase hosting (opcional)
├── package.json
└── README.md