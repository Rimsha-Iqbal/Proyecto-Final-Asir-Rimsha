# PROYECTO FINAL ASIR - Empresa con ERP (Rimsha Iqbal)
## Tabla de contenido

1. [Introducción](introduccion.md)
2. [Objetivos](objetivos.md)
3. [Análisis del Contexto y Estado del Arte](contexto.md)
   - [Análisis del Contexto](contexto.md)
   - [Estado del Arte](estado_arte.md)

## Introducción  
Hoy en día, donde la digitalización de negocios avanza rápidamente, la gestión óptima de los recursos y diversos procesos se ha vuelto esencial para la competitividad. Sin embargo, las aseguradoras requieren tecnologías avanzadas para una gestión empresarial óptima, como la gestión adecuada de clientes, pólizas, reclamaciones y facturación.
Por lo tanto, el proyecto que vamos a desarrollar consiste en la implementación de un sistema ERP Odoo, un sistema modular y flexible que permite añadir múltiples procesos de negocio en un único sistema. La implementación se realizará en Ubuntu Server 24.04 en AWS nos permitirá trabajar remotamente desde cualquier sitio de una manera controlada, segura y escalable
A lo largo del trabajo, analizaremos la situación actual del sector asegurador y la importancia de los ERP para la modernización. También describiremos el proceso de instalación y configuración de Odoo, incluyendo la creación de un sitio web y la selección de los módulos que componen la herramienta para la gestión de una empresa de seguros. Al final compararemos Odoo con otros ERP y explicaremos los beneficios de implementar esta solución y su impacto en la optimización de las operaciones de la Empresa.

  
## Objetivos  
El objetivo principal de este proyecto es la implementación de un sistema ERP basado en Odoo para gestionar las operaciones de una empresa de seguros en un entorno Ubuntu Server 24.04 alojado en AWS. Donde vamos a Implementar un servidor Ubuntu en una instancia EC2 de AWS, Instalar y configurar Odoo 18 como sistema ERP, Configurar PostgreSQL para la gestión de datos de Odoo, Seleccionar y configurar los módulos necesarios para la administración de una empresa de seguros, Crear sitio web de la empresa usando Odoo 18,Garantizar la seguridad y el correcto funcionamiento del ERP, Documentar el proceso de implementación y configuración del sistema y hacer una comparación entre odoo y otros diferentes ERP para explicar por qué es una buena opción para una empresa.  

## Análisis del Contexto  
Las empresas de seguros trabajan con muchas reglas y mucha competencia. Para tener éxito, necesitan ser muy eficientes en cómo manejan a sus clientes, pólizas y reclamaciones. Antes, muchas usaban diferentes programas de software, a veces de manera desorganizada, lo que hacía difícil juntar toda la información y procesos en un solo lugar.
Ahora, la digitalización y la automatización son clave para mejorar su funcionamiento y la experiencia de los asegurados. En este caso un sistema ERP ayuda a gestionar todo desde un solo lugar, haciendo que las operaciones sean más rápidas, organizadas y seguras en un único sistema. Esto reduce costos, mejora la toma de decisiones basada en datos y permite un control total sobre las operaciones de la empresa.

  
## Estado del Arte  
Actualmente, hay muchos tipos de sistemas ERP, tanto gratuitos como de pago. Uno de los más conocidos es Odoo, porque es de tipo open source, flexible y fácil de usar en cualquier tipo de empresa, incluso en aseguradoras. Con Odoo, se pueden agregar herramientas como gestión de clientes (CRM), contratos, facturación y control de accidentes, todo en un solo sistema con módulos.   
Además, como funciona en la nube, Odoo permite manejar información de manera segura y ayuda a que la empresa pueda crecer sin problemas. La tecnología en el sector asegurador sigue avanzando porque las empresas necesitan ser más eficientes y ofrecer un mejor servicio. Gracias a la inteligencia artificial, la automatización de tareas y el análisis de datos, los ERP son cada vez más inteligentes. Esto ayuda a las aseguradoras a tomar mejores decisiones, ser más competitivas y aprovechar mejor la tecnología.

  
# ¿Qué es ERP?

El acrónimo **ERP** (Enterprise Resource Planning), o **software de planificación de recursos empresariales**, se refiere a la asignación de activos corporativos. Un programa ERP ayuda a mejorar las operaciones centrales de las empresas, como gestión monetaria, administración de personal, fabricación y gestión de la cadena de suministro.

Un sistema ERP supervisa varias funciones internas de una empresa, racionalizando las actividades comerciales para aumentar la eficiencia y disminuir los gastos. La información sobre fabricación, adquisiciones, ventas, distribución y gestión se consolida en un solo marco, permitiendo que los procedimientos se administren automáticamente y funcionen de manera óptima.

Los sistemas de planificación empresarial son programas **completos y conectados**, que se pueden usar localmente o en la nube. Se crean para supervisar todas las facetas de una empresa de producción o distribución, y también facilitan la gestión fiscal, la administración del personal, la logística, la fabricación y la contabilidad principal.

