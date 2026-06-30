# Relevamiento de Requisitos y Sistema Operativo

En esta sección se detallan los requisitos técnicos recomendados para el software seleccionado en nuestro escenario de **Estación de trabajo para ingeniería**, así como la elección y justificación del sistema operativo base.

---

## Tabla Comparativa de Requisitos (Recomendados)

A continuación, se presenta la tabla con los requerimientos óptimos para garantizar el correcto funcionamiento y rendimiento en un entorno profesional:

| Software | Sistema Operativo Compatible | CPU Recomendada | Memoria (RAM) | Almacenamiento Requerido | Placa de Video (GPU) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Autodesk Fusion** | Windows 11 / macOS | 8 núcleos o más (>3 GHz) | 16 GB o más | SSD (8-10 GB libres) | Dedicada (4 GB de VRAM o más) |
| **Proteus Design Suite** | Windows 10 / 11 (64-bit) | Intel Core i5 / Ryzen 5 (>2.5 GHz) | 8 a 16 GB | SSD o HDD (Espacio base) | Compatible con OpenGL 2.0+ |
| **Visual Studio Code** | Windows / Linux / macOS | Multinúcleo (>1.6 GHz) | 4 a 8 GB | < 500 MB libres | No requiere GPU dedicada |
| **Adobe Acrobat Reader** | Windows / macOS | Procesador base (>1.5 GHz) | 2 a 4 GB | Espacio mínimo base | Integrada básica |

---

## Selección del Sistema Operativo

Para la propuesta final de esta estación de ingeniería se ha seleccionado **Windows 11 Pro de 64 bits** como el sistema operativo definitivo.

### Justificación Técnica

* **Compatibilidad Nativa:** El software *Proteus Design Suite* está diseñado específicamente para entornos de Microsoft Windows. Su ejecución en otros sistemas operativos como macOS o Linux requeriría capas de emulación o máquinas virtuales, lo cual degradaría notablemente el rendimiento general del sistema informático.
* **Aprovechamiento del Hardware:** Windows 11 administra de forma eficiente los procesadores con arquitecturas híbridas de múltiples núcleos (esencial para los renderizados de *Autodesk Fusion*) y cuenta con soporte optimizado para las últimas API de tarjetas gráficas dedicadas.
* **Estabilidad Profesional:** Ofrece un entorno maduro y compatible con los controladores oficiales de todos los componentes de hardware elegidos en el presupuesto de la consultora.
