# UFlex Woven Bags: contexto y alcance

Proyecto industrial para digitalizar y estructurar información de manufactura en una operación de bolsas tejidas. Organiza registros diarios para que puedan consultarse históricamente y servir como base para análisis y mejora de procesos.

## Estado documentado

Aplicación funcional V1 · en desarrollo desde agosto de 2026. Desde agosto de 2026. Existe una **aplicación funcional V1 en C#/.NET/WPF** y el proyecto continúa en desarrollo. Este repositorio presenta alcance funcional, enfoque de interfaz y contexto del proyecto.

Lehi Salvador — trabajo en estructuración de información operativa, definición de interfaz y desarrollo de la aplicación V1.

Esta documentación amplía la información proporcionada por el responsable del producto. Los criterios y siguientes pasos de la hoja de ruta son propuestas de documentación pública; no compromisos de entrega ni capacidades adicionales implementadas.

## Flujo de referencia

1. Registro diario en tablas.
2. Producción.
3. Desperdicio y su detalle.
4. Tiempos de paro.
5. Consulta histórica.

El flujo describe el contexto del producto. No define una API, integración ni procedimiento productivo listo para ejecutar.

## Vocabulario

| Concepto | Significado en este contexto |
| --- | --- |
| Producción diaria | Registro de producción correspondiente a una fecha operativa. |
| Desperdicio | Registro de material desperdiciado, con detalle que permite interpretarlo. |
| Paro | Tiempo de interrupción registrado para análisis operativo. |
| Trazabilidad histórica | Capacidad de consultar registros y su contexto a lo largo del tiempo. |
| Tabla operativa | Interfaz sencilla de captura y consulta, semejante a Excel. |

## Límites de publicación

- Existe una aplicación funcional V1 en C#/.NET/WPF; este repositorio contiene su presentación pública.
- No se publican registros, capacidades de planta, nombres de operadores ni fórmulas empresariales.
- Unidades, catálogos, causas de paro y reglas de corrección requieren definición con el responsable operativo; no se asumen aquí.

Los sistemas reales y su infraestructura se administran por separado. Este repositorio no contiene instrucciones para acceder a clientes o desplegar aplicaciones.

## Siguiente lectura

[Criterios y hoja de ruta pública](roadmap.md) · [Presentación principal](../README.md)
