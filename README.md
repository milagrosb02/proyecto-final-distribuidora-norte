# Proyecto Final - Distribuidora Norte 📑​

Proyecto desarrollado en el marco de las **Prácticas Profesionalizantes** de la carrera, orientado al análisis de procesos y a la aplicación de conceptos de **Seguridad Informática** en un entorno real.

El trabajo fue realizado sobre **Distribuidora Norte**, un emprendimiento comercial de la ciudad de Posadas, Misiones, dedicado a la venta y distribución de bebidas y otros productos.

El proyecto parte del relevamiento del funcionamiento cotidiano del negocio para identificar sus procesos principales, recursos tecnológicos, información utilizada, posibles riesgos y oportunidades de mejora.

---

## 🎯 Objetivo del proyecto

El objetivo principal fue analizar el funcionamiento de Distribuidora Norte desde una perspectiva de sistemas y seguridad informática, identificando los puntos del proceso que podrían verse afectados por fallas técnicas, pérdida de información, accesos no autorizados, fraudes u otros incidentes.

A partir del relevamiento realizado se desarrollaron distintas propuestas orientadas a:

- representar los procesos principales del negocio;
- identificar dispositivos, aplicaciones, cuentas y registros utilizados;
- detectar riesgos y vulnerabilidades;
- evaluar los riesgos según su probabilidad e impacto;
- establecer medidas de mitigación y contingencia;
- mejorar la seguridad de dispositivos y cuentas;
- definir una estrategia de copias de seguridad;
- establecer procedimientos básicos de actuación ante incidentes.

---

## 🏪 Escenario analizado

Distribuidora Norte es un negocio comercial cuya actividad comprende principalmente:

- control de stock;
- compra de mercadería a proveedores;
- recepción y verificación de productos;
- registro del ingreso de stock;
- recepción de pedidos de clientes;
- venta y entrega de mercadería;
- cobro mediante efectivo o medios digitales;
- validación de comprobantes;
- registro de ventas e información comercial.

Durante el relevamiento se observó que parte de la información del negocio se encuentra distribuida entre un sistema de gestión, archivos Excel y diferentes dispositivos móviles.

---

## 🔎 Metodología de relevamiento

Para obtener información sobre el funcionamiento real del negocio se utilizaron principalmente dos técnicas:

### Observación

Se observaron las tareas realizadas por los vendedores durante el desarrollo habitual de sus actividades, registrando información relevante para su posterior análisis.

### Entrevista estructurada

Se realizaron preguntas a los integrantes del negocio utilizando tanto preguntas abiertas como cerradas.

Las preguntas abiertas permitieron comprender el funcionamiento general de la distribuidora, mientras que las preguntas cerradas fueron utilizadas para confirmar aspectos específicos del proceso.

La información obtenida mediante estas técnicas fue tratada como **información primaria**.

---

## 🔄 Análisis de procesos

Se representó el funcionamiento de Distribuidora Norte mediante distintos tipos de diagramas.

### Diagrama de flujo

Representa el proceso general del negocio, desde la verificación del stock hasta la compra a proveedores o la venta al cliente.

Incluye decisiones relacionadas con:

- disponibilidad de productos;
- necesidad de realizar compras;
- selección de proveedores;
- estado de la mercadería;
- reposiciones;
- medios de pago;
- validación de comprobantes;
- actualización del stock.

### Diagramas de casos de uso

Se desarrollaron casos de uso correspondientes a los principales actores involucrados:

- Vendedor
- Proveedor
- Cliente
- Sistema de gestión

Los casos de uso fueron acompañados por su documentación correspondiente, incluyendo:

- descripción;
- actores;
- precondiciones;
- flujo principal;
- flujos alternativos;
- postcondiciones.

### Diagramas de secuencia

Se elaboraron diagramas de secuencia para representar la interacción entre los distintos participantes durante:

- compra a proveedores;
- venta a clientes.

---

## 💻 Recursos tecnológicos identificados

Durante el relevamiento se identificaron diferentes dispositivos y recursos utilizados para el funcionamiento cotidiano del negocio.

### Dispositivos

