---
layout: post
title: Riesgos y Amenazas
date: 2024-05-17 23:21 +0200
author: BorjaAB
category:
- Riesgos y Amenazas
- Slatzer & Schroeder
tags:
- Ingenieria social
- Riesgos
- Amenazas
pin: false
math: true
mermaid: true
---

## Introducción

La diferencia entre amenaza, vulnerabilidad y ataque

: Amenaza &rarr; Aquello que podría hacer uso de una vulnerabilidad con el objetivo de ejecutar esa amenaza.

: Vulnerabilidad &rarr; Punto debil.

: Ataque &rarr; Es el hecho de atacar.

## Ingeniería social

Procedencia de las amenazas &rarr; Ingeniería Social

- **Phising**: Técnica para intentar obtener datos sensibles, a través de una solicitud fraudulenta p.e. en email o en un sitio web, en la que el autor se hace pasar por una empresa legítima o una persona de confianza (variantes: whalling, spear phising, vishing, smishing, chats via pj. telegram, ...)

- **Malware**: Software o firmware destinado a realizar un proceso no autorizado que tendrá un impacto adverso en la confidencialidad, integridad o disponibilidad de un sistema de información.

	- Un virus, gusano, caballo de Troya u otro sw que infecta un host
	- El _spyware_ y algunas formas de adware también ejemplos de código malicioso

- **Ransomware**: Software malicioso diseñado para bloquear el acceso a un sistema informático hasta que se pague una suma de dinero (normalmente crypto monedas)

- **Compromiso del correo electrónico de la empresa** (Business Email Compromise, BEC): atacante obtiene acceso a una cuenta de correo electrónico de la empresa e imita la identidad del propietario &rarr; defraudar a la empresa y a sus empleados, clientes o socios

- **Internet de las cosas** (Internet of Things, IoT): interconexión a través de Internet de dispositivos informáticos integrados en objetos cotidianos, que les permite enviar y recibir datos &rarr; reto!

- **Exploit**: parte de un programa (software), un conjunto de datos o una secuencia de comandos que se aprovecha de un error o una vulnerabilidad para provocar un comportamiento no deseado o imprevisto en el software o hardware

## Slatzer & Schroeder

Principios de diseño de Slatzer & Schroeder

- **Economía de los mecanismos** (Economy of mechanism): kisss
- **Seguro ante fallos por defecto** (Fail-safe defaults): planificación previa, a menos que un sujeto tenga acceso explícito a un objeto, se le debe negar el acceso a dicho objeto
- **Mediación completa** (Complete mediation): comprobaciones de acceso a un objeto cada vez que se solicita el acceso
- **Diseño abierto** (Open design): seguridad de un mecanismo no debe depender del secreto de su diseño o aplicación
- **Separación de privilegios** (Separation of privilege): no conceder permisos basándonos solo en una condición
- **Privilegios mínimos** (Least privilege): los privilegios mínimos necesarios (p.e en permisos de cuentas de usuario como sea posible)
- **Mecanismo menos común** (Least common mechanism): mecanismos utilizados para acceder a los recursos no deben ser
compartidos
- **Interfaz amigable** (User-friendly interface): que los recursos no sean más difíciles de usar por el hecho de aplicar mecanismos de seguridad

## Políticas de seguridad

- **Gobernanza**: Una responsabilidad de planificación estratégica que proporciona una supervisión organizativa que fija las políticas y establece las prácticas para el cumplimiento
- **Cumplimiento**: Los requisitos de todas las partes afectadas siguen las mismas reglas
- **Auditoría**: Una revisión y examen independiente de los registros y actividades para evaluar la adecuación de los controles del sistema, con el fin de garantizar el cumplimiento de las políticas y los procedimientos operativos establecidos
- **Política**: Declaraciones, reglas o afirmaciones que especifican el comportamiento correcto o esperado de una entidad

## Normativa, legislación, estándares aplicados a riesgos

- **ENS** &rarr; Esquema nacional de seguridad
- **Ley** Orgánica 3/2018, de 5 de diciembre, de Protección de Datos Personales y garantía de los derechos digitales
- **RGPD** &rarr; Reglameto general de proteeción de datos (EU)
- Serie **ISO 27000**
	- ISO **27000**:2018, Information technology &rarr; Security techniques &rarr; Information security management systems &rarr; Overview and vocabulary
		- Visión general de los sistemas de gestión de la seguridad de la información (SGSI) y términos y definiciones usados en la familia de normas del SGSI
		- Aplicable a todos los tipos y tamaños de organización
		- Explicación de la importancia de implantar de un SGSI
		- Intro SGSI
		- Descripción de pasos para el establecimiento, monitorización, mantenimiento y mejora de un SGSI
	- ISO/IEC **27001**:2013, Information Security Management System (ISMS) Specification (UNE-EN ISO/IEC 27001:2017)
		- Especifica requisitos para establecer, implementar, mantener y mejorar continuamente un SGSI en el contexto de la organización
		- Requisitos para la evaluación y el tratamiento de los riesgos de seguridad de la información adaptados a las
