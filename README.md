# PokeApi + Astro ⚡️
![PokeApi + Astro image](Poke_img.jpg)
Una aplicación web moderna para explorar información sobre Pokémon, construida con [Astro](https://astro.build/), estilizada con [Tailwind CSS](https://tailwindcss.com/) y que consume datos de [PokeAPI](https://pokeapi.co/).

## Características

- Interfaz responsive diseñada con Tailwind CSS
- Carga de datos optimizada gracias a Astro
- Sitio web estático a través de API
- Paginación estática

## 🚀 Tecnologías

- **[Astro](https://astro.build/)**
- **[Tailwind CSS](https://tailwindcss.com/)**
- **[PokeAPI](https://pokeapi.co/)**
- [HTML, CSS, JavaScript, TypeScript]

## 🛠️ Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/Fernandomr23/astro-pokemon.git astro-pokemon
cd astro-pokemon
```

2. Instala las dependencias:
```bash
npm install
# o
yarn install
# o
pnpm install
```

3. Inicia el servidor de desarrollo:
```bash
npm run dev
# o
yarn dev
# o
pnpm dev
```

4. Abre [localhost:4321](http://localhost:4321) en tu navegador.

## 🏗️ Estructura del proyecto

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── PokemonCard.astro
│   ├── const/
│   │   └── site-info.ts
│   ├── interfaces/
│   │   └── pokemon-list.response.ts
│   ├── layouts/
│   │   └── MainLayout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── pokemon/[id].astro
│   │   └── pokemons
│	│			├── [name].astro
│   │   		└── [page].astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── tsconfig.json
└── package.json
```

## 📝 API utilizada

Este proyecto consume la [PokeAPI](https://pokeapi.co/), una API RESTful gratuita que proporciona datos detallados sobre el universo Pokémon. No se requiere API key para su uso, pero respeta los límites de tasa para evitar ser bloqueado.

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto:

1. Haz fork del repositorio
2. Crea una nueva rama (`git checkout -b feature/amazing-feature`)
3. Realiza tus cambios
4. Haz commit de tus cambios (`git commit -m 'Add amazing feature'`)
5. Haz push a la rama (`git push origin feature/amazing-feature`)
6. Abre un Pull Request