ERP ayuda a las empresas a **ver todo claramente**, gestionando producción, envíos y finanzas desde un solo lugar. Funcionan como el **centro principal** de la empresa, unificando equipos e información.

> Las soluciones ERP proporcionan capacidades diversas para todo tipo de negocios, con posibilidad de adaptación personalizada para industrias específicas.

Uno de estos sistemas es **Odoo**, que funciona como un “gran jefe” para una empresa: ayuda con dinero, clientes, ventas, compras, inventario, producción, proyectos, marketing y personal.

---

## ¿Cuáles son los beneficios de usar un sistema ERP?

- **Gestión centralizada**: una sola aplicación en lugar de múltiples sistemas.
- **Reducción de costos**: menos licencias, menos tiempo perdido.
- **Eficiencia**: menos clics, menos tareas repetitivas.
- **Control y análisis**: reportes centralizados para mejor toma de decisiones.

> Desde Odoo, uno de los objetivos es reducir el número de clics y los tiempos improductivos.

---

## ¿Cuáles son las características de un ERP?

- Gestión integral / integración  
- Digital  
- En la nube o en local  
- Automatización de procesos  
- Intuitivo  
- Reportes e informes  
- Centralización  

---

## Comparativa: Odoo vs. SAP vs. Oracle ERP Cloud vs. Microsoft Dynamics 365

Los sistemas ERP permiten gestionar procesos clave (finanzas, ventas, inventario, RRHH, etc.) en una única plataforma. Las soluciones líderes del mercado difieren en enfoque, público objetivo, licenciamiento y funcionalidad.

### Características principales

| ERP                   | Características clave                                                |
|------------------------|----------------------------------------------------------------------|
| **Odoo**              | Modular, open source, intuitivo, asequible, integración flexible     |
| **SAP S/4HANA**       | Integral, orientado a grandes empresas, escalable, por industria      |
| **Oracle ERP Cloud**  | Cloud-native, fuerte en finanzas y automatización, IA integrada       |
| **Microsoft Dynamics 365** | Suite ERP con opciones para pymes y grandes, integración con Microsoft |

---

### Facilidad de uso

- **Odoo**: interfaz moderna, intuitivo incluso para usuarios sin experiencia.
- **SAP S/4HANA**: complejo, curva de aprendizaje alta (a pesar de mejoras como Fiori).
- **Oracle ERP Cloud**: interfaz sólida, pero abrumadora por tantas funciones.
- **Dynamics 365**: interfaz familiar (Windows/Office), amigable y rápida de implementar.

---

### Escalabilidad

- **Odoo**: ideal para pymes y medianas empresas; para grandes entornos requiere ajustes.
- **SAP S/4HANA**: diseñado para escalar globalmente, operaciones complejas.
- **Oracle ERP Cloud**: escalabilidad elástica en la nube.
- **Dynamics 365**: desde pymes hasta grandes corporaciones, especialmente si usan Azure.

---

### Costos

| ERP                   | Modelo de costos                                                        |
|------------------------|------------------------------------------------------------------------|
| **Odoo**              | Versión gratuita (Community), Enterprise asequible por usuario/módulo   |
| **SAP S/4HANA**       | Costoso, requiere gran inversión en licencias y consultoría             |
| **Oracle ERP Cloud**  | Modelo por suscripción, alto coste total si se escalan módulos          |
| **Dynamics 365**      | Coste intermedio, menor TCO que SAP/Oracle, especialmente en Business Central |

---

### Personalización y flexibilidad

- **Odoo**: altamente flexible por su código abierto y modularidad.
- **SAP**: personalizable pero costoso y complejo.
- **Oracle**: personalizaciones posibles, pero promueve prácticas estándar.
- **Dynamics 365**: personalización con low-code y .NET, menos abierto que Odoo.

---

### Arquitectura (Nube vs. Local)

| ERP                   | Opciones de despliegue                     |
|------------------------|-------------------------------------------|
| **Odoo**              | En la nube o local (SaaS o on-premise)     |
| **SAP S/4HANA**       | On-premise, nube o híbrido                 |
| **Oracle ERP Cloud**  | Nube (cloud-native), Oracle Cloud          |
| **Dynamics 365**      | SaaS (Azure), on-premise e híbrido disponibles |

---

### Soporte y ecosistema

- **Odoo**: comunidad activa + soporte empresarial + red de partners.
- **SAP**: soporte premium + red global de consultoras.
- **Oracle**: soporte 24/7, parches y comunidad experta.
- **Dynamics 365**: soporte de Microsoft + comunidad + consultoras (ej. Avanade, Hitachi).

---

### Adaptabilidad a PYMEs y sector asegurador

- **Odoo**: ideal para pymes, adaptable a seguros mediante personalización (caso: Elige Seguro).
- **SAP/Oracle**: orientados a grandes corporativos; productos de nicho no pensados para pymes.
- **Dynamics 365**: adaptable a pymes (Business Central) y sector seguros (aceleradores específicos).

