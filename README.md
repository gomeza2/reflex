# REFLEX — Reaction Lab

Aplicación web de minijuegos para entrenar reflejos, concentración, memoria y velocidad mental. Interfaz en español, diseño responsive y récords guardados localmente.

## Ejecutar

Requiere Node.js 20.19+ o 22.12+.

```bash
npm install
npm run dev
```

Abrí la URL local que muestra Vite, normalmente `http://localhost:5173`.

## Producción

```bash
npm run build
npm run preview
```

## Minijuegos
- Reacción sorpresa: esperá la señal y tocá el color correcto; los toques anticipados penalizan.
- Colores engañosos: respondé al color de la tinta, no a la palabra.
- Atrapar objetos: tocá círculos del color objetivo y sumá combos.
- Decisiones rápidas: respondé preguntas contra reloj.
- Memoria de colores: repetí secuencias que crecen de nivel.
- Modo caos: mezcla desafíos de reacción, tinta y decisión.

Incluye niveles, cuenta regresiva, tiempos con `performance.now()`, estadísticas, sonidos sintetizados, almacenamiento local y diseño para móvil/tablet/escritorio. Los récords se guardan en el navegador y no se sincronizan entre dispositivos.
