# ♟️ Ajedrez en Java con Interfaz Gráfica

> Un elegante y completo juego de ajedrez hecho en Java con interfaz gráfica. Ideal para jugar contra otro jugador humano en el mismo equipo. ¡Diseño atractivo, experiencia fluida y completamente funcional!
## 📖 Tabla de Contenidos
- [Características](#-características)
- [Instalación](#-instalación)
- [Uso](#-uso)
- [Capturas](#-capturas)
- [Tecnologías](#-tecnologías)
- [Estructura del proyecto](#-estructura)
- [Licencia](#-licencia)

## 🧩 Características

✅ Interfaz gráfica amigable con Swing  
✅ Movimiento legal de piezas implementado  
✅ Detección de jaque y jaque mate  
✅ Soporte para coronación de peones  
✅ Tablero interactivo (click en piezas y casillas)  
✅ Colores personalizables  
✅ Reinicio de partida con un solo clic  

---
## 🚀 Instalación

### 1. Clona el repositorio

```bash
git clone https://github.com/tuusuario/ajedrez-java-gui.git
cd ajedrez-java-gui
2. Compila el código
javac src/*.java
3. Ejecuta el programa
java -cp src Main
📦 También puedes importar el proyecto directamente en Eclipse, IntelliJ IDEA o tu IDE favorito.
```
---
## 🚀 Uso
```bash
- Abre tu IDE de preferencia
- Importa el proyecto dentro del IDE
- Ejecuta el Main
- Selecciona una opcion de colores de tablero
- Juega y diviertete
```
## 🖥️ Capturas de pantalla
### Seleccion de los colores del Tablero
![Seleccion del Tablero](docs/Menu_Seleccion.png)
### Tablero Seleccionado
![Tablero Color 1](docs/Tablero.png)
### Movimiento de las piezas
![Prueba Movimiento](docs/Movimiento_Base.png)
### Seleccion de la ficha (cuando el peon llega a la otra parte)
![Seleccion de Ficha](docs/Llegada_Peon_Fin_Tablero.png)
### Game Over Screen
![Fin Juego](docs/Game_Over.png)
### Otro Tablero
![Otro Tablero](docs/Otro_Color_Tablero.png)

## 🛠️ Tecnologías utilizadas

- Java 8+  
- Swing (javax.swing)  
- POO (Programación Orientada a Objetos)

## 💡 Estructura del proyecto
```bash
Ajedrez-Master/
│
├── src/
│   └── Main/
|   |       ├── Board.java
│   |       ├── GamePanel.java
│   |       ├── Main.java
│   |       ├── Rey.java
│   |       ├── Mouse.java
|   |       └── Type.java
|   └── Piece/
│          ├── Bishop.java
│          ├── King.java
│          ├── Knight.java
│          ├── Pawn.java
│          ├── Piece.java
│          ├── Queen.java
|          └── Rook.java
|    
│
├── res/
│   └── piece/
│          └── /*Todas las imagenes de cada pieza, blanco y negro*/
│
└── README.md
```
## 📜 Licencia

![GitHub license](https://img.shields.io/github/license/Adri-Coding-Dev/Master_Chess)
![Made with Java](https://img.shields.io/badge/Made%20with-Java-blue)

MIT License
Copyright (c) 2025 Adri-Coding-Dev
