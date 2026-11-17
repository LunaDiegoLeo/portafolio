# Diego Leonardo Hernández Luna
### Portafolio de proyectos | Ingeniería en Sistemas Computacionales

Este repositorio reúne una selección de proyectos académicos, personales y colaborativos en los que he participado como desarrollador, líder de equipo e ingeniero de datos.

He trabajado en el diseño e implementación de bases de datos, desarrollo de aplicaciones web, integración de servicios, inteligencia artificial, procesamiento de datos y construcción de pipelines de ingeniería de datos.

Los proyectos documentan mi experiencia práctica con distintas tecnologías, desde el modelado de sistemas hasta la implementación de soluciones funcionales.



## Proyectos destacados

### 1.AutoPartes Laja-Bajío — base de datos de 79 tablas
**Rol:** Diseño de bases de datos y desarrollo SQL

Sistema de gestión de bases de datos relacional diseñado para integrar los procesos operativos y administrativos de una empresa manufacturera del sector automotriz.

- Diseñé el modelo entidad-relación y el esquema normalizado de **79 tablas**, considerando las áreas de personal, producción, calidad, inventarios, compras y ventas, con trazabilidad desde la materia prima hasta la facturación.
- Implementé **5 vistas SQL, 2 transacciones ACID y control de acceso basado en roles (RBAC)** con 12 roles operativos más el propietario del esquema.
- Desarrollé y documenté las estructuras para PostgreSQL 16 y MariaDB 10.11.

**Tecnologías:** PostgreSQL 16, MariaDB 10.11, SQL, modelado entidad-relación.

