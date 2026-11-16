# COOTRANSORIENTE TAYRONA
## Proyecto de Arquitectura Empresarial de TI y Transformación Digital

**Institución:** Universidad Cooperativa de Colombia  
**Programa:** Ingeniería de Software  
**Asignatura:** Electiva II – Arquitectura Empresarial de TI  
**Periodo académico:** 2026-2  
**Estado:** En desarrollo

---

# 1. Descripción general del proyecto

Cootransoriente Tayrona es una cooperativa de transporte público intermunicipal que opera principalmente en la ruta Santa Marta–Palomino, a través de la Troncal del Caribe.

Actualmente, la empresa presenta dificultades relacionadas con los procesos manuales de venta de tiquetes, registro de pasajeros, despacho de vehículos, control del recaudo y seguimiento de los pasajeros durante los recorridos.

Estas situaciones generan demoras en la atención, dificultades para controlar los ingresos, falta de información en tiempo real y riesgos relacionados con el cumplimiento de los requisitos de transporte.

Por esta razón, el proyecto propone desarrollar una transformación digital mediante una solución tecnológica integrada que permita centralizar la información, mejorar los procesos operativos y fortalecer el control administrativo y financiero de la cooperativa.

# 2. Planteamiento del problema

La operación actual de Cootransoriente Tayrona depende de procedimientos manuales y comunicaciones informales entre los trabajadores.

Entre las principales dificultades identificadas se encuentran:

- Venta de tiquetes físicos y procesos lentos en taquilla.
- Registro manual de los datos de los pasajeros.
- Falta de control sobre el dinero recaudado durante los recorridos.
- Ausencia de información actualizada sobre los vehículos en circulación.
- Dificultades para conocer la disponibilidad de sillas.
- Falta de trazabilidad de los pasajeros.
- Riesgos relacionados con la elaboración y actualización de los manifiestos de pasajeros.

# 3. Objetivo general

Diseñar una propuesta de transformación digital para Cootransoriente Tayrona mediante la aplicación de Arquitectura Empresarial de TI y el desarrollo de una solución de software que permita optimizar los procesos de venta de tiquetes, registro de pasajeros, despacho de vehículos y control del recaudo.

# 4. Objetivos específicos

- Analizar la situación actual de la empresa y sus procesos operativos.
- Identificar los actores involucrados y los riesgos de la transformación digital.
- Diseñar una arquitectura empresarial que responda a las necesidades identificadas.
- Evaluar las alternativas tecnológicas y económicas para implementar la solución.
- Desarrollar un sistema digital para administrar la venta de tiquetes y el despacho de vehículos.
- Establecer mecanismos de seguridad, seguimiento y control de la información.
- Proponer estrategias para facilitar la adopción del nuevo sistema.

# 5. Alcance del proyecto

La transformación digital contempla:

- Digitalización de la venta de tiquetes.
- Registro electrónico de pasajeros.
- Administración y despacho de vehículos.
- Generación de manifiestos digitales.
- Lectura de códigos QR para validar pasajeros.
- Seguimiento y control del recaudo.
- Administración de usuarios y permisos.
- Centralización de la información.
- Implementación de una base de datos.
- Integración de componentes mediante API.
- Pruebas y preparación del despliegue.

# 6. Organización del equipo de trabajo

El proyecto está distribuido entre cuatro integrantes, cada uno con responsabilidades específicas.

## 6.1 Santiago – Riesgos, seguridad y gestión del cambio

**Responsable 1 – Personas y cumplimiento**

**Objetivo del rol:** Identificar a las personas involucradas en la transformación digital, analizar los riesgos del proyecto y establecer estrategias para facilitar la adaptación de los trabajadores al nuevo sistema.

### Actividades

1. Elaborar la matriz de stakeholders con mínimo ocho actores internos y externos.
2. Clasificar los actores según su poder, interés y expectativas.
3. Construir la matriz de poder–interés.
4. Identificar los riesgos principales del proyecto:
   - Resistencia de los conductores al control digital del recaudo.
   - Resistencia de los taquilleros al nuevo proceso de venta.
   - Pérdida o filtración de información de pasajeros.
   - Fallas de conexión durante los recorridos.
   - Pérdida de información o interrupción del sistema.
5. Elaborar la matriz de riesgos con probabilidad, impacto, nivel y medidas de mitigación.
6. Diseñar el plan de gestión del cambio.
7. Proponer estrategias de capacitación para conductores, ayudantes, taquilleros y despachadores.
8. Investigar la aplicación de la Ley 1581 de 2012 sobre protección de datos personales.
9. Proponer avisos de privacidad, autorizaciones y controles de acceso a la información.

### Entregables de Santiago

- Matriz de stakeholders.
- Matriz de poder–interés.
- Matriz de riesgos.
- Plan de gestión del cambio.
- Plan de capacitación.
- Apartado de seguridad y protección de datos personales.

## 6.2 Andrea – Arquitectura de negocio y diagnóstico empresarial

**Responsable 2 – Empresa y procesos**

