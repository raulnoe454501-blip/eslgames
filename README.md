# ESL Games 2

Proyecto organizado con menú principal, juegos separados y bancos editables.

## Estructura

- `index.html`: menú principal para abrir los juegos.
- `admin-bancos.html`: guía rápida para editar bancos.
- `juegos/`: juegos HTML.
- `bancos/`: bancos de palabras por juego.
- `assets/css/home.css`: estilos del menú.

## Juegos incluidos

- Ahorcado: `juegos/ahorcado.html` → banco `bancos/ahorcado-bank.js`
- Anagrama: `juegos/anagrama.html` → banco `bancos/anagrama-bank.js`
- Memory Game: `juegos/memory.html` → banco `bancos/memory-bank.js`
- Word Match: `juegos/word-match.html` → banco `bancos/word-match-bank.js`
- Word Search: `juegos/word-search.html` → banco `bancos/word-search-bank.js`

## Cómo agregar palabras desde GitHub

1. Abre la carpeta `bancos`.
2. Abre el archivo del juego, por ejemplo `ahorcado-bank.js`.
3. Presiona el lápiz de edición.
4. Agrega palabras respetando el formato existente.
5. Guarda con `Commit changes`.

## Nota

Los HTML originales se conservaron como juegos independientes, pero ahora cargan su banco desde archivos externos en `bancos/`.
