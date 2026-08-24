---
title: Fase 2 - Tokenizacion y datos
tags: [roadmap, llm, datos]
fase: 2
---

# Fase 2. Tokenización y datos

## Byte Pair Encoding desde cero

- [ ] Implementar el algoritmo de merge de pares más frecuentes, sin librerías
- [ ] Seguir minBPE de Karpathy como referencia de implementación
- [ ] Entender por qué GPT-2 y GPT-4 usan splitting por regex antes de aplicar BPE, y qué problema resuelve eso

## Pipeline de datos de preentrenamiento

- [ ] Deduplicación exacta y deduplicación aproximada (MinHash o similar)
- [ ] Filtrado de calidad, heurísticas simples y clasificadores de calidad entrenados
- [ ] Mezcla de dominios (data mixing ratios), qué proporción de cada fuente conviene y por qué no es arbitraria

## Pipelines reales como referencia

- [ ] Estudiar cómo se armó FineWeb (Hugging Face), en particular cómo filtran Common Crawl
- [ ] Estudiar la composición de dominios de The Pile como segundo ejemplo de referencia

> [!success] Hito de la fase
> Tokenizer propio entrenado sobre un corpus real, con vocabulario custom de al menos unos miles de tokens, y un pipeline de limpieza de datos aplicado a un dataset crudo (no uno ya limpio descargado de HF).

## Mis notas

[[Notas - Fase 2]]

## Navegación

← [[Fase 1 - Transformer desde cero]] | → [[Fase 3 - Entrenamiento y optimizacion numerica]]

#fase-2
