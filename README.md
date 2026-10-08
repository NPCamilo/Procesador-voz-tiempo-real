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

## Uso
Ver `docs/plan_trabajo.pdf` para el plan por fases y `docs/plan_proyecto.pdf` para el
alcance y cronograma del proyecto.
