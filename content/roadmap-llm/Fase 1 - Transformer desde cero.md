---
title: Fase 1 - Transformer desde cero
tags: [roadmap, llm, transformers]
fase: 1
---

# Fase 1. Transformer desde cero, sin atajos

> [!info] Objetivo
> Escribir un GPT chico con tus propias manos en PyTorch puro, sin usar `transformers` de Hugging Face como muleta.

## Paper base

- [ ] Leer "Attention Is All You Need" completo, prestando atención específica a
  - [ ] Self-attention y la tripleta Q/K/V
  - [ ] Multi-head attention, por qué varias cabezas en vez de una sola grande
  - [ ] Positional encoding sinusoidal, por qué hace falta si no hay recurrencia
  - [ ] Feed-forward layers, layer norm, residual connections

## Implementación guiada

- [ ] Seguir "The Annotated Transformer" (Harvard NLP) línea por línea, del paper al código, implementando cada bloque vos mismo en paralelo a la lectura

## Serie de Karpathy (Neural Networks Zero to Hero)

- [ ] micrograd, autograd desde cero, para entender qué hace un framework por debajo
- [ ] makemore, de bigramas a MLP, antes de llegar a atención
- [ ] "Let's build GPT from scratch", el video central de esta fase
- [ ] "Let's reproduce GPT-2", que sirve de puente hacia la Fase 3

## Implementación propia

- [ ] Reproducir nanoGPT a mano, sin copiar bloques enteros
- [ ] Entrenarlo en un dataset chico (tiny shakespeare sirve)
- [ ] Confirmar que el loss baja de forma consistente y el texto generado es coherente, no solo que corre sin error

> [!success] Hito de la fase
> Modelo propio de unos pocos millones de parámetros generando texto coherente, entrenado por vos, sin copiar y pegar bloques enteros de otro repo.

## Mis notas

[[Notas - Fase 1]]

## Navegación

← [[Fase 0 - Chequeo de bases]] | → [[Fase 2 - Tokenizacion y datos]]

#fase-1