necesidades de la organización -> certificar los SGSIs de las organizaciones por auditores externos
		- Requisitos genéricos y aplicables a todas las organizaciones, independientemente de su tipo, tamaño o naturaleza

### [ISO/IEC 27001:2013](/assets/img/riesgos_amenazas/Norma UNE-EN ISO-IEC 27001.pdf)

Requisitos a tener en cuenta para el SGSI.

> Si el SGSI es el ```qué```, la ISO 27001 es el ```cómo```.
{: .prompt-info }

#### 5.2 Política

La alta dirección debe establecer una politica de seguridad de la información que:

: a) sea adecuada al propósito de la organización
: b) incluya objetivos
: c) incluya el compromiso de cumplir con los requisitos aplicables a la seguridad de la información e
: d) incluya el comprobmiso de mejora continua del sistema de gestión de la seguridad de la información

La política de seguridad de la información debe:

: e) estar disponisble como información documentada
: f) comunicarse dentro de la organización
: g) estar disponible para las partes interesadas, según sea apropiado

#### 6.2 Los dispositivos móviles y el teletrabajo

Objetivo: Garantizar la seguridad en el teletrabajo y en el uso de dispositivos móviles.

##### 6.2.1 Política de dispositivos móviles
###### Control

Se debe adoptar una política y una medidas de seguridad adecuadas para la protección contra los riesgos de la utilización de dispositivos móviles.

##### 6.2.2 Teletrabajo
###### Control

Se debe implementar una política y unas medidas de seguridad adecuadas para proteger la información accedida, tratada o almacenada en emplazamientos de teletrabajo.

Se debe adoptar una política y una medidas de seguridad adecuadas para la protección contra los riesgos de la utilización de dispositivos móviles.

### [ISO/IEC 27002:2013](/assets/img/riesgos_amenazas/Norma UNE-EN ISO-IEC 27002.pdf)

Nos dice que tener en cuenta para el sistema de gestión de la seguridad de la información con los dominios, categorías y controles.

Establece directrices y requisitos para la gestión de la seguridad de la información.
Seleccionar e implementar controles de seguridad adecuados, de acuerdo con los riesgos que enfrentan.

ISO/IEC 27002:2013, The Code of Practice for information Security Management (UNE-EN ISO/IEC 27002:2017)

: Guía de buenas prácticas describiendo objetivos de control y controles recomendables en cuanto a seguridad de la información

: No es certificable

: Contiene 14 dominios (capítulos de controles), 35 categorías principales de seguridad (cada capítulo una o más categorías) y 114 controles (control+guía+info adicional) &rarr; la implementación de todos los controles no es obligatoria pero argumentar en caso de no implantar

: Anexo en el 27001

#### 6.2 Los dispositivos móviles y el teletrabajo

Objetivo: Garantizar la seguridad en el trabajo y en el uso de dispositivos móviles.

##### 6.2.1 Política de dispositivos móviles
###### Control

Se debería adoptar una política y unas medidas de seguridad educuadas para la protección contra los riesgos de la utilización de dispositivos móviles.

###### Guía de implantación

Cuando se utilicen dispositivos móviles, se debería tener un cuidado especial para asegurar que no se compromete la información del negocio. La política de dispositivos móviles debería tener en cuenta los riesgos de trabajo con dispositivos móviles en entornos desprotegidos.

La política de dispositivos móviles debería considerar.

: a) el registro de dispositivos móviles

: b) los requisitos para la protección física

: c) la restriccioes de instalación de software

: d) los requisitos para las versiones de software de dispositivos móviles y para la aplicación de los parches y actualizaciones del software

: e) las restricciones de conexión a servicios de información

: f) los controles de acceso

: g) las técnicas criptográficas

: h) laprotección ante el software malicioso (malware)

: i) la inhabilitación, el borrado y bloqueo remotos

: j) las copias de respaldo

: k) la utilización de servicios y aplaciones web

Se debería tener cuidado con el uso de dispositivos móviles en zonas públicas, salas de reunión y otras áreas desprotegidas fuera de las instalaciones de la organización. Se debería implantar algún tipo de protección para evitar el acceso no autorizado o la revelación de la información almacenada y procesada por estos dispositivos, por ejemplo, utilizando técnicas criptográficas (véase el capitulo 10) e imponiendo el uso de protocolos secretos de indentificación y autenticación (véase 9.2.4).