**Repositorio:** [AutoPartes Laja-Bajío](https://github.com/LunaDiegoLeo/MetalMecanica)



### 2. Sistema de Gestión de Reportes Municipales — Inteligencia Artificial y Base de Datos
**Rol:** Proyecto individual | Desarrollador

Plataforma web para el registro, clasificación, canalización y seguimiento de reportes ciudadanos relacionados con los servicios municipales de Celaya, Guanajuato.

- Desarrollé una plataforma web con PHP 8.2 y JavaScript, respaldada por una base de datos de **16 tablas en PostgreSQL**, con consultas adaptadas a MariaDB.
- Implementé generación de comprobantes PDF, geolocalización y visualización de reportes mediante un mapa interactivo.
- Entrené un clasificador **Naive Bayes** utilizando TF-IDF y stemming en español para sugerir el departamento responsable de cada reporte.
- Implementé autenticación mediante sesiones, contraseñas con hash, RBAC por usuario y departamento, y validación de archivos.

**Tecnologías:** PHP 8.2, JavaScript, PostgreSQL, MariaDB, Python, Scikit-learn, TF-IDF, Naive Bayes.

**Periodo:** Enero – Junio 2026.

**Repositorio:** [SistemaDeReportesMunicipales](https://github.com/LunaDiegoLeo/SistemaDeReportesMunicipales)



### 3. AutoCompanion AI — Panel de Inventario Integrado con Salesforce
**Rol:** Líder y desarrollador | Hackathon Salesforce 2026

Aplicación web para la consulta y visualización de información operativa de inventarios, integrada con Salesforce y herramientas de inteligencia artificial.

- Desarrollé un panel web con Node.js y Express, conectado a Salesforce mediante Apex REST y autenticación OAuth 2.0.
- Implementé **11 módulos de consulta, 6 indicadores KPI y 8 visualizaciones** utilizando Chart.js.
- Integré un agente de inteligencia artificial mediante Agentforce.
- Implementé medidas de seguridad como cookies httpOnly, Helmet, Content Security Policy (CSP) y rate limiting.

**Tecnologías:** Node.js, Express, Salesforce, Apex REST, OAuth 2.0, Agentforce, JavaScript, Chart.js.

**Evento:** Hackathon Salesforce 2026.

**Repositorio:** [saleforce](https://github.com/LunaDiegoLeo/saleforce)



### 4. Entre Líneas — Plataforma Web con Supabase
**Rol:** Creador y administrador

Plataforma web desplegada en producción, diseñada para ofrecer un espacio digital de publicación y consulta de contenido.

- Desarrollé y administro una plataforma con aproximadamente **30 usuarios semanales**.
- Implementé una API propia con Node.js y Express, conectada a Supabase.
- Integré autenticación JWT y mecanismos de protección de contraseñas.
- Implementé controles de seguridad mediante rate limiting, CORS y Helmet.

**Tecnologías:** Node.js, Express, Supabase, JWT, JavaScript.

**Periodo:** Mayo 2026 – Actualidad.

**Plataforma:** [Entre Líneas](https://entre-lineas-f6ek.onrender.com/)



### 5. SENTINEL-X — Pipeline de Streaming para Detección de Anomalías en Eventos de Red
**Rol:** Data Engineer | Equipo de 4 integrantes

Proyecto de ingeniería de datos enfocado en el procesamiento de eventos de red en tiempo real, detección de comportamientos anómalos y análisis de relaciones entre direcciones IP.

- Desarrollé un pipeline de procesamiento continuo utilizando Apache Kafka y Spark Structured Streaming, con ventanas de 30 segundos y generación de métricas por dirección IP.
- Implementé almacenamiento en Azure Data Lake Gen2 mediante arquitectura Medallion: Bronze en JSON y Silver/Gold en Parquet.
- Integré **Isolation Forest** para la detección de anomalías.
- Construí consultas analíticas con DuckDB, un dashboard en Grafana conectado a OpenSearch y un grafo de relaciones entre IP mediante FastAPI y D3.js.
- Configuré los servicios mediante Docker Compose.

**Tecnologías:** Python, Apache Kafka, Apache Spark, PySpark, Azure Data Lake Gen2, Parquet, JSON, Isolation Forest, DuckDB, Grafana, OpenSearch, FastAPI, D3.js, Docker.

**Periodo:** Octubre 2026 – Actualidad.

**Repositorio:** [Sentinel-x](https://github.com/LunaDiegoLeo/Sentinel-x)



### 6. Customer Churn Pipeline — Databricks, PySpark y XGBoost
**Rol:** Ingeniería de datos y Machine Learning

Solución de análisis predictivo para identificar clientes con probabilidad de abandonar un servicio, utilizando un pipeline de datos y modelos de clasificación.

- Construí un pipeline de datos con arquitectura Medallion para procesar información de **7,043 clientes**.
- Desarrollé y optimicé un modelo XGBoost enfocado en identificar la mayor cantidad posible de clientes en riesgo de fuga.
- Evalué el modelo mediante métricas de clasificación: **Recall 0.65, precisión 0.54 y exactitud 0.77**.
- Implementé análisis de interpretabilidad con SHAP y seguimiento de experimentos mediante MLflow.
- Construí un dashboard en Power BI para presentar los resultados y facilitar el análisis de negocio.

**Tecnologías:** Databricks, PySpark, Python, XGBoost, SHAP, MLflow, Power BI.

**Repositorio:** [customer-churn-pipeline](https://github.com/LunaDiegoLeo/customer-churn-pipeline)



## Otros proyectos

### Celaya Limpia
**Evento:** HackOnLinces 2026 | 5.º lugar | Equipo de 4 integrantes.

Aplicación móvil para la consulta de rutas de recolección de residuos, incorporando un modelo de red neuronal convolucional (CNN) para la clasificación de residuos.

### Monitoreo de Invernadero con ESP32
Sistema de monitoreo ambiental basado en ESP32, con integración de cuatro sensores, API REST con respuestas JSON y mecanismos de automatización para el control de una bomba de agua y un ventilador.

**Tecnologías:** ESP32, C++, sensores, HTTP, API JSON.

### Infraestructura y Administración de Redes
Diseño y configuración de una infraestructura de red empresarial en Cisco Packet Tracer, implementando enrutamiento dinámico OSPF, túneles GRE, NAT, PAT y listas de control de acceso (ACL).

**Tecnologías:** Cisco Packet Tracer, OSPF, GRE, NAT, PAT, ACL.

### Hospital Hernández — Sistema de Gestión Hospitalaria
Aplicación de escritorio para administrar pacientes, personal médico, citas, medicamentos y procesos hospitalarios.

- Diseñé e implementé una base de datos relacional.
- Desarrollé una interfaz de escritorio con Java y JavaFX.
- Implementé gestión de usuarios y acceso diferenciado por roles.

**Tecnologías:** Java, JavaFX, MariaDB, SQL.

**Repositorio:** [Hospital](https://github.com/LunaDiegoLeo/Hospital)



## Áreas de conocimiento

- **Bases de datos:** PostgreSQL, MariaDB, Supabase, SQL Server, MongoDB, OpenSearch; modelado ER, normalización, vistas, transacciones, RBAC.
- **Lenguajes:** Python, SQL, Java, JavaScript, PHP.
- **IA y Machine Learning:** Scikit-learn, XGBoost, SHAP, MLflow, Naive Bayes, CNN, Isolation Forest, agentes de IA.
- **Seguridad:** JWT, sesiones, cifrado de contraseñas, RBAC, CORS, Helmet, rate limiting.
- **Big Data y Cloud:** Spark/PySpark, Kafka, Databricks, DuckDB, ETL/ELT, Pandas; Azure (ADLS Gen2), AWS (S3, EC2), Docker, Linux, Git.
- **BI y Redes:** Power BI, Grafana, Chart.js, D3.js, Excel (básico); OSPF, GRE, NAT, ACLs.
- **Infraestructura y herramientas:** Docker, Docker Compose, Git, GitHub, Cisco Packet Tracer.



## Contacto

**Diego Leonardo Hernández Luna**  
Ingeniería en Sistemas Computacionales

- GitHub: [github.com/LunaDiegoLeo](https://github.com/LunaDiegoLeo)
- LinkedIn: [linkedin.com\in\diego-leonardo-hernández-luna-b9b294403](https://www.linkedin.com/in/diego-leonardo-hern%C3%A1ndez-luna-b9b294403)
- Correo: [diegolhl678@gmail.com]

