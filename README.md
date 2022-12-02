# Civikmind
Plataforma Libre y de código abierto para la [Participación Ciudadana](https://es.wikipedia.org/wiki/Participaci%C3%B3n_ciudadana), Veeduría Ciudadana, Gestión de Comunidades Inteligentes, [Ciudades Inteligentes](https://es.wikipedia.org/wiki/Ciudad_inteligente) y [Gestión de activos inteligentes](https://es.wikipedia.org/wiki/Gesti%C3%B3n_de_activos) en el contexto de los [Objetivos de Desarrollo Sostenible](http://www.undp.org/content/undp/es/home/sustainable-development-goals.html) la cual nace desde el **Hacking Cívico**

| ## Problema a resolver |
| --- |
| Actualmente los problemas sociales en las ciudades son multidimensionales, no obstante todo se resume a solidaridad y colaboración. Sin esto, es complejo el intentar resolver problemas sociales, pero es aun más complejo, es el no disponer de una herramienta que permita convertir información, datos, propositos, ideas, proyectos y diagnosticos en impacto social positivo en acción. Esto convierte a Civikmind en una solución estrategica para aunar esfuerzos y concentrar a todas las partes interesadas de un reto y llevarlo acabo. No se puede depender de la voluntad politica cuando el sector público y privado aun registren altos niveles de corrupción e impacto medio ambiental negativo, mostrando así e inequivocamente su ausencia de conciencia social. Se hace necesario entonces la inteligencia colectiva, el uso de modelos disruptivos, datos abiertos  realizados de forma etica y con transparencia. `leer más`|

| ## Propósito |
| --- |
| Ser un mecanismo habilitador de [Democracia digital](https://es.wikipedia.org/wiki/Democracia_digital), participación política, veeduría ciudadana para materializar intenciones de construir de manera articulada alrededor de una idea, proyecto o iniciativa social en un territorio, procurando que sea simple, eficaz y fácil, de una manera creativa, abierta, solidaria y colaborativa, bajo mejores prácticas y marcos comunes.  |



## Licencia

La distribución de este software se hace bajo la licencia GNU GENERAL PUBLIC LICENSE Version 2 - favor revisar [Licencia](https://github.com/smartcitiescommunity/Civikmind/blob/main/LICENSE) para más detalles.

![Sustainable Development Goals](https://img.shields.io/badge/Sustainable%20Development%20Goals-Ready-blueviolet)
 | ![Smart City](https://img.shields.io/badge/Smart%20Citiy-%20Ready-orange) |![IOT](https://img.shields.io/badge/IOT-%20Ready-brightgreen)  | [Forkea nuestro repo](https://github.com/smartcitiescommunity/Civikmind/fork)
 
 |English | Français | 中文| русский |عرب|한국어|भारत|
|------------ | -------------|------------ | -------------|-------------|-------------|-------------|
| Software Solution for the Management of Smart Communities, Smart Cities and Smart Asset Management in the context of the Sustainable Development Goals| Plateforme pour la gestion des communautés intelligentes, des villes intelligentes et de la gestion des actifs intelligents dans le contexte des objectifs de développement durable | 可持续发展目标背景下的智慧社区，智慧城市和智慧资产管理管理平台| Платформа для управления умными сообществами, умными городами и умными активами в контексте Целей устойчивого развития | منصة لإدارة المجتمعات الذكية والمدن الذكية وإدارة الأصول الذكية في سياق أهداف التنمية المستدامة | 지속 가능한 개발 목표의 맥락에서 스마트 커뮤니티, 스마트 시티 및 스마트 자산 관리를위한 플랫폼| सतत विकास लक्ष्यों के संदर्भ में स्मार्ट समुदायों, स्मार्ट शहरों और स्मार्ट एसेट मैनेजमेंट के प्रबंधन के लिए मंच|

|Tareas del Proyecto | DevOps | Investigación|
|------------ | -------------|------------ |
|https://trello.com/civikmind | https://civikmind.slack.com | https://civikmind.bit.ai/|
|Ayudanos realizando alguna de las tareas |Todas las ideas de código o automatización son bienvenidas | Lo que vamos investigando o lo que nos cuentas lo vamos documentando. Todos los aportes son bienvenidos|
<img align="left" src="pics/scc.jpg?raw=true"/>

| **`SLES`** <img src="https://cdn.rawgit.com/smartcitiescommunity/Civikmind/e1070b30/pics/linux.svg"> | **`RHEL`** <img src="https://cdn.rawgit.com/smartcitiescommunity/Civikmind/e1070b30/pics/linux.svg"> | **`UBUNTU`** <img src="https://cdn.rawgit.com/smartcitiescommunity/Civikmind/e1070b30/pics/linux.svg"> | **`Windows`** <img src="https://cdn.rawgit.com/smartcitiescommunity/Civikmind/e1070b30/pics/windows.svg"> | **`MacOS`** <img src="https://cdn.rawgit.com/smartcitiescommunity/Civikmind/84d8b4da/pics/mac.svg"> | **`Estado`** | **`Appliance`** | **`Idioma`** | **`Tutorial`** |
|-----------------|---------------------|------------------|-------------------|---------------|---------------|---------------|---------------|---------------|
| OK :white_check_mark: | OK :white_check_mark: | OK :white_check_mark: | Fallo :collision: | OK :white_check_mark: | [![Estado](https://secure.travis-ci.org/glpi-project/glpi.svg?branch=master)](https://secure.travis-ci.org/glpi-project/glpi) | No disponible en el momento | :es: :us: :fr: :it: :de: 🇧🇷 :ru: :cn: :jp: :kr: 🇸🇦 | http://bit.ly/civikmind |

## Instalación
|Pasos|Instrucciones en la consola. [La instalación avanzada acá](https://github.com/smartcitiescommunity/Instalar-Civikmind)|
| ------- |------- |
|1. Actualizar el repositorio de instalación |```sudo apt update && sudo apt -y upgrade```| 
|2. Instalar base de datos |```sudo apt install mariadb-server && sudo mysql_secure_installation```| 
|3. Instalar lenguaje web |```sudo apt-get -y install php php7.2-{curl,gd,imagick,intl,apcu,recode,memcache,imap,mysql,cas,ldap,tidy,pear,xmlrpc,pspell,gettext,mbstring,json,iconv,xml,gd,xsl}```| 
|4. Instalar servidor web |```sudo apt-get -y install apache2 libapache2-mod-php```|
|5. Crear directorios |```sudo mk civikmind /var/www/html/ && sudo chown -R www-data:www-data /var/www/html/civikmind/```| 
|6. Descargar Civikmind |```git clone https://github.com/smartcitiescommunity/Civikmind.git /var/www/html/```|
|7. Terminar de instalar via web|```ir a http://localhost/civikmind/ desde su navegador y siga el paso a paso. Cambie localhost por la IP o DNS que usted tenga```| 

|Nota de apoyo|
| ------- |
|Agradecemos vea toda la aplicación, sus características y posibilidades. Pruébela, juzguéla, crítiquela y comparta su opinión pues es importante para el mejoramiento de la misma. Esta solución es el resultado de 23 años de estudio en las más variadas disciplinas y tecnologías. Si te agrada éste trabajo, si te inspira y encuentras una solución para transformar tu mundo, tu ciudad, tu comunidad no olvides darle una estrella a este repositorio e incluso si estás de acuerdo, puedes nominar a la persona que ha concentrado esfuerzos para que esta solución se ejecute en el [The GitHub Stars program](https://stars.github.com/nominate/) con el usuario [juanfernandovillahernandez](https://github.com/juanfernandovillahernandez). Todas las contribuciones son bienvenidas y a cada contribución se le dará sus respectivos créditos|

|¿Que es una Ciudad Inteligente?| ¿Que es un Hacker Civico? | La importancia del Hacking Cívico|
|------------ | -------------|------------ |
|Una ciudad inteligente es aquella en la que de manera articulada y planificada con todos sus habitantes y partes involucradas, construyen un territorio haciendo uso de sus conocimientos, mejores prácticas, tecnología, recursos y activos de manera sostenible, siendo ambiental y socialmente responsables, priorizando siempre  la calidad de vida y el bienestar del ciudadano. Juan F. Villa. (8 Abril de 2014)|Es el líder que colabora con otros para crear soluciones utilizando datos, código, tecnología, información y conocimiento abierto de carácter libre y público, buscando resolver desafíos políticos, económicos, sociales, tecnológicos, ambientales, legales, de seguridad y ética.|Existe una enorme brecha entre los ciudadanos y los actores públicos entre los cuales están los gobernantes, las instituciones de administración pública, los líderes políticos y los  partidos políticos, pues concentran el poder y la toma de deciones en asuntos que afectan o impactan a los ciudadanos de un territorio a nivel económico, social, tecnológico y ambiental sin tenerlos en cuenta en la mayoría de las situaciones, siendo ésto, una soterrada forma de violar derechos fundamentales, observando claramente una ausencia de transparencia, corrupción y arbitrariedad materializada en decisiones unilaterales|

## Actores y elementos en las ciudades y comunidades inteligentes

|Desde lo Tecnológico| Desde el Gobierno | Desde lo Social|
|------------ | -------------|------------ |
|Empresas y organizaciones de investigación orientadas a STEM, tecnologías de Smart City, tecnologías de la Cuarta Revolución Industrial|Marcos de legalidad, marcos normativos y de políticas públicas que habiliten las iniciativas políticas, económicas, sociales, tecnológicas y ambientales como también a nivel de planeación y estrategia en el uso y apropiación de recursos y activos del estado|Materializar liderazgos para una mejor participación en pro de los derechos humanos. Partiendo de la premisa "El ciudadano es el centro" debemos incluir costumbres, arte, cultura, el pensar y sentir de las personas y el como se integran a la construcción de sus territorios|

## Equipo

| ROL | Miembro del Equipo |
| ------------- | ------------- |
| Idea, dirección y desarrollo |[**Juan Fernando Villa**](https://www.linkedin.com/in/juanfernandovillahernandez/)|
| Base del software Civikmind: | Forkeado de [**GLPI**](https://github.com/glpi-project/glpi)|
| Conceptos: |[**Indira Carazo Roldan**](https://www.linkedin.com/in/indiracarazo/) y [**Francisco Javier Roldan**](https://www.linkedin.com/in/frajaro/) |
| Kickstarter: | [**Juan Felipe Campuzano Zuluaga**](https://www.galeriapolitica.com/galeriapolitica-com-entrevista-a-juan-felipe-campuzano/)|
| Apoyo Financiero  |[**Andrés Beltrán**](https://www.facebook.com/AndresJBeltran/)|
| Ideas de Mercadeo |[**Yessy Alejandro Lotero**](https://www.linkedin.com/in/yessy-alejandro-lotero-hernandez-74742917/)|
| Pruebas y Experiencia de usuario |[**Sergio Herrera**](https://www.linkedin.com/in/sergioandresherreravelasquez/)|
| Diseño Grafico: | [**Alejandro Cataño Garcia**](https://fb.watch/56FQNxk4ai/)  |
| Conceptos de Desarrollo: | [**Alejandro Angel Arango**]()|

## Funcionalidades - Gestión Social

| Funcionalidad | Especificidad |
|------------ | -------------|
|Toma  de decisiones |Es necesario tener una filosofia y [marco de trabajo](https://es.wikipedia.org/wiki/Framework), metodologías y planeación para tener mejores decisiones. Para este contexto es necesario ver de una manera clara y simple las actividades que se producen, ya sea por la lectura (tableros de graficos y datos) ó [Dashboards](https://es.wikipedia.org/wiki/Cuadro_de_mando) los cuales Civikmind posee|
|| Para mejor uso de Civikmind se puede hacer uso de la [Metodología 9D](https://github.com/smartcitiescommunity/9D) la cual permite ver las actividades que se producen en la plataforma con visión en contexto con los temas relacionados en Civikmind|
|||
||Cada petición validada puede estar realizada bajo anonimato para proteger la vida de las personas que formulan peticiones, problemas o denuncias que pueden poner en peligro su vida y así proteger a líderes sociales, defensores de derechos humanos e informantes de corrupción, irregularidades,[problemas de transparencia](https://es.wikipedia.org/wiki/Transparencia_pol%C3%ADtica) o actos en contra de la ley y la norma|
|| Cada petición es asignada a un responsable directo bajo criterio comunitario|
|| Cada petición pueder ser asignada a un grupo relacionado a uno de los [Objetivos de Desarrollo Sostenible](http://www.undp.org/content/undp/es/home/sustainable-development-goals.html) con mayor relación bajo criterio comunitario|
|| Cada petición pueder ser asignada a un grupo relacionado a un área de aplicación de la [Norma ISO 37120](https://es.wikipedia.org/wiki/ISO_37120) con mayor relación bajo criterio comunitario|
|| Cada petición pueder ser asignada a un proveedor tipo empresa que tenga implicación, relación directa o impacto directo según la categoria|
|| Cada petición pueder ser asignada a un proveedor tipo [organismo del estado](https://es.wikipedia.org/wiki/Estado), [función pública](https://es.wikipedia.org/wiki/Funci%C3%B3n_p%C3%BAblica) o funcionario que tenga implicación, relación directa o impacto directo según la situación, naturaleza o categoría|
|| Cada petición pueder ser asignada a un proveedor de la [sociedad civil](https://es.wikipedia.org/wiki/Sociedad_civil_(ciencia_pol%C3%ADtica)) que tenga implicación, relación directa o impacto directo según la situación, naturaleza o categoría|
|Gestión de  Grupos de personas| Opción de grupos segmentados bajo los [Objetivos de Desarrollo Sostenible](http://www.undp.org/content/undp/es/home/sustainable-development-goals.html)|
||Opción de grupos segmentados bajo las áreas de Aplicación de la [Norma ISO 37120](https://es.wikipedia.org/wiki/ISO_37120)|
||Correlación en peticiones, problemas, cambios, proyectos y activos entre otros|
|Gestión de personas| Seleccionar personas por categoría, título o etiqueta |
||Seleccionar personas según título|
||Seleccionar personas según etiquetas|
|Gestión del conocimiento| Sistema de preguntas de uso frecuente que pueden ser usados con el fin de conocer soluciones utiles |
||La información y experiencia documentada queda segmentada bajo los [Objetivos de Desarrollo Sostenible](http://www.undp.org/content/undp/es/home/sustainable-development-goals.html)|
||La información y experiencia documentada queda segmentada bajo las áreas de aplicación de la [Norma ISO 37120](https://es.wikipedia.org/wiki/ISO_37120) |
|Gestión Proyectos|Los proyectos pueden ser categorizados bajo los [Objetivos de Desarrollo Sostenible](http://www.undp.org/content/undp/es/home/sustainable-development-goals.html)|
||Los proyectos pueden ser categorizados bajo las áreas de aplicación de la [Norma ISO 37120](https://es.wikipedia.org/wiki/ISO_37120)|
||Se puede hacer uso de [metodologías ágiles](https://www.pmi.org/learning/library/es-balancing-agile-plan-oriented-methodologies-8881)|
||Se puede hacer uso de [tableros Kanban](https://es.wikipedia.org/wiki/Kanban_(desarrollo))|
||Se pueden generar [diagramas GANTT](https://es.wikipedia.org/wiki/Diagrama_de_Gantt)|
|Gestión Financiera|Es posible conocer quienes son los proveedores en cada proyecto|
||Es posible conocer cuáles son los contratos en cada proyecto|
||Es posible conocer cuáles son los costos en cada proyecto|
||Es posible conocer cuanto es el presupuesto en cada proyecto|
||Es posible conocer quienes son los proveedores en cada petición|
||Es posible conocer cuáles son los contratos en cada petición|
||Es posible conocer cuáles son los costos en cada petición|
||Es posible conocer cuánto es el presupuesto en cada petición|
|Gestión Territorio|Es posible conocer en que lugar sucede la petición, necesidad, reto, proyecto o denuncia ciudadanas|
||Es posible realizar trabajar por segmentación de ubicaciones o por territorios|


## Funcionalidades - Gestión Técnica

| Fundicionalidad | Especificidad |
|------------ | -------------|
|[Gestión de Activos](https://es.wikipedia.org/wiki/Gesti%C3%B3n_de_activos)| Gestión administrativa, contratos, documentos relacionados con componentes del inventario de activos, base de datos de conocimiento|
||Inventario de Activos digitales, Dispositivos y Archivos|
||Gestión de Garantias y [Ciclo de Vida](https://es.wikipedia.org/wiki/An%C3%A1lisis_de_ciclo_de_vida)|
| Cumplimiento en mesas de ayuda(ServiceDesk ITIL Compliant)|Gestión de problemas en varios entornos vía la creación de tickets, gestión de los tickets, asignación, planificación de los tickets para una Mesa de ayuda, etc.|
||Gestión de problemas, proyectos y cambios|
||Backlog y registro de actividades|
|Atención al usuario|Gestión y trazabilidad de TODAS las acciones realizadas en una petición|
|Usuarios|Historial de las intervenciones|
| |Encuestas de satisfacción|
| |Comentarios en las solicitudes|
| |Seguimiento de correos de la solicitud de intervención|
|Operación|Gestión de las solicitudes de intervención|
| |Escalamiento de los tickets bajo cumplimiento de mejores prácticas|
|Estadísticas|Información de activos en varios formatos (PNG,SVG,PDF)|
| |Estadísticas por categoría (por entidad, usuario, categoría, prioridad, ubicación)|
|Administración|Gestión del estado y de reservas del material|
||Gestión de los contratos y documentos|
||Sistema básico de un sistema de [Gestión del conocimiento](https://es.wikipedia.org/wiki/Gesti%C3%B3n_del_conocimiento)|
||Gestión de las solicitudes de soporte para todo tipo de inventario de material|
||Gestión de la información comercial y financiera (adquisición, garantía y extensión, amortización)|
|Reserva|Gestión de reservas|
||Interfaz usuario para gestión de calendarios|
|Base de datos de conocimientos|Gestión de artículos de la [base de datos de conocimiento](https://es.wikipedia.org/wiki/Base_de_conocimiento) y de la FAQ o [Preguntas Frecuentes](https://es.wikipedia.org/wiki/Preguntas_frecuentes)|
||Gestión de contenidos por objetivos (perfiles, grupos, entidades.)|
||Gestión de contenidos por Afinidad y Etiquetas|
||Gestión de contenidos por [Metodo 9D](https://github.com/smartcitiescommunity/9D)|
||Gestión de contenidos por [CivikMatrix](https://github.com/smartcitiescommunity/CivikMatrix)|
||Gestión de contenidos por [CivikBooks](https://github.com/smartcitiescommunity/CivikBooks)|
|Informes|Generación de informes por tipo de dispositivo, contratos asociados, informes comerciales, entre otros|
||Informes en formatos CSV para exportar a software  de [hojas de cálculo](https://es.wikipedia.org/wiki/Hoja_de_c%C3%A1lculo) (Libre Office,MS Excel, Google Sheets), analisis de datos o sistemas  de datos abiertos|
|Análisis|Exportar información en CSV o extraer por medio de API para ser llevado a otras aplicaciones y posterior analisis|
||Panel de Visualización de Estadisticas|
|Sistema API|Permite la comunicación con otras aplicaciones y mejoras en la capa de abstracción y bibliotecas del Civikmind|
|SLA - Acuerdo de nivel de servicio |Formalización de un contrato negociado con cualquiera de los proveedores y la definición del nivel de servicio esperado|
|Soporte Idiomas|Civikmind tiene adecuaciones realizadas en español no obstante soporte hasta 45 idiomas|


## Caracteristicas de administración en la interfaz

|Caracteristicas|Opciones|
|------------ | ------------- |
|Administración| Usuarios, Grupos, Entidades, Reglas, Diccionarios, Perfiles, Cola de notificaciones y Registros|
|Soporte| Peticiones, Problemas, Cambios, Planificación, Estadísticas y Peticiones recurrentes|
|Gestión| Licencias, Presupuestos, Proveedores, Contactos, Contratos, Documentos, Líneas, Certificados, Centros de datos, Clústeres, Dominios y Dispositivos|
|Herramientas| Proyectos, Recordatorios, Fuente RSS, Base de conocimiento, Reservas, Informes y Búsquedas guardadas|
|Activos| Computadores, Monitores, Software, Dispositivos de red, Dispositivos, Impresoras, Cartuchos, Consumibles, Teléfonos, Bastidores, Chasis, PDUs, Dispositivos Pasivos, Vehiculos Autonomos(Plugin), Drones(Plugin), Global|
|Configuración| Desplegables, Componentes, Notificaciones, Niveles de servicio, General, Campos de unicidad, Acciones automáticas, Autenticación, Destinatarios, Enlaces externos y Complementos|

##  Plugins
Ademas la plataforma viene precargada con 50 [plugins](https://plugins.glpi-project.org/#/plugins)  actualizados del Repositorio del  software Originario, que abre un panorama a otra clase de soluciones. Como buena practica revise que el plugin sea compatible con Civikmind verificando que tenga compatibilidad con versiones 9.5.5 o superior. Los dispositivos que posean una tarjeta o interfaz de red con un sistema operativo que les permite usar el protocolo SNMP, ICMP y/o permitan la instalación de clientes que se conecten a otras aplicaciones integrables al GLPI, habilitando la aplicación como sistema de gestión de información de dispositivos de red y sus incidencias.

##  Integración con Plataformas

|[OCS Inventory](https://ocsinventory-ng.org/?lang=en)|[Fusion Inventory](https://fusioninventory.org/)|[Zabbix](https://www.zabbix.com/)|[Grafana](https://grafana.com/)|[Nagios](https://www.nagios.org/)|[Shinken](http://www.shinken-monitoring.org/)|[Slack](https://slack.com/)|[Telegram](https://telegram.org/)|[Wazuh](https://wazuh.com/)|
|------------ | ------------- |------------ | ------------- |------------ | ------------- |------------- |------------- |------------- |
|[Plugin OCS Inventory](https://github.com/pluginsGLPI/ocsinventoryng)|[Plugin Fusion Inventory](https://github.com/fusioninventory/fusioninventory-for-glpi)|[Plugin Zabbix](https://github.com/janssenlima/zabbix-glpi)|[Plugin Grafana](https://github.com/ddurieux/glpi_app_grafana)|[Plugins Nagios](https://github.com/derricksmith/Nagios-Event-Handlers-for-GLPI)|[Plugin Shinken](https://github.com/shinken-monitoring/mod-glpidb)|[Plugin Slack](https://github.com/davejennings/hubot-slack-glpi)|[Plugin Telegram](https://github.com/pluginsGLPI/telegrambot)|[Plugin Wazuh](https://documentation.wazuh.com/current/user-manual/manager/manual-integration.html)|

|[Prelude](https://www.prelude-siem.com/en/)|[Mantis BT](https://www.mantisbt.org/)|[Graylog](https://www.graylog.org/)|[Rocket.Chat](https://rocket.chat/)|[Metabase](https://www.metabase.com/)|[Gitlab](https://about.gitlab.com/)|[Gdrive](https://drive.google.com/drive/my-drive)|[Jira](https://www.atlassian.com/es/software/jira)|
|------------ | ------------- |------------- |------------ | ------------- |------------- |------------- |------------- |
|[Plugin Prelude](https://github.com/pluginsGLPI/prelude)|[Plugin Mantis](https://github.com/pluginsGLPI/mantis)|[Plugin Graylog](https://github.com/airbus-cyber/graylog-plugin-glpi)|[Plugin Rocket.Chat](https://github.com/l33one/livechat)|[Plugin Metabase](https://github.com/pluginsGLPI/metabase)|[Plugin Gitlab](https://github.com/faizaleticia/gitlabintegration)|[Plugin Gdrive](https://github.com/ticgal/gdrive)|[Plugin Jira](https://valiantys.com/en/blog/agility/connect-asset-management-tool-jira-help-desk-nfeed/)|


## Autenticación

|SAML|CAS|X509|LDAP|SSO|Mail Server|
|------------ | ------------- |------------ |------------ | ------------- |------------ |
|[PLugin SAML](https://github.com/derricksmith/phpsaml)|Nativo|Nativo|Nativo|Nativo|Nativo|

## Citar formato APA

| Contexto de concepto | Lista de referencias | Contexto de Civikmind |
| ------------- | ------------- |------------- |
|- Villa, Juan F. (2021) sugiere en el Software “Civikmind (2021)” que … . |Villa, Juan F. (2021). Civikmind (2021) [Software]. Recuperado de https://github.com/smartcitiescommunity/Civikmind/|- Según el software Civikmind (2021)… Villa, Juan F. (2021).|

## Organizaciones que nos avalan
| Smart Cities Community |  Centro de Innovación y Desarrollo Texnológico País del Conocimiento| Smart Cities Community U.S |
| ------------- | ------------- |------------- |
| <img align="center" src="pics/logo_scc.png?raw=true" width="60%"/>|<img align="center" src="https://media-exp1.licdn.com/dms/image/C4E0BAQGnjmEKoiziNA/company-logo_200_200/0/1519904835018?e=1627516800&v=beta&t=tGDF_YoIIMgoF8UupRnDjRHZnROvqLZoy2zF8UhGpw0" width="80%"/>|<img align="center" src="pics/logo_scc.png?raw=true" width="20%"/>|

## Redes Sociales

|[Linkedin](http://bit.ly/Smart-Cities-Community-Linkedin)|[Youtube](http://bit.ly/Smart-Cities-Community-Youtube)|[Facebook](http://bit.ly/Smart-Cities-Community-Facebook)|[Twitter](http://bit.ly/Smart-Cities-Community-Twitter)|
| ------------- | ------------- |------------- |------------- |
|En nuestra red profesional estaremos publicando información tipo B2B|Sigue nuestros videos, suscribete a nuestro canal y activa la campanita|Participa activa activamente en nuestro sitio de Facebook comparte con la comunidad y hagamos inteligencia colectiva|Nuestras opiniones y link de interes|

## Copying

* **Nombres**: [GLPI](http://glpi-project.org/) is a registered trademark of [Teclib'](http://www.teclib-edition.com/en/).
* **Documentación**: released under Attribution 4.0 International ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)).


:circus_tent: :european_post_office: :house_with_garden: :school: :house: :church: :office: :house: :convenience_store: :post_office: :department_store: :factory: :hospital: :house: :house_with_garden: :bank: :atm: :house: :hotel: :house_with_garden: :department_store: :factory: :japanese_castle: :european_castle: :tokyo_tower: :house: :circus_tent: :european_post_office: :house_with_garden: :school: :house: :church: :hospital: :house: :house_with_garden: :bank: :atm: :house: :hotel: :house_with_garden: :house_with_garden: :school: :house: :church: :hotel:

:heavy_minus_sign: :articulated_lorry:  :bus: :heavy_minus_sign: :heavy_minus_sign: :heavy_minus_sign: :bike: :heavy_minus_sign: :heavy_minus_sign: :heavy_minus_sign: :car: :heavy_minus_sign: :heavy_minus_sign: :heavy_minus_sign: :blue_car: :heavy_minus_sign: :fire_engine: :heavy_minus_sign: :minibus: :heavy_minus_sign: :articulated_lorry:  :bus: :heavy_minus_sign: :heavy_minus_sign: :heavy_minus_sign: :bike: :heavy_minus_sign: :heavy_minus_sign: :heavy_minus_sign: :car: :heavy_minus_sign: :heavy_minus_sign: :heavy_minus_sign: :blue_car: :heavy_minus_sign: :fire_engine: :heavy_minus_sign: :minibus: :blue_car: :heavy_minus_sign: :fire_engine: :heavy_minus_sign: :minibus: :heavy_minus_sign: :heavy_minus_sign: 

:stadium: :classical_building: :building_construction: :bricks: :houses: :derelict_house: :house: :house_with_garden: :office: :post_office: :european_post_office: :hospital: :bank: :hotel: :love_hotel: :convenience_store: :school: :department_store: :factory: :japanese_castle: :european_castle: :wedding: :tokyo_tower: :circus_tent: :european_post_office: :house_with_garden: :school: :house: :church: :hospital: :house: :house_with_garden: :bank: :atm: :house: :hotel: :house_with_garden: :house_with_garden: :school: :house: :church: :hotel:  :love_hotel: :convenience_store: :school:


## Activismo y Causas Sociales
<p align="center">
  <img src="pics/smart_cities2.png?raw=true" width="512" alt="Activismo">
</p>

**Civikmind** sistema de gestión de información orientado a la gestión de peticiones ciudadana. esta orientado a los objetivos de desarrollo sostenible y las normas relacionadas a la ISO 37120.

Puede ser usado tanto por organizaciones Sociales, Comunitarias, Politicas, Activistas, Defensores de derechos humanos, Veeduria ciudadana, Transparencia y Anticorrupción, Lideres sociales como tambien Lideres politicos y afines.

## Objetivos de Desarrollo Sostenible
<p align="center">
  <img src="https://i1.wp.com/www.un.org/sustainabledevelopment/es/wp-content/uploads/sites/3/2015/09/ODSbann.jpg" width="100%" alt="ODS">
</p>

**Civikmind** Busca la implementación efectiva de los objetivos de desarrollo sostenible y mejores practicas sociales, buscando a su vez que las intenciones globales se puedan hacer posibles a través de una plataforma como **Civikmind** la cual hace que el trabajo y los objetivos sean posibles de realizar.

## Mejores prácticas & Estandares
<p align="center">
  <img src="pics/smart_cities2.png?raw=true" width="512" alt="ISO">
</p>

**CivikMind** es un sistema de gestión de información y activos basado en la aplicación GLPI. 
Entre sus potencialidades encontramos que hace uso de manera integrada ya sea de forma filosofica, completa o parcial de las normas o estandares: iso 9001, 14001, 20000, 21500, 27001, 31000, 37120 y adaptable a muchas otras. Tambien hace uso de mejores practicas a nivel integrado como lo es ITIL, Agilismo, Auditoria y Gobierno de TI.

## Gestión de Ciudades Inteligentes
<p align="center">
  <img src="pics/smart_cities2.png?raw=true" width="512" alt="Ciudades">
</p>

**Civikmind** Su principal caracteristica es la adecuada gestión de la información bajo las mejores practicas las cuales pueden ser usadas para la gestión de ciudades inteligentes, Las caracteristicas incluidas permiten que este sistema controle de manera eficiente y eficaz con una fuerte orientación al logro y al resultado, Caracteristicas esenciales para la correcta gestión de una Ciudad Inteligente o Smart City.



