# T02 — Ejercicios de clase

Ejercicios cortos para resolver en el aula. Dificultad: (b) básico, (m) medio, (r) reto.

## EC2.1 ¿IT u OT? (b)

Clasifica cada uno de los sistemas siguientes como IT, OT o mix IT/OT (escribe la
respuesta en la columna final):

| # | Sistema | IT | OT | Mix |
|---|---------|----|----|-----|
|1| Servidor de correo corporativo (Microsoft 365)| X | | |
|2| SCADA de una planta química que controla válvulas y sensores|  | X | |
|3| ERP en la nube que gestiona pedidos y facturación| X | | |
|4|PLC que gobierna una cadena de montaje| | X | |
|5| Plataforma de tickets de soporte (Jira, Zendesk)| X | | |
|6| Sistema MES que conecta el PLC con el ERP| | | X |
|7| Software de copias de seguridad de los servidores| X | | |
|8| Sistema de control de accesos de un edificio (tarjetas)| | X | |

## EC2.2 Departamentos IT de una empresa (b)

Mira el organigrama de tu empresa (o el de cualquier empresa mediana del sector TIC
que conozcas) y rellena la tabla siguiente: 

**Empresa CGI**

| Área / Departamento | ¿Qué gestiona? | ¿Por qué es entorno IT? |
|---------------------|----------------|-------------------------|
| **Desarrollo de software y aplicaciones** | Diseña, desarrolla y mantiene aplicaciones y programas para sus clientes. | Trabaja con software, programación y sistemas digitales. |
| **Ciberseguridad** | Protege los sistemas, redes y datos de los clientes frente a ciberataques. | Se encarga de la seguridad de la información y de los sistemas informáticos. |
| **Infraestructuras y sistemas** | Gestiona servidores, redes, almacenamiento y equipos informáticos. | Administra los recursos tecnológicos necesarios para el funcionamiento de los sistemas. |
| **Consultoría tecnológica** | Asesora a otras empresas para mejorar sus procesos mediante la tecnología. | Ayuda a implantar y optimizar soluciones y sistemas informáticos. |
| **Integración de sistemas** | Conecta diferentes aplicaciones, plataformas y bases de datos. | Permite que distintos sistemas informáticos compartan información. |

Si tu empresa no tiene departamentos diferenciados, elige una empresa del sector TIC de referencia (consultora, SaaS, agencia digital).

## EC2.3 Tecnología de negocio vs. de planta (b)

Para cada una de las tecnologías siguientes, marca con una cruz si la clasificaríamos como tecnología de negocio (back-office, administración, comercial) o de planta (producción, operativa, fabricación):

| Tecnología | Negocio | Planta |
|------------|---------|--------|
| ERP (SAP, Oracle, etc.)| X | |
| SCADA / HMI | | X |
| CRM (Salesforce, HubSpot) | X | |
| MES (Manufacturing Execution System) | | X |
| E-commerce (PrestaShop, Shopify) | X | |
| PLC / PAC | | X |
| BI / Data Warehouse | X | |
| Robots colaborativos (cobots) | | X |

## EC2.4 Qué hace que IT y OT se parezcan y se diferencien (m)

Rellena la tabla siguiente con 3 coincidencias y 3 diferencias entre IT y OT (no copies el texto del tema, reformúlalo):

| Aspecto | IT | OT | 
| ------- | -- | -- | 
| Coincidencia 1 | | | 
| Coincidencia 2 | | |
| Coincidencia 3 | | | 
| Diferencia 1 | | | 
| Diferencia 2 | | | 
| Diferencia 3 | | |

## EC2.5 Convergencia IT-OT de una consultora IT (m)

Lee el caso:

> BIT Consultores es una consultora IT de 60 personas que ha decidido ofrecer mantenimiento preventivo remoto a los clientes industriales. Para hacerlo, instala pequeños sensores IoT en las instalaciones del cliente (línea de producción, sala de servidores, climatización) y los conecta a una plataforma en la nube desde donde los técnicos de BIT monitorizan y actúan.

Responde:

1. ¿Cuál es el entorno IT de BIT Consultores? ¿Y cuál es el entorno OT que ahora
entra en casa del cliente?
2. ¿Qué sistema hace de puente entre los dos entornos?
3. ¿Qué tecnología habilitadora permite que un técnico de BIT vea, en tiempo real,
el estado de la línea de producción de un cliente a 500 km?
4. ¿Qué ventajas tiene para el cliente industrial?
5. ¿Qué riesgo nuevo introduce esta conexión que antes no existía?

EC2.6 Ventajas de una digitalización de extremo a extremo (m)

> La consultora IT DeltaCode ha pasado de:

- vender horas de programación a mano,
- a ofrecer un SaaS para la gestión de inventarios de pymes,
- integrado con el MES de un proveedor de maquinaria,
- y con soporte 24×7 monitorizado desde su NOC.

¿Qué ventajas de extremo a extremo (del sensor al cliente) identificas? Rellena esta
tabla con al menos 4 y justifica brevemente cada una:

| Ámbito | Ventaja | Justificación (1-2 frases) |
|--------|---------|----------------------------|
||||
||||
||||
||||

## EC2.7 Riesgos de conectar OT a Internet (r)

Una planta de packaging conecta su SCADA directamente a Internet para que un proveedor pueda hacer mantenimiento remoto. Identifica al menos 4 riesgos (técnicos, de seguridad u operacionales) y propón una medida de mitigación para cada uno.

