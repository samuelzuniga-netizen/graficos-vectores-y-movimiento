# Bitácora del laboratorio

## Sesión

- Número de práctica: Vectores y movimiento
- Commit o rama: feat: error-practica vectores y movimiento
- Datos del mock utilizados: datos/mock-request.json (flores F1 = (2, 2) y F2 = (5, 6)) y datos/mock-response.json (ruta [1, 2], velocidad 2 u/s, dirección (0.6, 0.8))

## Pruebas

| Caso y parámetros | Predicción antes de ejecutar | Resultado observado | Explicación o corrección |
|---|---|---|---|
| | | | |
| | | | |
| | | | |

## Error documentado

1. Intento: quitar dt de la linea 15 de Matematicas2D.cs
2. Evidencia: el agente llega demasiado rapido
3. Causa: sin dt, el paso de 2u por cuadrado paso de 60 FPS a 120 FPS, 
4. Corrección: Restaurar MathF.Min(MathF.Max(0, rapidez) * MathF.Max(0, dt), distancia)
5. Explicación: la rapidez esta en u/s al multiplicarlo por dt da una distancia para ese cuadro 

## Datos del proyecto final

| Campo y origen | Unidad o rango | Variable gráfica | Regla de mapeo |
|---|---|---|---|
| | | | |
| | | | |
| | | | |
