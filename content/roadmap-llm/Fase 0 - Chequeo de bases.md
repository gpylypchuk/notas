---
title: Fase 0 - Chequeo de bases
tags: [roadmap, llm, fundamentos]
fase: 0
---

# Fase 0. Chequeo rápido de bases

> [!tip] No hace falta un curso entero
> Solo confirmar que estos temas están sólidos antes de avanzar. Si algo de esto falla, para ahí primero.

## Álgebra lineal aplicada

- [ ] Producto matricial y su interpretación geométrica (transformación lineal, no solo mecánica de cálculo)
- [ ] Descomposición en valores singulares (SVD)
- [ ] Autovalores y autovectores, diagonalización
- [ ] Normas de vectores y matrices (L1, L2, Frobenius)
- [ ] Multiplicación por bloques. Esto vuelve relevante más adelante para entender tiling en kernels CUDA (Fase 5)

## Probabilidad y entropía

- [ ] Distribuciones de probabilidad discretas y continuas
- [ ] Entropía de Shannon, qué mide exactamente
- [ ] KL divergence, por qué aparece al comparar distribuciones de probabilidad
- [ ] Cross entropy como función de costo. Entender por qué es la elección natural para predicción de próximo token

## Backpropagation

- [ ] Regla de la cadena aplicada a un grafo computacional, no solo a una función compuesta simple
- [ ] Diferencia entre forward pass y backward pass
- [ ] Derivar a mano el gradiente de un MLP de dos capas, sin autograd, sin mirar apuntes

## Recursos si algo falla

- CS231n de Stanford, específicamente las clases sobre backpropagation
- 3Blue1Brown, serie de álgebra lineal y la serie de redes neuronales, para intuición visual

> [!success] Hito de la fase
> Poder derivar a mano el gradiente de una red de dos capas sin mirar apuntes, y explicar en una frase qué mide la cross entropy.

## Mis notas

[[Notas - Fase 0]]

## Navegación

→ [[Fase 1 - Transformer desde cero]]

#fase-0
