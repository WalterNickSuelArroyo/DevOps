# Seccion 1: Antes de empezar (las bases)
## 1. Desarrollo y operaciones, como funciona IT en las empresas antes de DevOps
**Estructura de los departamentos de tecnologia:**

Equipo de desarrollo: Se construye el producto

**Problemas:**
- Aislamiento de equipos
- Friccion entre los equipos
- Uso de correo sobre comunicacion agil
- Baja automatizacion

Infraestructura u operaciones: Manejan los servidores, administran las aplicaciones haciendo lo posible para que estas no se caigan

**Problemas:**
- Script rudimentarios
- Calendarios de releases fijos
- Puesta en produccion mas lenta

## 2. Aprendizaje Recomendado
1. Ver el video
2. Practicar
3. Prueba y compara
4. Depurar el codigo
5. Investigar

## 3. ¿Que es DevOps, Cual es su ciclo de vida y que beneficios aporta?

**DevOps:** (Development + Operation)

Es la union de personas, procesos y tecnologia, con el fin de proporcionar valor continuamente a los clientes. 

Es una metodologia o enfoque que combina el desarrollo de software y las operaciones de TI con el objetivo de acelerar la entrega de software de alta calidad. La idea principal detras de DevOps es promover la colaboracion estrecha y la integracion continua entre los equipos de desarrollo de software y operaciones de TI para lograr una entrega mas rapida y eficiente de aplicaciones y servicios.

**DevOps Cycle:**

- Plan (Planificación): En esta etapa, se definen los objetivos y requisitos del proyecto. Se planifican las tareas, se asignan recursos y se establece una estrategia de desarrollo y entrega.

- Code (Codificación): Los desarrolladores escriben y revisan el código fuente de las aplicaciones. Se siguen prácticas de desarrollo colaborativo y se utilizan sistemas de control de versiones para gestionar el código.

- Build (Construcción): Durante esta etapa, se compila el código fuente en un artefacto ejecutable o en un paquete que se puede desplegar. Esto puede incluir la construcción de aplicaciones, la compilación de código y la generación de ejecutables.

- Test (Pruebas): Se realizan pruebas automatizadas y manuales para verificar que el software funcione correctamente y cumpla con los requisitos. Las pruebas pueden incluir pruebas unitarias, de integración, de rendimiento, de seguridad, entre otras.

- Release (Liberación): En esta etapa, se prepara el software para su liberación en entornos de preproducción y producción. Se asegura que la versión esté lista y se documenta adecuadamente.

- Deploy (Implementación): La implementación es el proceso de desplegar el software en un entorno de producción o preproducción. Se puede hacer de manera automatizada o semiautomatizada para garantizar una entrega rápida y confiable.

- Operate (Operaciones): Después de la implementación, las operaciones de TI mantienen y administran la infraestructura y las aplicaciones en producción. Esto incluye la gestión de servidores, bases de datos y la resolución de problemas.

- Monitor (Monitoreo): Se monitorean constantemente las aplicaciones y la infraestructura en producción para detectar problemas, garantizar el rendimiento y la disponibilidad, y recopilar datos para su análisis. Esto permite una respuesta rápida a eventos inesperados.

**Beneficios o ventajas de DevOps:**
- Mejores objetivos comerciales
- Mayor satisfaccion del cliente
- Agilidad en las entregas y Alto rendimiento
- Mejores productos
- Armonia entre los equipos
- Menos problemas en produccion
- Facilidad en el diagnostico y la resolucion de incidentes

## 4. Aspectos claves de DevOps

**Aspectos fundamentales de DevOps:**
1. Control de versiones

**Qué es:** El control de versiones es el proceso de gestionar y rastrear cambios en el código fuente y otros recursos digitales a lo largo del tiempo. Permite llevar un registro de quién hizo qué cambio, cuándo se hizo y por qué se hizo.

**Importancia en DevOps:** El control de versiones es esencial en DevOps para garantizar la colaboración efectiva entre los miembros del equipo de desarrollo y operaciones. Facilita la gestión de cambios, la corrección de errores y la integración continua al proporcionar un historial completo de los cambios en el código.

2. integración continua

**Qué es:** La integración continua (CI) es una práctica en la que los cambios de código se integran automáticamente en un repositorio compartido varias veces al día. Cada integración se verifica mediante pruebas automatizadas para detectar problemas de manera temprana.

**Importancia en DevOps:** La CI garantiza que los cambios se prueben y validen rápidamente, lo que reduce la posibilidad de errores en etapas posteriores del ciclo de desarrollo. Fomenta la colaboración y la entrega constante de software de alta calidad.

3. Entrega continua

**Qué es:** La entrega continua (CD) es una extensión de la CI y se refiere a la práctica de automatizar la entrega de software a entornos de prueba o producción de manera confiable y eficiente.

**Importancia en DevOps:** La CD permite una entrega rápida y confiable de software. Los cambios que pasan las pruebas de CI se despliegan automáticamente en los entornos adecuados, lo que acelera la implementación y reduce el riesgo de errores humanos.

