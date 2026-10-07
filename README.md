# Taller-github-Trabajo-asistido-ciencia-de-datos

## ¿Quién es DJ Patil?

Dhanurjay "DJ" Patil (nacido en 1974) es un matemático y científico de la computación estadounidense. Es reconocido como uno de los creadores del término "científico de datos" y como el primer Chief Data Scientist de Estados Unidos (2015–2017), cargo que ocupó en la Oficina de Política Científica y Tecnológica de la Casa Blanca durante el gobierno de Barack Obama.

![FOTO](DJ_Patil.jpeg)

## Formación

- Pregrado en Matemáticas, Universidad de California, San Diego.
- Doctorado en matemáticas aplicadas.
- Investigador y profesor asistente en la Universidad de Maryland, donde trabajó en dinámica no lineal, teoría del caos y predicción numérica del clima.

## Trayectoria profesional

| Etapa | Rol |
|---|---|
| Academia | Investigador y profesor asistente, Universidad de Maryland |
| Industria | Cargos en eBay, PayPal y Skype |
| LinkedIn | Jefe de productos de datos y científico jefe |
| Capital de riesgo | Data Scientist in Residence, Greylock Partners |
| Gobierno | Primer Chief Data Scientist de EE. UU. (2015–2017) |
| Salud | Head of Technology, Devoted Health |

## Proyectos que lideró

- **Precision Medicine Initiative:** uso de grandes volúmenes de datos genómicos para mejorar el tratamiento de enfermedades.
- **Police Data Initiative:** apertura de datos policiales para aumentar la transparencia y la confianza entre la policía y la comunidad.
- **Data-Driven Justice:** uso de datos para reformar el sistema de justicia penal.
- **Cancer Moonshot:** apoyo con datos a la investigación contra el cáncer.
- **Creación de cargos de Chief Data Officer** en agencias federales (cerca de 40).

## ¿Qué lo hace un ejemplo de científico de datos?

1. **Combina áreas:** matemáticas, programación, producto y política pública.
2. **Lidera, no solo analiza:** dirigió equipos y definió estrategias de datos a escala nacional.
3. **Resuelve problemas reales:** salud, justicia, seguridad y servicios públicos.
4. **Comunica y promueve el uso responsable de los datos:** su misión declarada era usar los datos de forma responsable en beneficio de la ciudadanía.
5. **Ayuda a construir la profesión:** escribió sobre cómo formar equipos de ciencia de datos (*Building Data Science Teams*) y sobre convertir datos en productos (*Data Jujitsu*).

## Relación con el ciclo de un proyecto de datos

| Etapa del ciclo | Ejemplo en su trabajo |
|---|---|
| Definir el problema | Mejorar la confianza entre policía y comunidad |
| Obtener datos | Apertura de datos policiales y genómicos |
| Analizar y modelar | Identificar patrones en interacciones y tratamientos |
| Comunicar | Memorandos, informes y charlas públicas |
| Generar impacto | Nuevos programas y cargos de datos en el gobierno |

## Lecciones para un futuro científico de datos

- Las bases matemáticas y estadísticas son esenciales.
- El conocimiento del contexto (salud, justicia, negocio) importa tanto como el código.
- Comunicar resultados es parte del trabajo.
- La ética y la responsabilidad en el uso de datos son centrales.


## Proyecto: Data-Driven Justice

## 1. Contexto y Naturaleza del Proyecto
La iniciativa **Data-Driven Justice (DDJ)** fue impulsada por la Casa Blanca bajo el liderazgo de DJ Patil (Primer Científico de Datos Jefe de EE. UU.) en colaboración con la *National Association of Counties (NACo)*. 

**¿En qué consiste?**

Integra datos de múltiples agencias locales (policía, cárceles, hospitales y servicios de salud mental) y los procesa con modelos analíticos para identificar tempranamente a "utilizadores frecuentes" del sistema con necesidades complejas no resueltas. El objetivo es desviar a personas con problemas crónicos de salud mental y adicciones fuera del ciclo penal hacia tratamiento médico y vivienda comunitaria, antes de que vuelvan a ser arrestadas.

**Lenguaje cominmente usaso**: R,Python y SQL

**Ejemplos de plataformas, entidades u organismos que lo integran**: 
- Consejo General del Poder Judicial (CGPJ)
- Fiscalía General del Estado (FGE)
- Comité Técnico Estatal de la Administración Judicial Electrónica (CTEAJE)
- Conferencia Sectorial de Justicia

**¿Qué datos toma en cuenta?**
- **Interacciones policiales**: Registros de detenciones, causas de arresto previas, incidentes no delictivos o llamadas por disturbios menores.
- **Datos de salud y urgencias**: Visitas frecuentes a salas de emergencias (ER) e historial en centros de tratamiento de salud mental o adicciones.
- **Servicios sociales y de vivienda**: Registros de estancia en albergues para personas sin hogar y asistencia pública.
- **Factores socioeconómicos y procesales**: Capacidad económica para fianza, nivel de riesgo evaluado en la fase previa al juicio.


## Arquitectura del proyecto 
1. **Almacén de datos (Data warehouse)**
   
   Es un modelo de colaboración entre administraciones y organizaciones para transferir y obtener datos en un entorno de colaboración y corresponsabilidad.
   
   <img width="707" height="326" alt="image" src="https://github.com/user-attachments/assets/dab9f646-9976-4c61-bafe-2d2c9aafe9c6" />

2. **Dashboard**

   Un sistema de paneles y aprovechamiento de la información, con visualizaciones y formatos tabulares que permiten la toma de decisiones en políticas públicas basadas en evidencias.
   
   <img width="549" height="249" alt="image" src="https://github.com/user-attachments/assets/0ab9fe85-ea3c-4caf-aaf1-9b49ce3b02d1" />

3. **Uso de información georreferenciada**

   Un módulo de información georreferenciada que permite visualizaciones avanzadas de la información. El sistema de información cubre todo el territorio, llegando hasta el ámbito municipal, y permite      considerar también operaciones avanzadas.
   
   <img width="551" height="268" alt="image" src="https://github.com/user-attachments/assets/9c5ebd06-157f-4df7-9c05-34dce106791e" />

> [!NOTE]
> La información de la arquitectura y las imágenes fueron sacadas de: Ministerio de la Presidencia, Justicia y Relaciones con las Cortes. (s. f.). What is Data-driven Justice? Portal de Datos de Justicia. https://datos.justicia.es/en/what-is-data-driven-justice

## Impacto Social y Económico (Métricas de Éxito)
* **Reducción de Costos Públicos:** Hubo una disminución grande de gastos en el sistema penitenciario y hospitalario público.
* **Descongestión Carcelaria:** Reducción de cupos carcelarios destinados a delitos menores asociados a salud mental.
* **Rehabilitación Efectiva:** Incremento en el porcentaje de personas que se sometieron a tratamiento médico y vivienda comunitaria duradera.
> [!NOTE]  
> Davis, R. L., Austin, R. L., Jr., & Patil, D. (2016, 13 de octubre). Growing number of communities are using data to improve policing and criminal justice. The White House. https://obamawhitehouse.archives.gov/blog/2016/10/13/growing-number-communities-are-using-data-improve-policing-and-criminal-justice

## Conclusión

El análisis de iniciativas como *Data-Driven Justice*, impulsadas por líderes en la industria como DJ Patil, demuestra que el verdadero valor de la ciencia de datos no existe únicamente en la complejidad técnica de los algoritmos o el código, sino en su capacidad para resolver problemas sociales que afectan a un gran grupo de personas. 