Los dispositivos móviles también deberían estar físicamente protegidos contra el robo, especialmente cuando se dejan, por ejemplo, en coches y otras formas de transporte, habitaciones de hoteles, centros de conferencia y lugares de reunión. Se debería establecer un procedimiento específico, que tuviera en cuenta, los requisitos legales, los requisitos de los seguros y otros requisitos de seguridad de la organización, para los casos de robo o pérdida de los dispositivos móviles. Los equipos que contengan información importante, sensible o crítica para el negocio, no se deberían dejar desatendidos y, cuando sea posible, se deberían bloquear físicamente, o se deberían utilizar cierres especiales para proteger el equipo.

Se debería proporcionar formación al personal que utiliza dispositivos móviles para aumentar su concienciación respecto a los riesgos adicionales de esta forma de trabajo y de los controles que se deberían implantar.

Cuando la política de dispositivos móviles permita el uso de dispositivos móviles personales o privados, la política y las medidas de seguridad relacionadas deberían considerar también:

: a) la separación del uso de los dispositivos con fines privados respecto a los del negocio, incluyendo el uso de software para permitir dicha separación y proteger los datos de negocio en un dispositivo personal o privado

: b) proporcionar acceso a la información de la organización sólo después de que los usuarios han firmado un acuerdo de usuario final que incluya el reconocimiento de sus obligaciones (protección física, actualización de software, etc.), con renuncia a la propiedad de los datos de negocio, permitiendo la limpieza remota de los datos por la organización en caso de robo o pérdida del dispositivo o cuando ya no estén autorizados a utilizar el servicio. Esta política debería tener en cuenta la legislación de privacidad

##### Información adicional

Las conexiones de dispositivos móviles a redes inalámbricas son similares a otros tipos de conexión a redes, pero tienen diferencias importantes que deberían tenerse en cuenta cuando se identifican los controles.

Las diferencias típicas son:

: a) algunos protocolos de seguridad inalámbrica son inmaduros y tienen debilidades

: b) de la información almacenada en dispositivos móviles puede que no se haga una copia de respaldo debido a la limitación del ancho de banda o porque el equipo móvil puede no estar conectado en el momento en que se programan las copias de seguridad

Los dispositivos móviles, en general, comparten funciones comunes con los dispositivos de uso fijo como, por ejemplo, redes compartidas, acceso a Internet, correo electrónico y gestión de archivos. Los controles de seguridad de la información para los dispositivos móviles consisten, en general, en aquellos adoptados para los dispositivos de uso fijo y aquellos que hacen frente a las amenazas planteadas por su uso fuera de los locales de la organización.

### ISO/IEC 27005:2018

Propone una forma de llevar a cabo la evaluación de riesgos con el objetivo de minimizar los riesgos basado en la norma 27001 y 27002.

ISO/IEC 27005:2018, **ISMS Risk Management**

: Directrices para la gestión del riesgo en la seguridad de la información
: Apoya los conceptos generales especificados en la norma ISO/IEC 27001
: Ayudar a la aplicación satisfactoria de la seguridad de la información basada en un enfoque de gestión de riesgos
: Ser capaces de identificar, medir, analizar, evaluar, y tratar varios riesgos de seguridad a los que se enfrentan las organizaciones
: Dar soporte a las organizaciones a priorizar riesgos y llevar a cabo acciones para reducir o mitigarlos
: No certificable

> Normativa homóloga en EEUU: ```HIPAA Security and Privacy``` (datos de salud, historia clínica), ```Payment Card Industry Data Security Starndard``` (PCI DSS)
{: .prompt-info }