4. Infraestructura como modigo

**Qué es:** IaC es una práctica en la que la infraestructura de TI se define y gestiona mediante código, generalmente en forma de scripts o archivos de configuración. Esto permite la creación y gestión automatizada de entornos de infraestructura.

**Importancia en DevOps:** IaC facilita la creación y gestión consistente de entornos, lo que es fundamental para lograr la reproducibilidad y escalabilidad en DevOps. Permite la automatización de la configuración de servidores y recursos de infraestructura.

5. Supervision y registro

**Qué es:** La supervisión implica el monitoreo constante de aplicaciones y sistemas en producción para detectar problemas y recopilar datos de rendimiento. El registro implica el almacenamiento de registros de eventos y actividades.

**Importancia en DevOps:** La supervisión y el registro son críticos para mantener la disponibilidad y el rendimiento de las aplicaciones en producción. Ayudan a identificar problemas de manera proactiva y a realizar análisis de datos para tomar decisiones informadas.

6. Aprendizaje validado

**Qué es:** El aprendizaje validado se refiere a la práctica de recopilar datos y retroalimentación de usuarios para validar hipótesis y tomar decisiones basadas en evidencia.

**Importancia en DevOps:** El aprendizaje validado fomenta una mentalidad orientada a los datos y la mejora continua en DevOps. Permite tomar decisiones informadas sobre mejoras en el software y los procesos, lo que lleva a una entrega más eficiente y de mayor calidad.

## 5. La estructura del curso y los objetivos

**Desarrollo:**

- Git flow: Git Flow es un modelo de ramificación y flujo de trabajo que se utiliza con el sistema de control de versiones Git. Fue propuesto por Vincent Driessen y es ampliamente adoptado para gestionar el desarrollo y la entrega de software de manera organizada. En Git Flow, se definen dos ramas principales: master (rama principal) y develop (rama de desarrollo).
- Github- GitLab: GitHub y GitLab son plataformas de gestión de código fuente basadas en Git que permiten a los equipos de desarrollo colaborar, alojar y gestionar proyectos de software. Ambas ofrecen funcionalidades como repositorios, seguimiento de problemas, colaboración, integración continua y más.
- Microservicios: Los microservicios son un enfoque de arquitectura de software en el que una aplicación se divide en múltiples componentes o servicios independientes y autónomos. Cada uno de estos componentes, llamados microservicios, se enfoca en realizar una tarea o función específica dentro de la aplicación. Estos microservicios son pequeñas unidades de software que operan de manera independiente y se comunican entre sí a través de interfaces bien definidas.
- Pruebas unitarias: Las pruebas unitarias son pruebas automatizadas que se centran en comprobar el funcionamiento de unidades individuales de código, como funciones o métodos, de manera aislada. El objetivo de las pruebas unitarias es identificar y corregir errores en pequeñas unidades de código antes de que se integren en el sistema completo.

**Operaciones:**

- Docker: Docker es una plataforma de contenedorización que permite empaquetar aplicaciones y sus dependencias en contenedores ligeros y portátiles. Los contenedores Docker permiten que las aplicaciones se ejecuten de manera consistente en diferentes entornos, desde el desarrollo hasta la producción, lo que facilita la implementación y el escalado.
- Kubernetes: Kubernetes, a menudo abreviado como K8s, es una plataforma de orquestación de contenedores de código abierto que se utiliza para automatizar la implementación, el escalado y la gestión de aplicaciones en contenedores.
- Prometheus: Prometheus es una herramienta de monitoreo y alerta de código abierto diseñada para recopilar métricas y datos de rendimiento de sistemas, aplicaciones y servicios. Permite supervisar el estado y el rendimiento de los componentes de una aplicación en tiempo real y almacenar los datos recopilados para su análisis y generación de alertas.
- Grafana: Grafana es una plataforma de visualización y análisis de datos de código abierto que se utiliza para crear paneles de control y gráficos interactivos a partir de datos de métricas y registros. Se integra con diversas fuentes de datos, incluyendo Prometheus, bases de datos, servicios en la nube y más.

**Pipelines Jenkins:** Jenkins es una herramienta de código abierto ampliamente utilizada para la automatización de procesos de construcción, pruebas y despliegue de aplicaciones. Es especialmente valiosa en DevOps para habilitar la integración continua (CI) y la entrega continua (CD). Imagina que tienes un proyecto de desarrollo de software y deseas que cada vez que se realice un cambio en el código, se construya automáticamente, se pruebe y, si las pruebas son exitosas, se implemente en un servidor de pruebas. Puedes configurar una pipeline de Jenkins para que esto suceda de manera automatizada cada vez que se realice una nueva confirmación de código en tu repositorio.

**Slack:** Slack es una plataforma de comunicación empresarial que se utiliza para la colaboración y la comunicación en equipos y organizaciones. Es especialmente útil en DevOps para mantener a los equipos informados sobre el estado de los proyectos, alertas de sistemas, eventos de CI/CD y otros eventos importantes.


## 6. Invitacion a la comunidad de trabajo colaborativo

# Seccion 2:















