# PluvioRed

## Capstone Intermedio 2026

**Equipo:** GeoAlerta  
**Desafío:** Gestión del Riesgo: Monitoreo de Aluviones[cite: 4]  
**Contraparte:** SERNAGEOMIN, SENAPRED RM y Municipalidad de San José de Maipo[cite: 4]  
**Estado actual:** En desarrollo

![Foto del equipo](imagenes/S01/foto-equipo.jpg)

## Descripción

El proyecto aborda la actual brecha preventiva en el monitoreo de aluviones en la comuna de San José de Maipo[cite: 4]. Actualmente, la recolección de datos depende de observadores locales y pluviómetros artesanales que operan de forma 100% manual[cite: 4]. Desarrollaremos una solución para automatizar y centralizar este registro en zonas de conectividad limitada, beneficiando a la comunidad expuesta y a las instituciones de emergencia[cite: 4].

## Equipo

| Integrante | Carrera o especialidad | Rol inicial | Usuario de GitHub |
|---|---|---|---|
| Víctor Manquelipe | Ingeniería Civil Electrónica | Apoyo en Plataforma / Hardware | [@usuario_victor] |
| Constanza Constenla | Ingeniería Civil Industrial | Visita a Terreno / Procesos | [@usuario_constanza] |
| Martín Fariña | Ingeniería Civil en Computación e Informática | Creación de Aplicación / Software | [@usuario_martin] |

## Valores del equipo

- Adaptabilidad
- Proactividad
- Colaboración
- Compromiso social

## Normas de funcionamiento

1. Cumplir estrictamente con los plazos establecidos para el desarrollo y entrega de los avances del prototipo.
2. Mantener una comunicación activa, transparente y respetuosa, donde toda idea u opinión sea escuchada.
3. Dividir la carga de trabajo de manera equitativa y comunicar de inmediato si existe algún bloqueo o problema técnico.
4. **Cómo resolveremos desacuerdos:** Toda decisión técnica o de diseño se someterá a debate priorizando el bajo costo y la escalabilidad; de no haber consenso, se definirá por votación de mayoría simple.
5. **Cómo registraremos las decisiones:** Las decisiones clave se documentarán en la sección de "Acuerdos y tareas" de las bitácoras en GitHub, especificando responsable y fecha.

## Desafío inicial

Nuestro desafío es desarrollar una alternativa de bajo costo que automatice el monitoreo comunitario de aluviones. Sabemos que San José de Maipo tiene 105 quebradas susceptibles y 50 de ellas con población expuesta[cite: 4]. Sabemos que hoy el monitoreo es manual y disperso[cite: 4]. Todavía no sabemos cómo garantizar una transmisión de datos fluida bajo nula conectividad, ni qué sensores específicos resistirán el clima precordillerano. Nuestro principal supuesto a comprobar es que una aplicación móvil offline será adoptada fácilmente por la red de observadores sin volverse una carga extra.

## Objetivo SMART del equipo

Nosotros, como equipo de este Proyecto Capstone, nos comprometemos a desarrollar y probar un prototipo de pluviómetro inteligente de bajo costo y una interfaz móvil para el monitoreo de aluviones en San José de Maipo. Validaremos el sistema demostrando su capacidad para registrar datos instrumentales y reportes ciudadanos bajo condiciones de conectividad limitada, con el objetivo de tener el modelo operativo completamente funcional en un plazo de 4 semanas.

## Compromisos individuales

| Integrante | Compromiso SMART |
|---|---|
| Víctor Manquelipe | Evaluar y configurar los sensores de precipitación y temperatura de bajo costo, registrando al menos dos pruebas de funcionamiento físico antes del 20 de septiembre. |
| Constanza Constenla | Diseñar el flujo de levantamiento de información y testear el registro manual validándolo con al menos 5 pruebas de usabilidad antes del 20 de septiembre. |
| Martín Fariña | Programar la lógica de almacenamiento offline de la aplicación, comprobando una simulación de retención de datos sin red y sincronización antes del 25 de septiembre. |

## Usuarios y contexto

El problema ocurre en la comuna de San José de Maipo, una zona cordillerana con geografía expuesta a remociones en masa[cite: 4]. Los afectados directos son los habitantes de los sectores expuestos en quebradas críticas y la red de observadores voluntarios[cite: 4]. La evidencia actual (catastro de SERNAGEOMIN) muestra que un monitoreo 100% manual y sin automatización genera un riesgo inminente por el retraso en las alertas tempranas[cite: 4].

## Plan inicial

| Actividad | Responsable(s) | Fecha | Estado |
|---|---|---|---|
| Cotizar y adquirir microcontroladores y sensores | Víctor Manquelipe | 05-09-2026 | Pendiente |
| Diseñar wireframes (bocetos) de la interfaz móvil | Martín Fariña | 10-09-2026 | Pendiente |
| Coordinar logística para visita a terreno | Constanza Constenla | 08-09-2026 | Pendiente |

## Índice de la bitácora

- [S01 - Identidad del equipo y desafío](bitacora/S01.md)
- [S02 - Levantamiento inicial](bitacora/S02.md)
- [S03 - Empatizar](bitacora/S03.md)

## Evidencias principales

- [Mapa de susceptibilidad de Flujos de Detritos en San José de Maipo (Plataforma SIGMA)]
- [Registro fotográfico de la red de pluviómetros artesanales actuales]

## Decisiones relevantes

| Fecha | Decisión | Evidencia o criterio utilizado |
|---|---|---|
| 31-08-2026 | Enfoque "Offline-First" para la app. | Restricciones de conectividad confirmadas por SERNAGEOMIN[cite: 4]. |
| 31-08-2026 | Distribución de roles técnicos. | Perfiles académicos de los integrantes. |

## Próximo hito

El equipo debe lograr definir la arquitectura de hardware/software del prototipo y realizar la primera inmersión en terreno. Comprobaremos que se consiguió al presentar un diagrama de flujo validado y el listado de componentes electrónicos adquiridos.

## Uso y licencia

Por definir con el equipo docente y la contraparte. No reutilizar ni publicar información reservada sin autorización.