**Objetivo del rol:** Investigar cómo funciona actualmente Cootransoriente Tayrona, identificar sus problemas operativos y documentar los procesos que necesitan transformarse.

### Actividades

1. Realizar la caracterización de la empresa:
   - Nombre y actividad económica.
   - Sector al que pertenece.
   - Ubicación y entorno.
   - Servicios que ofrece.
   - Funcionamiento de la ruta Santa Marta–Palomino.
2. Coordinar dos entrevistas obligatorias:
   - Una al administrador o gerente.
   - Una a un despachador, taquillero o conductor.
3. Elaborar los guiones y las actas de las entrevistas.
4. Realizar una observación del funcionamiento actual de la empresa.
5. Recopilar fotografías de planillas, tiquetes y formatos utilizados, con autorización.
6. Elaborar el modelo de negocio Canvas con sus nueve bloques.
7. Describir los procesos actuales (AS-IS):
   - Venta de tiquetes.
   - Registro de pasajeros.
   - Despacho de vehículos.
   - Recaudo del dinero.
   - Control de pasajeros en ruta.
8. Identificar las fallas y problemas de cada proceso.
9. Elaborar los diagramas de procesos actuales y propuestos (AS-IS y TO-BE).
10. Establecer la línea base de los indicadores utilizando información real de la empresa.

### Entregables de Andrea

- Caracterización de Cootransoriente Tayrona.
- Dos entrevistas y sus respectivas actas.
- Evidencias de observación.
- Modelo de negocio Canvas.
- Diagramas de procesos AS-IS y TO-BE.
- Diagnóstico empresarial.
- Problema priorizado y línea base.

## 6.3 Lucho – Arquitectura de soluciones y desarrollo del software

**Responsable 3 – Tecnología y producto**

**Objetivo del rol:** Diseñar la solución tecnológica que permitirá resolver los problemas encontrados en la empresa y liderar la construcción del producto software.

### Actividades

1. Definir la solución tecnológica que se implementará.
2. Diseñar la arquitectura objetivo (TO-BE).
3. Seleccionar y justificar un framework de Arquitectura Empresarial, comparándolo con otras dos alternativas.
4. Diseñar las cinco capas de arquitectura:
   - Estrategia.
   - Negocio.
   - Información y datos.
   - Aplicaciones y sistemas de información.
   - Tecnología y servicios tecnológicos.
5. Diseñar las tres capas transversales:
   - Seguridad y cumplimiento.
   - Gobierno de TI.
   - Uso y apropiación.
6. Elaborar el diagrama de arquitectura tecnológica.
7. Diseñar el modelo de datos y las entidades necesarias.
8. Definir las funcionalidades del sistema.
9. Construir el producto software con las siguientes características:
   - Portal web para la venta de tiquetes en taquilla.
   - Módulo de administración y despacho.
   - Aplicación móvil o interfaz para el ayudante o conductor.
   - Registro digital de pasajeros.
   - Generación de manifiestos digitales.
   - Lectura de códigos QR.
   - Registro y seguimiento del recaudo.
10. Implementar autenticación y al menos dos roles de usuario.
11. Configurar la base de datos y las integraciones mediante API.
12. Realizar pruebas y preparar el despliegue del producto.

### Entregables de Lucho

- Framework seleccionado y justificado.
- Arquitectura empresarial TO-BE.
- Diagramas de arquitectura.
- Análisis de brechas AS-IS/TO-BE.
- Modelo de datos.
- Diagramas de componentes y despliegue.
- Producto software funcional.
- Documentación técnica y manual de usuario.

## 6.4 Juancho – Finanzas, adquisición y contratación tecnológica

**Responsable 4 – Costos e inversión**

**Objetivo del rol:** Analizar la viabilidad económica de la transformación digital, determinar cuánto costaría implementar y mantener la solución y establecer las mejores alternativas de adquisición tecnológica.

### Actividades

1. Identificar los recursos tecnológicos necesarios:
   - Equipos móviles para los trabajadores.
   - Lectores de códigos QR o dispositivos compatibles.
   - Servidores o servicios en la nube.
   - Conectividad a internet.
   - Licencias de software.
   - Servicios de mantenimiento y soporte.
2. Comparar las alternativas de adquisición:
   - Build: desarrollar la solución.
   - Buy: comprar una solución existente.
   - Rent: arrendar equipos o contratar servicios.
3. Analizar la compra frente al leasing de dispositivos móviles.
4. Solicitar o consultar cotizaciones reales de equipos y servicios.
5. Elaborar una matriz de decisión ponderada con mínimo seis criterios.
6. Calcular el costo total de propiedad (TCO) a 36 meses, comparando mínimo dos alternativas.
7. Diferenciar los costos de inversión (CapEx) y los gastos operativos (OpEx).
8. Elaborar el presupuesto de implementación y operación a 12 meses.
9. Identificar los costos ocultos.
10. Elaborar el acuerdo de nivel de servicio (SLA), incluyendo disponibilidad, tiempos de respuesta, respaldo, recuperación y penalidades.
11. Analizar los riesgos financieros y la dependencia de proveedores.
12. Elaborar el análisis costo-beneficio de la transformación digital.

