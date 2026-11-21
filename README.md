# Diseño de Sistema de Transmisión para Elevador de Cangilones

> **Enfoque:** Mecánica Aplicada / Diseño Mecatrónico / CAD y Simulación[cite: 7]  
> **Contexto:** Proyecto desarrollado en equipo en el marco de mi formación en Ingeniería Mecatrónica (Diseño Mecatrónico I — ITM, Medellín, Colombia)[cite: 7].  
> **Mi rol:** Modelado CAD y simulación del sistema de transmisión (junto con los compañeros de equipo Kevin Stiven Leal González, Jahn Carlos Meneses Tamayo y Felipe Hernández Ramos)[cite: 7, 20, 22, 26].

## 📌 Resumen del proyecto
Diseño mecánico de un sistema de transmisión de potencia en dos etapas para un elevador de cangilones impulsado por un motor de **24 HP a 3400 rpm**, reduciendo la velocidad de salida a **1150 rpm**[cite: 7, 10, 11]. Se combinó una etapa de transmisión por cadena de rodillos y una etapa de engranajes rectos, validando la selección de componentes mediante cálculos analíticos, herramientas de diseño asistido (CAD) y simulación[cite: 7, 11, 20, 22].

## 🎯 Objetivos y alcance
- Diseñar la reducción de velocidad en dos etapas: de **3400 rpm** a un eje paralelo (**2500 rpm** nominales / **2537.31 rpm** reales con dientes seleccionados) mediante cadena, y de **2537.31 rpm** a **1150 rpm** en el eje de salida mediante engranajes[cite: 11, 12, 17].
- Seleccionar y dimensionar elementos de transmisión capaces de soportar cargas de choque moderado asociadas al transporte vertical de material a granel[cite: 10, 12, 13].
- Desarrollar modelos CAD y verificar parámetros operativos y factores de seguridad mediante simulación[cite: 20, 21, 22, 26].
- **Alcance:** Diseño mecánico y modelado/simulación CAD (no incluye fabricación física ni pruebas en planta).

## 🛠️ Arquitectura / Metodología / Herramientas
- **Herramientas y software:** Autodesk Inventor (modelado de piezas, ensambles y *Design Accelerator*), cálculo analítico y hojas de verificación[cite: 20, 22, 26].
- **Metodología:**
  1. **Etapa 1 — Transmisión por cadena:** Cálculo de relación de transmisión, selección de piñones ($Z_1 = 35$, $Z_2 = 47$), factor de servicio ($f_s = 1.4$) para potencia de diseño de **33.6 HP**, determinación de cadena **#40 de 4 hileras** (paso de 0.5 in, 122 eslabones), distancia entre centros y arcos de contacto[cite: 11, 12, 13, 14, 15, 16].
  2. **Etapa 2 — Transmisión por engranajes:** Cálculo de relación de transmisión ($\approx 2.206$), selección de piñón ($Z = 22$) y engranaje ($Z = 49$) con módulo **8 mm**, diámetros primitivos (176 mm y 392 mm), distancia entre centros (284 mm) y torques de entrada (**67.37 Nm**) y salida (**148.61 Nm**).
  3. **Modelado y simulación (labor realizada):** Generación de componentes, verificación de parámetros de diseño, simulación y ensamblaje en CAD[cite: 20, 21, 22, 26].

## 📂 Estructura del repositorio
```text
├── docs/          # Documento técnico del diseño del sistema de transmisión
├── cad/           # Archivos de piezas (.ipt), ensambles (.iam) y Design Accelerator
├── evidence/      # Capturas de simulación y vistas del modelo CAD
└── README.md
