---
title: ML infra para drug discovery
tags: [drug-discovery, ml-infra]
---

# ML infra para drug discovery

Aplicación concreta de todo el recorrido de [[Roadmap LLM desde cero]] a modelos biomoleculares en vez de modelos de lenguaje. La infraestructura (kernels custom, paralelismo distribuido, optimización de memoria) es la misma, cambia el dominio del modelo.

## Dónde se conecta con el roadmap LLM

- [[Fase 6 - Sistemas y performance]] es la base técnica directa. Los mismos kernels de atención fusionada que se optimizan para transformers de texto son los que después se adaptan a [[Triangle attention kernels]] en modelos de estructura de proteínas
- [[Fase 4 - Arquitectura de computadoras (Onur Mutlu)]] y [[Fase 5 - C++ y CUDA]] son igual de necesarias acá, no cambian por tratarse de biomoléculas en vez de texto

## Identidad profesional

Este nodo une el [[Roadmap LLM desde cero]] con [[Fase 4 - Arquitectura de computadoras (Onur Mutlu)]] del lado de fundamentos de arquitectura, apuntando hacia [[Performance engineering para modelos biomoleculares]].

#drug-discovery #ml-infra
