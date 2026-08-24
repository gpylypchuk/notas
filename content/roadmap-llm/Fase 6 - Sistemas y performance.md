---
title: Fase 6 - Sistemas y performance
tags: [roadmap, llm, gpu-infra, performance-engineering]
fase: 6
---

# Fase 6. Sistemas y performance

> [!info] Acá se une con el plan de GPU infra
> Con [[Fase 4 - Arquitectura de computadoras (Onur Mutlu)]] y [[Fase 5 - C++ y CUDA]] ya hechas, esta fase se vuelve mucho más digerible.

## PMPP (Programming Massively Parallel Processors)

- [ ] Modelo de ejecución SIMT (single instruction, multiple threads)
- [ ] Coalescing de memoria, conexión directa con lo visto en la Fase 4 sobre row buffer
- [ ] Ocupancy y latency hiding como estrategia central de las GPUs

## GPU MODE

- [ ] Ver cómo se optimizan kernels reales en producción, no solo ejercicios de libro

## Triton

- [ ] Escribir kernels custom en Triton
- [ ] Empezar por un kernel de atención fusionada propio, sin copiar el de Flash Attention todavía

## Flash Attention

- [ ] Entender por qué el cuello de botella es el manejo de memoria y no el cómputo puro
- [ ] Tiling, cómo evita materializar la matriz de atención completa en memoria
- [ ] Recomputation en el backward pass, trade-off memoria vs cómputo otra vez

## Paralelismo distribuido

- [ ] PyTorch DDP primero. Replicación completa del modelo, all-reduce de gradientes
- [ ] FSDP después. Sharding de parámetros, optimizer states y gradientes
- [ ] Una vez cómodo con FSDP, paralelismo de tensores y de pipeline, mirando Megatron-LM y torchtitan (repo de entrenamiento distribuido de Meta) como referencias reales

## Conexión con performance engineering

Todo lo de esta fase es la base técnica directa de [[Performance engineering para modelos biomoleculares]], la identidad profesional que une GPU/ML infra con drug discovery.

## Mis notas

[[Notas - Fase 6]]

## Navegación

← [[Fase 5 - C++ y CUDA]] | → [[Fase 7 - Escalar con hardware]]

#fase-6
