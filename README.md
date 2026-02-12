# ayudando-en-lo-que-se-pueda
plataforma de educación chile
ayudando-en-lo-que-se-pueda/
│
├── backend/
│   ├── app.py                 # App principal Flask
│   ├── models.py              # Modelos de BD
│   ├── config.py              # Configuración
│   ├── requirements.txt        # Dependencias
│   └── utils/
│       ├── paypal.py          # Integración PayPal
│       └── auth.py            # Autenticación
│
├── frontend/
│   ├── index.html             # Página principal
│   ├── cursos.html            # Listado de cursos
│   ├── curso-detalle.html     # Detalle curso
│   ├── perfil.html            # Perfil usuario
│   ├── admin.html             # Panel admin
│   ├── css/
│   │   ├── style.css          # Estilos principales
│   │   └── responsive.css     # Responsive design
│   └── js/
│       ├── main.js            # JavaScript principal
│       ├── paypal.js          # Integración PayPal JS
│       └── admin.js           # Admin funciones
│
├── data/
│   └── cursos-ejemplo.json    # Cursos de ejemplo
│
├── .env.example               # Variables de entorno
├── .gitignore
├── README.md                  # Documentación completa
├── LICENSE                    # MIT License
└── requirements.txt
