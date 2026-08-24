---
title: Fase 5 - C++ y CUDA
tags: [roadmap, llm, cuda, cpp]
fase: 5
---

# Fase 5. C++ y CUDA desde cero

> [!info] Requisito conceptual
> Apoyada directamente en [[Fase 4 - Arquitectura de computadoras (Onur Mutlu)]]. Sin esa base, [[Fase 6 - Sistemas y performance]] se estudia de memoria en vez de entenderse.

## C++ moderno

- [ ] Punteros y aritmética de punteros
- [ ] Gestión manual de memoria, new/delete, y el patrón RAII
- [ ] Structs y layout de memoria en disco duro (padding, alineación)
- [ ] Templates básicos
- [ ] Recurso: "A Tour of C++" de Stroustrup, corto y directo al grano, no hace falta el libro completo de mil páginas

## Ejercicios que fuerzan a pensar en memoria

- [ ] Allocator simple escrito desde cero
- [ ] Matriz implementada a mano sin librerías, entendiendo row-major vs column-major y por qué el orden de recorrido importa para el cache

## CUDA, modelo de programación

- [ ] Jerarquía grid, block, thread
- [ ] Tipos de memoria: global, shared, registers, constant
- [ ] Recursos: curso gratuito de Udacity/NVIDIA "Intro to Parallel Programming", CUDA C++ Programming Guide de NVIDIA como referencia permanente

## Ejercicios de CUDA

- [ ] Suma de vectores
- [ ] Multiplicación de matrices
- [ ] Kernel de reducción

Ninguno de estos ejercicios debería tocar nada relacionado a transformers todavía. Esta fase es sobre CUDA puro, no sobre atención.

> [!success] Hito de la fase
> Poder leer un kernel CUDA ajeno y entender qué hace cada línea, sin necesitar ejecutar el código para confirmarlo.

## Mis notas

[[Notas - Fase 5]]

## Navegación

← [[Fase 4 - Arquitectura de computadoras (Onur Mutlu)]] | → [[Fase 6 - Sistemas y performance]]

#fase-5