- Teléfonos móviles utilizados para atención al cliente y comunicación con proveedores.
- PC de escritorio utilizada para el sistema de gestión e inventario.
- Notebook utilizada para registros comerciales.
- Equipamiento de red.

### Aplicaciones y servicios

- WhatsApp
- WhatsApp Business
- Facebook Marketplace
- Mercado Pago
- Sistema de gestión
- Microsoft Excel

---

## 📊 Registros utilizados

El negocio utiliza distintos medios para registrar y consultar información.

Entre ellos se identificaron:

### Sistema de gestión

Utilizado principalmente para:

- control de stock;
- registro de ventas;
- consulta de información de productos.

### Registro de ventas en Excel

Incluye información como:

- fecha;
- producto;
- cantidad;
- precio total;
- forma de pago;
- ganancia.

### Lista de precios en Excel

Contiene información relacionada con:

- productos;
- precios de venta;
- presentación;
- precios de compra;
- margen de ganancia.

### Lista de proveedores

Contiene:

- nombre del proveedor;
- datos de contacto;
- productos comercializados.

---

## 🌐 Representación de red

Se utilizó **Cisco Packet Tracer** para realizar una representación de los dispositivos que participan en la infraestructura tecnológica de Distribuidora Norte.

La representación incluye:

- teléfonos móviles;
- PC;
- notebook;
- punto de acceso;
- switch;
- conectividad de red.

El archivo correspondiente se encuentra disponible en este repositorio.

---

## ⚠️ Análisis de riesgos

A partir del análisis de los procesos se identificaron diferentes riesgos asociados al funcionamiento del negocio.

Entre ellos:

- malware;
- phishing;
- comprobantes de pago falsos;
- fallos de hardware;
- fallos de software;
- averías eléctricas;
- pérdida de información;
- dificultad para recuperar conversaciones;
- accesos no autorizados;
- pérdida o robo de dispositivos.

Los riesgos fueron analizados considerando los recursos involucrados y las consecuencias que podrían generar sobre la operación del negocio.

---

## 📈 Matriz de riesgos

Se elaboró una matriz de riesgos en **Microsoft Excel** para evaluar los riesgos identificados.

Para cada situación se analizaron aspectos como:

- etapa del proceso;
- actividad;
- actor involucrado;
- recurso;
- origen del riesgo;
- vulnerabilidad;
- probabilidad;
- impacto;
- severidad.

La severidad permite establecer qué riesgos requieren mayor atención.

Como complemento se elaboraron gráficos que muestran:

- cantidad de riesgos según su nivel de severidad;
- cantidad de riesgos identificados según la etapa del proceso.

El archivo completo de la matriz se encuentra incluido en este repositorio.

---

## 🛡️ Plan de mitigación y contingencia

A partir de los riesgos identificados se desarrolló un plan compuesto por tres elementos:

**Riesgo → Mitigación → Contingencia**

### Mitigación

Incluye las medidas destinadas a reducir la probabilidad de ocurrencia o disminuir el impacto de los riesgos.

### Contingencia

Define las acciones a realizar cuando un incidente ya ocurrió, con el objetivo de recuperar la operación y reducir sus consecuencias.

Se contemplaron situaciones relacionadas con:

- malware;
- phishing;
- comprobantes falsos;
- fallas de hardware y software;
- problemas eléctricos;
- pérdida de información;
- accesos no autorizados;
- pérdida o robo de dispositivos.

---

## 🔐 Plan básico de hardening

También se desarrolló un plan de hardening orientado a fortalecer la configuración de los dispositivos y cuentas utilizadas en el negocio.

Entre las medidas propuestas se encuentran:

- utilización de PIN seguro;
- biometría;
- bloqueo automático de pantalla;
- verificación en dos pasos;
- revisión de dispositivos vinculados;
- actualización del sistema operativo;
- instalación de parches;
- mantenimiento preventivo;
- revisión de sesiones activas;
- configuración de copias de seguridad.

---

## 💾 Estrategia de copias de seguridad 3-2-1

Se propuso implementar una estrategia basada en la regla **3-2-1**.

La propuesta consiste en mantener:

