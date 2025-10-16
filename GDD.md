# 🎮 Game Design Document (GDD) – *Nombre del Juego*

## 1. Información General
- **Nombre del juego:** MoleHole
- **Género:** Party / Arcade Competitivo
- **Plataforma:** PC  
- **Modo:** Multijugador en red  
- **Público objetivo:** Todas las edades 
- **Estilo visual:** Cartoon
- **Inspiración:** Los juegos arcade clasicos de las ferias

---

## 2. Concepto del Juego
* 

---

## 3. Mecánicas de Juego
- Movimiento con las teclas numéricas y el ratón.
- Recolección de power-ups en agujeros.
- Si el jugador que controla el mazo logra golpear al topo gana puntos y el topo pierde, pero por cada error del mazo el topo es el que gana puntos y el mazo pierde.
- Marcador visible en tiempo real.
- Contador del timpo que una vez que se llega a cero para el juego.

---

## 4. Controles

| Acción   Pin          | Tecla / Botón               |
|-----------------------|-----------------------------|
| Moverse               | Teclas numéricas            |
| Cojer Power-Up        | Barra espaciadora / Click   |


| Acción   Pom          | Tecla / Botón               |
|-----------------------|-----------------------------|
| Moverse               | Ratón click izquierdo       |
| Cojer Power-Up        | Barra espaciadora / Click   |



---

## 5. Físicas y Escenario
- Mapa cuadrado 2D.  
- Movimiento fluido con inercia ligera.  
- Colisiones simples entre lois jugadores. 
- Power-ups aparecen aleatoriamente.

---

## 6. Arte y Diseño Visual
- **Estilo:** Cartoon 
- **Cámara:** Top–down.  
- **Colores:** Paleta de colores vivos.  
- **Bocetos:** (Aquí puedes pegar imágenes o enlaces a tus bocetos).  
- **Logo:** (Puedes incluirlo más adelante).

---

## 7. Sonido
- **Música:** BGM espacial retro estilo arcade.  
- **Efectos:** Disparos, explosiones, colisiones, aparición de power-ups.

---

## 8. Narrativa
- Los personajes eran dos abogados que eran muy amigos, pero en el momento que ascendieron a Pom a juez su trato hacia Pin cambió.
- **Personajes:**  
  - *Spike* – bulldog espacial.  
  - *Luna* – galga rápida.  
  - *Rex* – pastor alemán táctico.

---

## 9. Diagrama de Flujo
```text
Menú principal → Lobby multijugador → Partida en red
      ↑                                 ↓
   Resultados ← Fin de partida ← Jugadores