[Enlaces de Interés](https://www.industriaconectada40.gob.es/difusion/Paginas/enlaces-interes.aspx)

## Marco de ciberseguridad del NIST (NIST Cybersecurity Framework, NIST CSF)

NIST Computer Security Resource Center (CSRC) (USA)

: Estándares, guías, documentos con requisitos técnicos &rarr; privacidad y seguridad de información, dispositivo y cyber

Las guías sp800 del NIST son todos los documentos relaccionados con la ciberseguridad
	- [Directrices para la gestión del riesgo en la seguridad de la información](https://csrc.nist.gov/publications/sp800)

### Introducción

Componentes: marco básico o núcleo (core), el nivel de implementación (implementatio tiers) y los perfiles (profiles)

: Core: Actividades y resultados deseados en materia de ciberseguridad utilizando un lenguaje
común y fácil de entender. Guía a las organizaciones en la gestión y reducción de sus riesgos de ciberseguridad de una manera que complementa los procesos existentes de ciberseguridad y gestión de riesgos de una organización.

: Tiers: Ayudan a las organizaciones proporcionando un contexto sobre cómo una organización ve la gestión de riesgos de ciberseguridad. Los niveles guían a las organizaciones para considerar el nivel apropiado de rigor para su programa de ciberseguridad y se utilizan a menudo como una herramienta de comunicación para discutir el apetito de riesgo, la prioridad de la misión y el presupuesto.

: Profile: Alineación (personalizada, única) de la organización en términos de sus requisitos y objetivos organizativos, su apetito de riesgo y sus recursos según los resultados deseados del Core. Los perfiles se utilizan principalmente para identificar y priorizar las oportunidades de mejora de la ciberseguridad en una organización.

![Desktop View](/assets/img/riesgos_amenazas/wheel_pie.png){: width="200" height="200" }

### Marco de ciberseguridad del NIST: **Marco Básico (Core)**

- Consta de tres partes: **Funciones, Categorías** y Subcategorías

- Seis **funciones** de alto nivel: Governanza, Identificar, Proteger, Detectar, Responder y Recuperar, aplicables a la gestión de riesgos de ciberseguridad y a la gestión de riesgos en general

![Desktop View](/assets/img/riesgos_amenazas/funciones_core.png){: width="300" height="300" }

![Desktop View](/assets/img/riesgos_amenazas/steps_create_profile.png){: width="972" height="589" }

- 22 **categorías** que se reparten entre las seis funciones

![Desktop View](/assets/img/riesgos_amenazas/core_categories.png){: width="972" height="589" }

[Información obtenida del NIST Cybersecurity Framework (CSF) 2.0](https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.pdf)

Las categorías fueron diseñadas para cubir en toda su amplitud los objetivos de ciberseguridad de una organización, sin ser excesivamente detalladas. Abarcan temas relacionados con la ciberseguridad, la seguridad física y el personal, centrándose en los resultados empresarieales.

![Desktop View](/assets/img/riesgos_amenazas/subcategories.png){: width="972" height="589" }
_Solo con motivo de representación, esta desactualizada, para información actual consulte los enlaces de debajo_

[Más información de las subcategorías del NIST Cybersecurity Framework (CSF) 1.1 en la página 31](/assets/img/riesgos_amenazas/NIST.CSWP.04162018es.pdf)

[Hoja de calculo con información de las subcategorías del NIST Cybersecurity Framework (CSF) 2.0](/assets/img/riesgos_amenazas/csf2.xlsx)

[Lo mismo que el enlace anterior pero en la página web de NIST](https://csrc.nist.gov/projects/cybersecurity-framework/filters#/csf/filters)

> La información en la [página web](https://csrc.nist.gov/projects/cybersecurity-framework/filters#/csf/filters) ```TARDA EN CARGAR```.
{: .prompt-danger }

![Desktop View](/assets/img/riesgos_amenazas/tarda_cargar.png){: width="972" height="589" }
_[Subcategorías actualizadas a el NIST CSF 2.0](/assets/img/riesgos_amenazas/info_subcategorias.pdf)_

### Marco de ciberseguridad del NIST: **Niveles de implementación (Tiers)**

- Grado en que las prácticas de gestión de riesgos de ciberseguridad de una organización presentan las caracteríasticas definidas en el Marco Básico (core)

- De Parcial (nivel 1) a Adaptable (nivel 4)

	- Grado creciente de rigor +
	- Grado de integradción de las decisiones sobre riesgos de ciberseguridad en las decisiones más amplias sobre riesgos +
	- Grado en que la organización comparte y recibe información sobre ciberseguridad de partes externas

![Desktop View](/assets/img/riesgos_amenazas/tiers.png){: width="972" height="589" }

Proceso de gestión de riesgos

: La funcionalidad y repetibilidad de la gestión de riesgos de ciberseguridad.

Programa Integrado de Gestión de Riesgos

: El grado de consideración de la ciberseguridad en las decisiones de gestión de riesgos más amplias.

Participación externa

: El grado en que la organización:

	- Controla y gestiona el riesgo de la cadena de suministro.

	- Beneficios de que comparta o reciba información de terceros.

- Se pueden usar para indentificar oportunidades de mejora comparando **perfil actual** con **perfil objetivo** (target)

- Los perfiles consisten en optimizar el marco de ciberseguridad para que sirva mejor a la organización

- Una forma de enfocar los perfiles es mapeando los requisitos de ciberseguridad de la organización, objetivo y metodologías operativas y practicas usando las subcategorías del Núcleo (core) del Marco para crear (Perfil Objetivo)

- Estos requistos y objetivos pueden ser comparados con el estado operatio actual de la organización (Perfil Actual) para obtener una comprensión de las brechas entre ambos

![Desktop View](/assets/img/riesgos_amenazas/roadmap_target_prof.png){: width="972" height="589" }
_Credito a NIST por la [imágen](https://www.nist.gov/cyberframework/cybersecurity-framework-components) - [Image info](https://www.nist.gov/image/roadmaptargetprofpng)_

## CIS (Center for Internet Security)

Tres herramientas:

: **Benchmarks** ([CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks)), guías de configuración / hardering de sistemas operativos, dispositivos, redes, aplicaciones y software

: **Controles** ([CIS Controls](https://www.cisecurity.org/controls)), conjunto de acciones para proteger su organización y sus datos de los vectores de ciberataque conocidos

: **CIS-Cat** ([versión gratuita](https://learn.cisecurity.org/cis-cat-lite) y [versión de pago](https://www.cisecurity.org/cybersecurity-tools/cis-cat-pro)):

	- Automatización del proceso de implementación de configuraciones para sistemas seguros

	- Herramienta de evaluación de configuraciones y pasos para corregirlas y cumplir las recomendaciones de CIS Benchmark

### [CIS Controles V.8](/assets/img/riesgos_amenazas/CIS_Controls_v8_Spanish_ESP_ONLINE_2022_0411.pdf)

[CIS Controles V.8 Vesión Ingles](/assets/img/riesgos_amenazas/CIS_Controls_v8_Critical_Security_Controls_2023_08.pdf)

[Hoja de calculo CIS Controles V.8](/assets/img/riesgos_amenazas/CIS_Controls_Version_8.xlsx)

Tres categorías: básicos (basic), fundacional (foundational) y organitzativos (organizational) y tres grupos de implantación (limitado, moderado, significativo)

Básicos

: 1 - Inventario y control de los activos de hardware

: 2 - Inventario y control de los activos de software

: 3 - Gestión continua de la vulnerabilidad

: 4 - Uso controlado de los privilegios administrativos

: 5 - Configuración segura de hardware y software en dispotivos móviles, portátiles, estaciones de trabajo y servidores

: 6 - Mantenimiento, monitorización y análisis de los registros de auditoría

Fundacionales

: 7 - Protecciones del correo electrónico y del navegador web

: 8 - Defensas contra el malware

: 9 - Limitación y control de puertos, protocolos y servicios de red

: 10 - Capacidades de recuperación de datos

: 11 - Configuración segura para dispositivos de red, como cortafuegos, routers y switches

: 12 - Defensa de límites (Boundary Defense)

: 13 - Protección de datos

: 14 - Control de acceso basado en la necesidad de saber (need to know)

: 15 - Control de acceso inalámbrico

: 16 - Supervisión y control de cuentas

Organizativos

: 17 - Implantar un programa de concienciación y formación en materia de seguridad

: 18 - Seguridad del software de aplicación

: 19 - Respuesta y gestión de incidentes

: 20 - Pruebas de penetración (pentesting) y ejercicios de equipos rojo (red team)

### Ejemplo

Inventario y control de los activos de hardware

: Gestionar activamente (inventaria, rastrear y corregir) todas los dispositivos de hardware de la red, de modo que sólo se dé acceso a los dispositivos autorizados y se localices los no autorizados y no gestionados y se impida su acceso, ¿**por qué** es importante?

	- Atacantes escanean continuamente espacio de direcciones de las organizaciones objetivo, esperando que se conecten a la red sistemas nuevos y posiblemente desprotegidos (p.e., dispositivos que entran y salen de la red de la empresa, "Bring-Your-Own-Devices &rarr; BYOD")

	- Ataques pueden aprovechar el nuevo hardware que se instala en la red un dia pero no se configura ni se parchea con las actualizaciones de seguridad adecuadas hasta el día siguiente

	- Dipositivos no visibles desde Internet pueden ser utilizados por los atacantes que ya han obtenido acceso interno

	- Sistemas adicionales que se conectan al ared de la empresa (p.e., demostradores, sistemas de prueba temporales, redes de invitados) también deben gestionarse cuidadosamente y/o aislarse para evitar que el acceso de los adversarios afecte a la seguridad de las operaciones de la empresa

	- Control gestionado de todos los dispositivos desempeña un papel fundamental en la planificación ejecución de las copias de seguridad del sistema, la respuesta a incidentes y a la recuperación

: ¿**Cómo**?

: Utilizar una herramienta de detección activa para identificar los dispositvos conectados a la red de la organización y actualizar el inventario de activos de hardware

: Mantener un inventario preciso y actualizado de todos los activos tecnolígicos con potencial para almacenar o procesar información

: Inventario deberá incluir todos los activos de hardware, estén o no conectados a la red de la organización

![Desktop View](/assets/img/riesgos_amenazas/CASControl1.png){: width="683" height="585" }
_Inventario y control de los activos de hardware_

: ¿Herramientas? "Discovery tool"

- [Network Inventory Advisor](https://www.network-inventory-advisor.com/es/)

- [Advanced IP Scanner](https://www.advanced-ip-scanner.com/es/)

- [Intermapper](https://www.fortra.com/products/network-monitoring-software)

- [Nagios XI](https://www.nagios.com/products/nagios-xi/)

- [Network Topology Mapper](https://www.solarwinds.com/network-topology-mapper)

- [**Nmap**](https://nmap.org/)

![Desktop View](/assets/img/riesgos_amenazas/nmap_usage.png){: width="972" height="589" }

- [**Scapy**](https://scapy.net/), suite de elaboración, manipulación y análisis de paquetes

	- Falsificar o decodificar paquetes de difirentes protocolos, enviarlos, capturarlos, hacer coincidir peticiones y respuestas, etc.

	- Tareas como escaneao (scanning), tracerouting, sondeo (probing), unit test, ataques o descubrimiento de la red (network discovery) pudiendo sustituir a hping, nmap (no todo), arpspoof, arp.sk, arping, tcpdump, tethereal, p0f, etc.

	- Envío de tramas inválidas, inyección de sus propias tramas 802.11, la combinación de técnicas (VLAN hopping+ARP cache poisoning, decodificación de VOIP en el canal cifrado WEP, ...), etc.

![Desktop View](/assets/img/riesgos_amenazas/scapy.png){: width="972" height="589" }
_[Scapy - Documentación](https://scapy.readthedocs.io/en/latest/index.html)_

## Gestión y análisis de riesgos

Limitaciones en el grado de implementación de acciones de ciberseguridad, ¿por qué?

- Recursos de seguridad limitados (dinero, expertos y tiempo)

- Prioridades empresariales que compiten entre sí

- Amenazas siempre cambiante

Dificultan que las organizaciones puedan aplicar completamente las medidas de seguridad y que apliquen por completo una norma de ciberseguridad.

Y que se aplique por igual a todas las empresas, DIFICIL implementar un estándar de ciberseguridad por igual a todos los activos de información.

Incluso sin esos retos las organizaciones deben operar en entornos "algo" vulnerables para cumplir su misión y alcanzar sus objetivos.

- Por ejemplo, ¿cifrado sí o no? ¿cómo saber si aceptar el riesgo de esos momentos y transacciones cuando la información no está cifrada? ¿Cómo determinar si otras salvaguardass de apoyo protegen adecuadamente la información sin cifrar?

Mediante una **Evaluación de Riesgos**, para responder por nosotros mismos si debemos aceptar o reducir los riesgos.

### Ejemplo Gestión de riesgos (CIS RAM & CIS Controls)

> La guía CIS RAM nos explica como hacer una Gestión de riesgo basada en los CIS Controls.
{: .prompt-info }

En esta sección vamos a hacer un analisis de riesgo siguiendo la guía CIS RAM

Descripción: Los tres conjuntos de instrucciones presentan una organización ficticia que está llevando a cabo una de seguridad de la información, y que mejora sus capacidades de gestión de riesgos a lo largo del tiempo. La organización del ejemplo comienza la evaluación de riesgos en el primer conjunto de instrucciones, con poca participación de la dirección de la empresa. Después de un año de mejorar su postura y habilidades de seguridad, evalúan el riesgo en el segundo conjunto de instrucciones utilizando un razonamiento y métodos más refinados, y en colaboración con la dirección de la empresa. Finalmente, maduran lo suficiente como organización capaz de asumir un análisis de riesgos complejo en el tercer conjunto de instrucciones.

- La organización de ejemplo descrita en este **documento fabrica y presta servicios a dispositivos médicos** ("dispositivos de diario") **que leen información biológica de los pacientes que llevan los dispositivos**. La organización trabaja en entornos clínicos para dar soporte a los pacientes, así como a los dispositivos, y como resultado mantiene información sanitaria privada sobre los pacientes. Como trabajan con organizaciones militares y de veteranos, muchos de sus pacientes son miembros activos o antiguos de las fuerzas armadas. Como resultado, la organización plantea un riesgo mayor y requiere un mayor escrutinio sobre sus controles de ciberseguridad.

El análisis de riesgos se ha descrito comúnmente como **Riesgo = Impaco x Probabilidad**

La regla "hand rule" ("Learned Hand Rule" aka "the Calculus of Negligence"): la carga (B, Burden) para prevenir el daño no debe ser mayor que la probabilidad (P, probability) de que se produzca el daño multiplicada por la responsabilidad (L, liability) después de un evento dañino **B <= P x L**

**Principios**

- El análisis de riesgos debe tener en cuenta los intereses de todas las partes que puedan verse perjudicadas por el riesgo
- Los riesgos deben reducirse a un nivel que las autoridades y las partes potencialmente afectadas consideren apropiado
- **3. Las garantías no deben ser más gravosas que los riesgos contra los que protegen**

**Prácticas**

1. Análisis de riesgos considera la probabilidad de que ciertas amenazas puedan crear magnitudes de impacto.g
2. Los riesgos y las salvaguardias se evalúan con los mismos criterios para poder compararlos.
3. Puntuaciones de impacto y probabilidad tienen un componente cualitativo que expone de forma concisa las preocupaciones de las partes interesadas, las autoridades y la organización evaluadora.
4. Puntuaciones de impacto y probabilidad se obtienen mediante cálculo numérico que permite comparar entre todos los riesgos evaluados, las salvaguardias y contra los criterios de aceptación del riesgo.
5. Definiciones de impacto garantizan que la magnitud del daño a una parte se equipare con la magnitud del daño a otros.
6. Definiciones de impacto deben tener un límite explícito entre las magnitudes que serían aceptables para todas las partes y las que no lo serían.
7. Definiciones de impacto abordan: la misión o la utilidad de la organización para explicar por qué la organización y los demás se involucran en el riesgo, los objetivos de interés propio de la organización y las obligaciones de la organización de proteger a los demás de los daños.
8. Análisis de riesgos se basa en un estándar de atención para analizar los controles actuales y las salvaguardias recomendadas.
9. El riesgo es analizado por expertos en la materia que utilizan pruebas para evaluar los riesgos y las salvaguardias.
10. Evaluaciones de riesgos no pueden evaluar todos los riesgos previsibles; Las evaluaciones de riesgos se repiten para identificar y abordar más riesgos a lo largo del tiempo.

**Analiza el riesgo observado**

: Definir el alcance: Identificar los activos de información que se están evaluando, así como los propietarios y administradores de los activos de información
: Programar las sesiones: Programar las entrevistas y las sesiones de revisión de pruebas
: **Desarrollar la evaluación de riesgos y los criterios de aceptación: Establecer y definir los criterios para evaluar y aceptar el riesgo**
: Reunir las pruebas: Entrevistar al personal, revisar los documentos y observar las salvaguardas
: Modelar los riesgos: Evaluar las salvaguardas actuales que podrían prevenir o detectar las amenazas previsibles amenazas previsibles contra la seguridad de los activos de información
: Evaluación de riesgos: Estimar la probabilidad y el impacto de las violaciones de la seguridad para calcular la puntuación del riesgo y luego determinar si los riesgos identificados son aceptables

**Proponer salvaguardas**

: Proponer salvaguardas: Recomendar salvaguardas de CIS Controls V7 que reduzcan los riesgos inaceptables
: Evaluar las salvaguardas propuestas: Analizar el riesgo de las salvaguardas recomendadas para garantizar que plantean riesgos aceptablemente bajos sin crear una carga indebida

![Desktop View](/assets/img/riesgos_amenazas/puntuacion_cis.png){: width="972" height="589" }
_Puntuación en la guía CIS_

**Pasos del proyecto**

![Desktop View](/assets/img/riesgos_amenazas/pasos_cis.png){: width="972" height="589" }
_Pasos en la guía CIS_

#### Definir el alcance y planificar las sesiones (ejemplo)

![Desktop View](/assets/img/riesgos_amenazas/definir_alcance.png){: width="972" height="589" }
_Definir alcance en la guía CIS_

En ocasiones se diferencia entre activos primarios (primary assets) y de soporte (supporting assets)

: **Activos primarios**: actividades y procesos de negocio (business processes and activities) e información

- **Procesos** cuya pérdida o degradación harían imposible llevar a cabo la misión de la organización, procesos que contienen procesos secretos o que implican información propietaria, procesos que si se ven modificados podrían afectar el cumplimiento de objetivo de organización, procesos necesarios para cumplir con normativa / legislación vigente

- **Información** vital para el ejecutar la misión / negocio de la organización, información personal (ver leyes), información estratégica, información de alto valor

**Activos de soporte**: Hardware, software, red, personal, ubicación / emplazamiento, estructura de la organización

- Hardware: laptos, pdas, servidor, estaciones de trabajo, impresoras, discos externos, usbs, medios no electrónicos, ...

- Software: OS, sw administración, sw mantenimiento, sw bbdd, sw mensajería electrónica, sw servidor web, sw contabilidad, etc.

- Red: PSTN, ETH, GTth, ADLS, 802.11, Bluetooth, Firewire, switches, routers, hubs, ap, interfaces.

- Personal: quien toma decisiones, usuarios, personal de administración desarrolladores, ...

- Emplazamiento: lo que contien los activos de alcance, externo (casas de los empleados), interno (edificio de la organización), zonas internas, utilities y servicios (comunicaciones, agua, basura, AC, ...)...

- Organización: autoridades, estructura, organización de proyectos / sistemas, subcontratista, proveedores, fabricantes, ...

#### Definir los criterios de medición de riesgos

![Desktop View](/assets/img/riesgos_amenazas/balance_within_core_risk_analysis.png){: width="972" height="589" }
_Balance analisis de riesgo_

![Desktop View](/assets/img/riesgos_amenazas/example_impact_definitions.png){: width="972" height="589" }
_Ejemplo de definiciones de impactos_

![Desktop View](/assets/img/riesgos_amenazas/example_definitions.png){: width="972" height="589" }
_Ejemplo de definiciones de probabilidad_

#### Definir el criterio de aceptación de riesgo

En CIS RAM, la aceptación del riesgo tiene dos componentes:

: **Riesgo apropiado**: que la probabilidad de un impacto debe ser aceptable para todas las partes previsiblemente afectadas

: **Riesgo razonable**: que el riesgo que representa una salvaguarda debe ser menor o igual al riesgo contra el que protege.

![Desktop View](/assets/img/riesgos_amenazas/impactos_inaceptables.png){: width="972" height="589" }
_Impactos inaceptables_

![Desktop View](/assets/img/riesgos_amenazas/probabilidad_inaceptable.png){: width="972" height="589" }
_Probabilidad inaceptable_

![Desktop View](/assets/img/riesgos_amenazas/critero_aceptacion_riesgo.png){: width="972" height="589" }
_Criterio de riesgo aceptable_

En CIS RAM, la aceptación del riesgo tiene dos componentes:

: **Riesgo apropiado**: que la probabilidad de un impacto debe ser aceptable para todas las partes previsiblemente afectadas

: **Riesgo razonable**: que el riesgo que representa una salvaguarda debe ser menor o igual al riesgo contra el que protege

![Desktop View](/assets/img/riesgos_amenazas/heat_map.png){: width="972" height="589" }
_Heat map_

#### Medición de riesgo basado en controles (**control-base risk assessment**)

Uso de los "CIS Controls"

![Desktop View](/assets/img/riesgos_amenazas/risk_analysis_diagram.png){: width="972" height="589" }
_Diagrama de analisis de riesgos_

![Desktop View](/assets/img/riesgos_amenazas/risk_analysis_diagram_control.png){: width="972" height="589" }
_Diagrama de analisis de riesgos_

#### Proponer salvaguardas / medidas

Recomendaciones para tratar los riesgos

: Apropiados y razonables!!!

: **Adecuado**: una condición en la que los riesgos para los activos de información no crearán previsiblemente un daño mayor de lo que la organización o sus componentes pueden tolerar.

: **Razonable**: una condición en la que las salvaguardas no crearán una carga para la organización que sea mayor que el riesgo contra el que se pretende proteger.

![Desktop View](/assets/img/riesgos_amenazas/recomendaciones_tratar_riesgos.png){: width="972" height="589" }
_Recomendaciones para tratar los riesgos_

#### Intrucciones y documentos necesarios para realizar la gestión y análisis de riesgos

[CIS Risk Assessment Metoth (RAM) Versión 2.1 Core Document](/assets/img/riesgos_amenazas/CIS_RAM_v2.1_Core_Document_2022_08.pdf)

[Instrucciones implementar Group 1 (IG1)](/assets/img/riesgos_amenazas/CIS_RAM_v2.1_IG1_Workbook_Guide_2022_08.pdf)

[Hoja de calculo IG1](/assets/img/riesgos_amenazas/CIS_RAM_v2.1_for_IG1_Workbook_22.05.xlsx)

[Instrucciones implementar Group 1 (IG2)](/assets/img/riesgos_amenazas/CIS_RAM_v2.1_IG2_Workbook_Guide_2022_08.pdf)

[Hoja de calculo IG2](/assets/img/riesgos_amenazas/CIS_RAM_v2.1_for_IG2_Workbook_23.03.xlsx)

[Instrucciones implementar Group 1 (IG3)](/assets/img/riesgos_amenazas/CIS_RAM_v2.1_IG3_Workbook_Guide_2022_08.pdf)

[Hoja de calculo IG3](/assets/img/riesgos_amenazas/CIS_RAM_v2.1_for_IG3_Workbook_22.05.xlsx)