1. una copia original de la información;
2. una copia adicional en un medio físico;
3. una copia externa al establecimiento.

Para Distribuidora Norte se propuso utilizar:

- **PC de la distribuidora:** información original;
- **disco HDD adicional:** copia física;
- **Google Drive:** copia externa en la nube.

Entre la información a proteger se incluyen:

- archivos Excel;
- registros comerciales;
- listas de precios;
- proveedores;
- comprobantes;
- contactos;
- información relevante de WhatsApp y WhatsApp Business.

---

## 🚨 Respuesta ante incidentes

Se definieron procedimientos básicos de actuación para responder ante diferentes incidentes.

Los procedimientos contemplan situaciones como:

- infección por malware;
- compromiso de información;
- interrupción operativa;
- pérdidas financieras;
- phishing;
- comprobantes falsos;
- fallas de hardware;
- fallas de software;
- averías eléctricas;
- pérdida de información;
- dificultad para recuperar conversaciones;
- accesos no autorizados;
- pérdida o robo de dispositivos.

Además se establecieron buenas prácticas operativas destinadas a reducir la posibilidad de que estos incidentes ocurran.

---

## 🛠️ Herramientas utilizadas

Durante el desarrollo del proyecto se utilizaron diferentes herramientas:

- **Microsoft Word** - elaboración y documentación del informe.
- **Microsoft Excel** - elaboración de la matriz de riesgos y análisis de información.
- **Cisco Packet Tracer** - representación de la infraestructura de red.
- **PlantUML** - elaboración de diagramas de secuencia.
- **Lucidchart** - representación de procesos y diagramas.
- **GitHub** - almacenamiento y documentación del proyecto.

---

## 📁 Contenido del repositorio

### `ProyectoFinal-DistribuidoraNorte.docx`

Documento principal del proyecto.

Contiene:

- descripción del escenario;
- evidencias del relevamiento;
- diagramas;
- análisis de procesos;
- identificación de dispositivos y aplicaciones;
- metodología utilizada;
- análisis de riesgos;
- matriz de riesgos;
- representación gráfica de los riesgos;
- plan de mitigación y contingencia;
- hardening;
- estrategia de copias de seguridad;
- procedimientos de respuesta ante incidentes;
- buenas prácticas;
- conclusión;
- referencias.

### `matrizRiesgos.xlsx`

Matriz utilizada para evaluar los riesgos identificados en Distribuidora Norte según probabilidad, impacto y severidad.

### `DistribuidoraNorte.pkt`

Archivo de **Cisco Packet Tracer** que contiene la representación de los dispositivos y conexiones utilizadas como referencia para la infraestructura del negocio.

---

## 📚 Áreas de conocimiento aplicadas

El proyecto permitió integrar conocimientos correspondientes a diferentes áreas de la carrera:

- análisis de sistemas;
- relevamiento de información;
- modelado de procesos;
- UML;
- redes;
- gestión de riesgos;
- seguridad informática;
- hardening;
- continuidad operativa;
- copias de seguridad;
- respuesta ante incidentes;
- documentación técnica.

---

## 🎓 Contexto académico

Proyecto realizado como parte de las **Prácticas Profesionalizantes**.

**Área:** Seguridad Informática  
**Institución:** Teclab Instituto Técnico Superior  
**Año:** 2026

---

## 📌 Estado del proyecto

✅ Relevamiento del negocio  
✅ Modelado de procesos  
✅ Diagramas de casos de uso  
✅ Diagramas de secuencia  
✅ Representación de red  
✅ Análisis de riesgos  
✅ Matriz de riesgos  
✅ Representación gráfica  
✅ Plan de mitigación y contingencia  
✅ Plan de hardening  
✅ Estrategia de backup 3-2-1  
✅ Procedimientos de respuesta ante incidentes  
✅ Documentación final

---

## 📄 Uso académico

Este repositorio fue creado con fines académicos y documenta el trabajo desarrollado durante las Prácticas Profesionalizantes.

La información presentada se utiliza exclusivamente como evidencia y documentación del proyecto realizado sobre Distribuidora Norte.
