# 🎮 Game Design Document (GDD) – *Nombre del Juego*

## 1. Información General
- **Nombre del juego:** Space Dogs Battle  
- **Género:** Shooter / Acción 2D  
- **Plataforma:** PC  
- **Modo:** Multijugador en red (no por turnos)  
- **Público objetivo:** 12+  
- **Estilo visual:** Pixel Art, vista top–down  
- **Inspiración:** Asteroids, Enter the Gungeon, Geometry Wars

---

## 2. Concepto del Juego
*

---

## 3. Mecánicas de Juego
- Movimiento con WASD o flechas.
- Disparo con clic izquierdo / barra espaciadora.
- Recolección de power-ups en el mapa.
- Colisiones con proyectiles → pérdida de puntos de vida.
- Los jugadores reaparecen tras morir.
- Marcador visible en tiempo real.

---

## 4. Controles
| Acción               | Tecla / Botón              |
|-----------------------|-----------------------------|
| Moverse               | WASD                        |
| Disparar              | Barra espaciadora / Click   |
| Habilidad especial    | Shift                       |
| Pausa / Menú          | Esc                         |

---

## 5. Físicas y Escenario
- Mapa rectangular 2D.  
- Movimiento fluido con inercia ligera.  
- Colisiones simples entre jugadores, proyectiles y muros.  
- Power-ups aparecen aleatoriamente.

---

## 6. Arte y Diseño Visual
- **Estilo:** Pixel art.  
- **Cámara:** Top–down.  
- **Colores:** Paleta retro (azules, verdes y rojos brillantes).  
- **Bocetos:** (Aquí puedes pegar imágenes o enlaces a tus bocetos).  
- **Logo:** (Puedes incluirlo más adelante).

---

## 7. Sonido
- **Música:** BGM espacial retro estilo arcade.  
- **Efectos:** Disparos, explosiones, colisiones, aparición de power-ups.

---

## 8. Narrativa
- Año 3025. En la galaxia “Canina”, las razas de perros compiten por territorios espaciales. Cada jugador representa una facción y lucha por dominar los planetas.  
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
