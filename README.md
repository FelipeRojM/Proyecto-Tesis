# Proyecto-Tesis
# Diseño de un Convertidor de Potencia para Fines Educacionales

![Altium Designer](https://img.shields.io/badge/Altium_Designer-A5CD39?style=for-the-badge&logo=altium&logoColor=white)
![Hardware](https://img.shields.io/badge/Hardware-PCB-blue?style=for-the-badge)
![Estado](https://img.shields.io/badge/Estado-Finalizado-success?style=for-the-badge)

## 📌 Descripción General
Este repositorio contiene el diseño de hardware (esquemáticos y PCB) de un convertidor de potencia con topología de puente H, desarrollado como proyecto de título de Ingeniería Civil Electrónica. El objetivo principal de este hardware es servir como plataforma educativa para el estudio de modulación PWM y electrónica de potencia en laboratorios universitarios.

*(Inserta aquí un render 3D de tu placa terminada exportado desde Altium. Una buena imagen vale más que mil palabras para un reclutador).*
`![Render 3D de la PCB](ruta/a/tu/imagen/render3d.png)`

## ⚙️ Características Técnicas
* **Software EDA:** Altium Designer
* **Topología:** Puente H
* **Módulos de Potencia:** *(Ej: Integración y ruteo para módulos IGBT tipo Infineon FF300R12KE4 u otros que hayas utilizado).*
* **Propósito:** Uso en entornos de laboratorio (consideraciones de seguridad, puntos de prueba accesibles, etc.).
* **Fabricación:** Diseño optimizado y fabricado exitosamente (Archivos Gerber y NC Drill verificados con PCBWay).

## 📂 Estructura del Repositorio

El proyecto está organizado de la siguiente manera para facilitar su revisión y manufactura:

```text
├── Hardware/               # Archivos fuente de Altium (.PrjPcb, .SchDoc, .PcbDoc)
├── Fabrication/            # Archivos listos para manufactura (Gerbers, NC Drill, Pick & Place)
├── Docs/                   # Documentación técnica, esquemáticos en formato PDF y reportes
├── BOM/                    # Lista de Materiales (Bill of Materials) en formato CSV/Excel
└── README.md               # Este documento