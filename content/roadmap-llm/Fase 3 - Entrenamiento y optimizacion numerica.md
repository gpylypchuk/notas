---
title: Fase 3 - Entrenamiento y optimizacion numerica
tags: [roadmap, llm, entrenamiento]
fase: 3
---

# Fase 3. Entrenamiento y optimización numérica

## Precisión numérica

- [ ] Diferencia entre bf16, fp16 y fp32
- [ ] Por qué bf16 es más estable para entrenamiento (mismo rango de exponente que fp32, menos bits de mantisa)
- [ ] Loss scaling cuando se entrena en fp16, y por qué bf16 generalmente no lo necesita

## Estabilización del entrenamiento

- [ ] Gradient checkpointing, el trade-off entre memoria y cómputo que implica
- [ ] Learning rate warmup, por qué hace falta al inicio del entrenamiento y no solo un LR constante
- [ ] Gradient clipping, cómo evita la explosión de gradientes en las primeras iteraciones

## Leyes de escala

- [ ] Kaplan et al. (2020), relación entre parámetros, datos, compute y loss
- [ ] Chinchilla, Hoffmann et al. (2022), ratio óptimo de tokens por parámetro, y por qué corrigió a Kaplan
- [ ] Saber usar esto en la práctica, dado un presupuesto de compute fijo, calcular qué combinación de tamaño de modelo y cantidad de datos conviene

## Reproducción de referencia

- [ ] Reproducir el reentrenamiento de GPT-2 de Karpathy usando llm.c o build-nanogpt
- [ ] Correrlo en hardware alquilado (no local), documentando curvas de pérdida reales, no solo el resultado final

> [!success] Hito de la fase
> GPT-2 chico (124M parámetros) reproducido desde cero, con curvas de pérdida documentadas y comparadas contra las publicadas por OpenAI.

## Mis notas

[[Notas - Fase 3]]

## Navegación

← [[Fase 2 - Tokenizacion y datos]] | → [[Fase 4 - Arquitectura de computadoras (Onur Mutlu)]]

#fase-3
