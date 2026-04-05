# Alkemy Challenge 🍿

Challenge técnico iOS para [Alkemy](https://www.alkemy.org/). Aplicación de películas consumiendo la API de [The Movie Database (TMDb)](https://www.themoviedb.org/).

## Funcionalidades

- Listado de películas top y por género
- Vista de detalle de película
- Login de usuario
- Menú principal con navegación

## Tecnologías y decisiones de diseño

- **Lenguaje:** Swift
- **Arquitectura:** MVVM
- **Networking:** Alamofire
- **Vistas:** XIBs (sin Storyboards)
- **Gestión de dependencias:** CocoaPods
- **API:** [TMDb](https://developers.themoviedb.org/3)

## Estructura

```
Alkeflix/
├── Model/
│   └── Movies Struct/
├── Service/
│   └── APIClient.swift
├── View/
│   ├── Login/
│   ├── Main Menu/
│   ├── List of Top Movies/
│   ├── List of Genre Movies/
│   └── Movie View/
└── ViewModel/
    └── MoviesViewModel.swift
```

## Requisitos

- Xcode 13+
- iOS 14+
- CocoaPods
- API Key de TMDb (gratuita — [registrarse aquí](https://www.themoviedb.org/signup))

## Instalación

```bash
git clone https://github.com/lucas-dilorenzo/Alkemy-Challenge.git
cd Alkemy-Challenge
pod install
open Alkeflix.xcworkspace
```

> Reemplazar la API key de TMDb en `APIClient.swift` con la propia antes de correr la app.
