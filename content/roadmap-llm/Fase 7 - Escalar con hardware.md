---
title: Fase 7 - Escalar con hardware
tags: [roadmap, llm, compute]
fase: 7
---

# Fase 7. Escalar con el hardware que consigas

> [!info] Tamaño realista
> El modelo objetivo tiene que ser realista según el presupuesto, no hace falta competir con GPT-4. Algo entre 100 millones y mil millones de parámetros es alcanzable con acceso a pocas GPUs por unos días.

## Prototipado y debug (gratis)

- [ ] Google Colab y Kaggle, 30 horas semanales gratis de GPU, para prototipos chicos y debug antes de gastar plata

## Alquiler de GPUs por hora

- [ ] Vast.ai o RunPod cuando el prototipo necesita algo más grande. El spot pricing hace mucha diferencia en el costo total

## Acceso a compute vía programas

- [ ] TPU Research Cloud de Google, acceso gratuito a TPUs para proyectos de investigación individuales
- [ ] Créditos de Lambda Labs o Hugging Face
- [ ] Colectivos como EleutherAI, que a veces comparten acceso a compute con gente que aporta código

## Antes de correr el entrenamiento grande

- [ ] Confirmar que el pipeline completo (Fases 1 a 6) corre sin errores en una escala chica primero
- [ ] Calcular el presupuesto de compute usando las leyes de escala de la Fase 3, no elegir el tamaño del modelo a ojo

## Mis notas

[[Notas - Fase 7]]

## Navegación

← [[Fase 6 - Sistemas y performance]] | → [[Fase 8 - Publicar y validar]]

#fase-7
