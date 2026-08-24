---
title: Fase 4 - Arquitectura de computadoras (Onur Mutlu)
tags: [roadmap, llm, arquitectura, en-progreso]
aliases: [Onur Mutlu - Computer Architecture, Onur Mutlu]
fase: 4
status: en progreso, curso sin terminar
---

# Fase 4. Arquitectura de computadoras (Onur Mutlu)

> [!warning] Estado actual
> En progreso. Curso de ETH Zürich, Digital Design and Computer Architecture (227-0003-10L), con Harris & Harris como texto base. No es requisito para las Fases 0 a 3, pero sí es la base conceptual real de la Fase 5 en adelante.

## Por qué esta fase existe como fase propia

Un GPT chico (Fases 0 a 3) no necesita saber cómo funciona una cache. Un kernel CUDA optimizado sí. La jerarquía de memoria y el pipelining explican por qué un acceso a memoria coalescente es rápido y uno disperso es lento, por qué el ocupancy importa, y por qué latency hiding es la estrategia central de una GPU. Sin esto, la Fase 5 y la Fase 6 se estudian de memoria en vez de entenderse.

## Fundamentos

- [ ] Ley de Moore y sus límites actuales (dark silicon, fin del Dennard scaling)
- [ ] Niveles de abstracción en el diseño de una computadora, de transistor a software

## Diseño de ISA

- [ ] RISC vs CISC, trade-offs de cada filosofía
- [ ] Encoding de instrucciones y modos de direccionamiento

## Pipelining

- [ ] Etapas clásicas: fetch, decode, execute, memory, writeback
- [ ] Hazards estructurales, de datos y de control
- [ ] Forwarding y stalling como soluciones a hazards de datos

## Out-of-order execution

- [ ] Algoritmo de Tomasulo
- [ ] Reservation stations, register renaming, reorder buffer

## Branch prediction

- [ ] Predictores estáticos vs dinámicos
- [ ] Branch target buffer, tabla de historia de saltos

## Jerarquía de memoria

- [ ] Principio de localidad temporal y espacial
- [ ] Niveles de cache L1, L2, L3, por qué existen múltiples niveles
- [ ] Políticas de reemplazo (LRU y variantes)
- [ ] Write-through vs write-back

## Memory controllers y DRAM

- [ ] Organización en bancos, filas y columnas
- [ ] Row buffer, por qué un acceso a la misma fila es mucho más barato
- [ ] Timing constraints (tRCD, tCAS, tRP) a nivel conceptual
- [ ] Refresh, por qué la DRAM necesita reescribirse periódicamente

## Multicore y coherencia de caché

- [ ] Protocolo MESI
- [ ] Snooping vs directory-based coherence

## Notas de clase individuales

- [[Pipelining - hazards y forwarding]]
- [[Out-of-order execution - Tomasulo]]
- [[Jerarquia de memoria - caches]]
- [[DRAM - fundamentos]]

> [!success] Hito de la fase
> Poder explicar, sin mirar apuntes, por qué un acceso a memoria coalescente en CUDA es rápido y uno con stride disperso es lento, en términos de row buffer y jerarquía de memoria.

## Mis notas

[[Notas - Fase 4]]

## Navegación

← [[Fase 3 - Entrenamiento y optimizacion numerica]] | → [[Fase 5 - C++ y CUDA]]

#fase-4 #onur-mutlu
