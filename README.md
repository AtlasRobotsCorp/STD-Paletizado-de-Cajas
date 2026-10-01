# STD Paletizado de Cajas

Programa estándar de Atlas Robots para una célula de paletizado de cajas con una dársena sobre enfardadora.

Publicado en abierto como parte de nuestro compromiso con la reutilización y la no obsolescencia programada. Cualquiera puede consultarlo, usarlo y adaptarlo.

## Contenido

| Elemento | Dónde está | Formato |
|---|---|---|
| Programa del robot | En este repositorio (archivo .zip) | Backup del robot |
| Programa del PLC | En [Releases](../../releases) → *Estandar PLC v1.0* | Archivo de proyecto TIA Portal (.zap) |

El programa del PLC está en Releases porque supera el tamaño máximo de archivo del repositorio.

## Equipos

- **Robot:** KRC2 ed05
- **PLC:** [CPU Siemens1200]
- **Software:** TIA Portal V17

## Uso

1. Descargar el backup del robot y restaurarlo en la controladora.
2. Descargar el archivo del PLC desde Releases y desarchivarlo con TIA Portal 17 o superior.
3. Adaptar la configuración de la instalación (direcciones IP, formatos de caja y mosaicos de palé) antes de la puesta en marcha.

## Aviso de seguridad

Este código es una base de referencia. Cualquier célula robotizada que lo utilice debe contar con su propia evaluación de riesgos, arquitectura de seguridad y marcado CE conforme a la normativa vigente. Atlas Robots no se responsabiliza del uso de este código fuera de instalaciones suministradas por la empresa.

## Contacto

**Atlas Robots S.L.**
Av. de las Morcilleras 20, 28343 Valdemoro, Madrid
[www.atlas-robots.com](https://www.atlas-robots.com)