### Entregables de Juancho

- Matriz de adquisición Build, Buy o Rent.
- Comparación de compra frente a leasing.
- Cotizaciones y fuentes de precios.
- Cálculo del TCO a 36 meses.
- Presupuesto del proyecto.
- Comparación CapEx y OpEx.
- Acuerdo de nivel de servicio (SLA).
- Análisis costo-beneficio.

# 7. Producto software propuesto

El producto software será un sistema integrado de despacho y boletería digital para Cootransoriente Tayrona.

### Módulos principales

| Módulo | Funcionalidad |
|---|---|
| Venta de tiquetes | Registro y venta de pasajes |
| Pasajeros | Registro y consulta de información |
| Despacho | Administración de vehículos y recorridos |
| Manifiestos | Generación de manifiestos digitales |
| Código QR | Validación de tiquetes y pasajeros |
| Recaudo | Registro y seguimiento de ingresos |
| Administración | Gestión de usuarios y permisos |

# 8. Arquitectura empresarial

La propuesta de transformación digital tendrá como referencia los modelos de arquitectura empresarial que seleccione y justifique el equipo.

Se contemplará el análisis de la situación actual (AS-IS), la arquitectura objetivo (TO-BE) y las brechas identificadas entre ambos escenarios.

La arquitectura objetivo deberá integrar los procesos empresariales, los datos, las aplicaciones, la infraestructura tecnológica y los aspectos transversales de seguridad, gobierno de TI y apropiación tecnológica.

# 9. Organización del repositorio

La documentación y el código fuente se organizarán de la siguiente manera:

```text
Proyecto-Cootransoriente/
│
├── README.md
│
├── 01_Santiago_Riesgos_Seguridad/
│   ├── Stakeholders/
│   ├── Poder_Interes/
│   ├── Matriz_Riesgos/
│   ├── Gestion_Cambio/
│   ├── Capacitacion/
│   └── Proteccion_Datos/
│
├── 02_Andrea_Diagnostico_Empresarial/
│   ├── Caracterizacion/
│   ├── Entrevistas/
│   ├── Evidencias/
│   ├── Canvas/
│   ├── Procesos_AS-IS/
│   ├── Procesos_TO-BE/
│   └── Diagnostico_Indicadores/
│
├── 03_Lucho_Arquitectura_Software/
│   ├── Framework/
│   ├── Arquitectura_TO-BE/
│   ├── Diagramas/
│   ├── Modelo_Datos/
│   ├── Backend/
│   ├── Frontend/
│   ├── API/
│   ├── Tests/
│   └── Manual_Usuario/
│
├── 04_Juancho_Finanzas_Adquisicion/
│   ├── Build_Buy_Rent/
│   ├── Cotizaciones/
│   ├── TCO/
│   ├── Presupuesto/
│   ├── CapEx_OpEx/
│   ├── SLA/
│   └── Costo_Beneficio/
│
├── 05_Documentacion_General/
│   ├── Informe_Final/
│   ├── Referencias/
│   └── Anexos/
│
└── 06_Despliegue/
    ├── Docker/
    └── Instrucciones/
```

# 10. Control de versiones y participación

GitHub será utilizado como herramienta de almacenamiento, organización y seguimiento del desarrollo del proyecto.

Cada integrante deberá participar con su propia cuenta y registrar los cambios correspondientes a sus responsabilidades mediante commits.

Los cambios deberán documentarse progresivamente durante el desarrollo, manteniendo un historial verificable de las contribuciones.

# 11. Pruebas y validación

El producto software deberá someterse a pruebas para verificar:

- Registro y autenticación de usuarios.
- Funcionamiento de los roles y permisos.
- Venta y registro de tiquetes.
- Registro de pasajeros.
- Despacho de vehículos.
- Generación de manifiestos.
- Lectura y validación de códigos QR.
- Registro del recaudo.
- Integración con la base de datos.
- Funcionamiento de las API.

# 12. Despliegue

Se documentará el procedimiento necesario para instalar, configurar y ejecutar el producto software.

El proyecto contemplará la preparación del entorno de ejecución, la configuración de servicios y base de datos, y las instrucciones necesarias para reproducir el despliegue.

# 13. Estado de los entregables

Los entregables de cada integrante se incorporarán progresivamente al repositorio. Su estado deberá actualizarse de acuerdo con el avance y la existencia de evidencias verificables.

# 14. Consideraciones sobre la información

La información empresarial, las entrevistas, las fotografías, las cotizaciones y los indicadores deberán contar con fuentes o evidencias verificables.

No se presentarán entrevistas no realizadas, cotizaciones no consultadas ni mediciones estimadas como resultados reales de la empresa.

La información personal de pasajeros y trabajadores deberá manejarse de forma segura y conforme a las disposiciones aplicables de protección de datos.

---

**Proyecto académico de Arquitectura Empresarial de TI**  
**Cootransoriente Tayrona – 2026**


