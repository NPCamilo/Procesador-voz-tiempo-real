# Procesador de Efectos de Voz en Tiempo Real

Procesa voz capturada por un micrófono INMP441, aplica efectos (eco, ring modulation)
y reproduce la señal por una bocina mediante un amplificador MAX98357A, controlado
con un ESP32-S3. Parte del procesamiento se valida en PC con Python.

## Hardware
- ESP32-S3 DevKit
- Micrófono I2S INMP441
- Amplificador I2S MAX98357A + bocina
- Potenciómetros / joystick para selección de efectos

## Estructura
- `firmware/` — código del ESP32-S3 (MicroPython)
- `python_dsp/` — prototipado y validación de efectos en PC
- `docs/` — documentación del proyecto
- `assets/` — gráficas y evidencias

## Equipo
- Camilo Ramírez — Hardware + Git
- Ángel Burbano — DSP Firmware
- Mariano Orrego — Python DSP (PC)
- Luis Ospina — Docs + Integración UI

## Presupuesto

| Componente | Precio promedio (COP) | Dónde comprarlo |
|---|---|---|
| ESP32-S3 DevKit N16R8 | $35.000 – $50.000 | Dualtronica (Pereira), Electronilab, Sigma Electrónica |
| Micrófono INMP441 (I2S) | $20.000 – $27.000 | ja-bots.com, Tecnoelite, Sigma Electrónica |
| Amplificador MAX98357A I2S 3W | $17.000 – $25.900 | Dualtronica (Pereira), CVR Electrónica, Electronilab |
| Bocina 4Ω/8Ω 3W | $8.000 – $15.000 | MercadoLibre, tiendas electrónicas |
| Joystick o potenciómetros | $5.000 – $12.000 | MercadoLibre, taller electrónico |
| Protoboard + cables Dupont | $15.000 – $25.000 | Tiendas electrónicas |
| Cable USB-C | $5.000 – $10.000 | Tiendas digitales |
| **Total estimado** | **≈ $105.000 – $165.000** | |

## Uso
Ver `docs/plan_trabajo.pdf` para el plan por fases y `docs/plan_proyecto.pdf` para el
alcance y cronograma del proyecto.
