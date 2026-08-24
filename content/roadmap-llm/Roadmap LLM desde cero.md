---
title: Roadmap LLM desde cero
tags: [moc, roadmap, llm, gpu-infra]
status: activo
---

# Roadmap LLM desde cero

> [!info] Punto de partida
> Pensado desde Python ya sólido, así que se salta la introducción a programación y arranca directo en arquitectura de transformers. La arquitectura de compute entra como fase propia antes de C++ y CUDA, porque es la base conceptual real para esa etapa.

## Fases en orden

- [[Fase 0 - Chequeo de bases]]
- [[Fase 1 - Transformer desde cero]]
- [[Fase 2 - Tokenizacion y datos]]
- [[Fase 3 - Entrenamiento y optimizacion numerica]]
- [[Fase 4 - Arquitectura de computadoras (Onur Mutlu)]] — en progreso, curso sin terminar
- [[Fase 5 - C++ y CUDA]]
- [[Fase 6 - Sistemas y performance]]
- [[Fase 7 - Escalar con hardware]]
- [[Fase 8 - Publicar y validar]]

## Por qué la Fase 4 va ahí y no en otro lado

El curso de Onur Mutlu no es un requisito para escribir un transformer (Fases 0 a 3 no lo necesitan). Pero sí es la base conceptual de la Fase 5 en adelante. Sin entender jerarquía de memoria, pipelining y cómo se mueve un dato del DRAM al registro, PMPP y CUDA se aprenden de memoria en vez de entenderse. Por eso va justo antes del salto a C++/CUDA, ni antes ni después.

## Conexiones con otras áreas

- [[Fase 4 - Arquitectura de computadoras (Onur Mutlu)]] sostiene conceptualmente la [[Fase 5 - C++ y CUDA]] y la [[Fase 6 - Sistemas y performance]]
- [[ML infra para drug discovery]] es la aplicación concreta de lo aprendido en las fases 6 a 8, mismo stack técnico, distinto dominio de modelo
- [[Performance engineering para modelos biomoleculares]] es la identidad profesional que junta este roadmap con drug discovery

## Estado actual

- [ ] Fase 0 completa
- [ ] Fase 1 completa
- [ ] Fase 2 completa
- [ ] Fase 3 completa
- [ ] Fase 4 en progreso (Onur Mutlu, curso sin terminar)
- [ ] Fase 5 completa
- [ ] Fase 6 completa
- [ ] Fase 7 completa
- [ ] Fase 8 completa

#roadmap #llm #gpu-infra
