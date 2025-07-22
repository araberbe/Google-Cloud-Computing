# Introducción a la Computación en la Nube

La computación en la nube es actualmente un tema de gran interés, pero muchas personas aún se preguntan: ¿qué es exactamente la nube?

El término **computación en la nube** fue acuñado por el Instituto Nacional de Estándares y Tecnología de los Estados Unidos (NIST, por sus siglas en inglés). Sin embargo, es importante destacar que este concepto no es exclusivo de Estados Unidos: es aplicable a nivel mundial.

La computación en la nube es una forma moderna de utilizar la tecnología de la información (TI) basada en cinco características igualmente importantes:

1. **Recursos Bajo Demanda y de Autoservicio**  
   En primer lugar, los clientes tienen acceso a recursos informáticos que se pueden solicitar bajo demanda y mediante autoservicio. Esto significa que, a través de una simple interfaz web, los usuarios pueden obtener la capacidad de procesamiento, el almacenamiento y las capacidades de red que necesiten, sin necesidad de intervención humana por parte del proveedor de servicios. Esta agilidad permite a las empresas acelerar sus operaciones tecnológicas sin depender de largos procesos administrativos.

2. **Acceso Remoto a los Recursos**  
   En segundo lugar, los clientes pueden acceder a estos recursos desde cualquier lugar donde tengan conexión a internet. Esto proporciona una flexibilidad enorme, ya que elimina la necesidad de estar físicamente en un centro de datos o en una oficina para utilizar las herramientas y servicios de TI.

3. **Recursos Centralizados y Compartidos**  
   La tercera característica es que los proveedores de servicios en la nube gestionan un gran conjunto de recursos que se asignan dinámicamente a los usuarios según sus necesidades. Al manejar un “pool” de recursos compartido, el proveedor puede comprar tecnología a gran escala, lo que genera importantes ahorros que luego son trasladados a los clientes en forma de precios más accesibles. Además, los usuarios no necesitan conocer ni preocuparse por la ubicación exacta de los recursos físicos que están utilizando; todo está abstraído.

4. **Elasticidad**  
   La cuarta característica clave es la elasticidad. Esto implica que los recursos de TI pueden incrementarse o reducirse rápidamente según los cambios en la demanda. Si una empresa necesita más capacidad de procesamiento o almacenamiento, puede obtenerla de forma casi instantánea. Si posteriormente esa demanda disminuye, también puede reducir sus recursos para evitar costos innecesarios. Esta elasticidad proporciona una enorme flexibilidad a organizaciones de todos los tamaños.

5. **Pago por Uso**  
   Finalmente, los usuarios pagan únicamente por los recursos que utilizan o que reservan, en función de sus necesidades específicas. No existen costos fijos innecesarios: si los usuarios dejan de utilizar los recursos, simplemente dejan de pagar por ellos. Este modelo es extremadamente eficiente desde el punto de vista económico, especialmente para startups o proyectos que necesitan controlar de cerca sus gastos tecnológicos.

---

## ¿Qué es la Infraestructura de TI?

El concepto de **infraestructura** se refiere al marco básico que sostiene un conjunto de instalaciones y sistemas. Para comprenderlo mejor, podemos hacer una analogía con la infraestructura de una ciudad.

En una ciudad, la infraestructura incluye servicios esenciales como transporte, comunicaciones, suministro de energía eléctrica, agua potable, combustible, y otros. Del mismo modo, en el mundo de la tecnología de la información, la **infraestructura de TI** proporciona los elementos esenciales para que funcionen los usuarios (personas) y las aplicaciones (software).

En esta analogía:
- Los **usuarios** serían los habitantes de la ciudad.
- Las **aplicaciones** serían los vehículos, edificios y otros componentes que utilizan esa infraestructura.

Todo lo que se necesita para crear, mantener y hacer funcionar estos servicios forma parte de la infraestructura.

---

## ¿Qué aprenderás en este curso?

En este curso, explorarás los servicios de infraestructura que ofrece **Google Cloud**.

Te familiarizarás con los diferentes servicios, aprenderás qué funciones cumple cada uno y comenzarás a comprender cómo utilizarlos de manera efectiva en distintos contextos profesionales o empresariales.

El objetivo principal es que al finalizar tengas una comprensión sólida de cómo aprovechar la infraestructura de Google Cloud para optimizar proyectos tecnológicos, ya sea en el desarrollo de aplicaciones, en el análisis de datos o en la administración de redes seguras.

---

## Transición hacia la Arquitectura en la Nube

Ahora que tienes una mejor comprensión de qué es la computación en la nube y de la infraestructura que la sostiene, avanzaremos hacia el concepto de **arquitectura en la nube**.

En esta sección, exploraremos cómo se compara la arquitectura en la nube con la arquitectura tradicional. Para comprender esta comparación de manera adecuada, primero es necesario repasar un poco de historia.

### Evolución hacia la Nube

La tendencia hacia la computación en la nube comenzó con una primera ola conocida como **colocación (colocation)**. La colocación ofrecía a los usuarios una eficiencia financiera significativa, ya que les permitía alquilar espacio físico en centros de datos en lugar de realizar grandes inversiones en bienes raíces para construir sus propios centros de datos.

Posteriormente, surgieron los **centros de datos virtualizados**, que representan la segunda ola de esta evolución. Estos centros de datos virtualizados comparten varias similitudes con los centros de datos privados y las instalaciones de colocación de décadas anteriores. Los componentes de estos centros virtualizados —como servidores, CPUs, discos, balanceadores de carga, entre otros— son equivalentes a los bloques físicos tradicionales de la computación alojada, pero ahora son dispositivos virtuales. Con la llegada de la virtualización, las empresas seguían manteniendo y administrando su propia infraestructura. Era, en esencia, un entorno controlado y configurado directamente por el usuario.

### La Revolución de Google: La Tercera Ola

Hace varios años, Google se dio cuenta de que su modelo de negocios no podía avanzar con la suficiente rapidez dentro de los límites del modelo de virtualización.

Por ello, Google decidió adoptar una **arquitectura basada en contenedores**, dando lugar a una tercera ola de la computación en la nube: una nube totalmente automatizada y elástica, compuesta por una combinación de servicios automáticos y datos escalables.

En esta nueva arquitectura:
- Los servicios aprovisionan y configuran automáticamente la infraestructura necesaria para ejecutar aplicaciones.
- La elasticidad y la automatización permiten que las aplicaciones escalen de forma dinámica y eficiente.

Actualmente, Google Cloud pone esta tecnología de tercera ola a disposición de sus clientes, permitiendo que las organizaciones aprovechen la misma infraestructura avanzada que Google utiliza internamente.

### La Visión de Google sobre el Futuro Tecnológico

Google sostiene que en el futuro, toda empresa —sin importar su tamaño o industria— se diferenciará de sus competidores a través del uso de la tecnología. Cada vez más, esa tecnología tomará la forma de software.

Un software excelente depende, a su vez, de datos de alta calidad.

Esto implica que, tarde o temprano, toda empresa será, en esencia, una empresa de datos.

---

## El Impacto Ambiental de los Centros de Datos

Aunque el mundo virtual parece intangible, está sostenido por una infraestructura física real: redes de cables, servidores, racks y centros de datos, que consumen enormes cantidades de energía.

De hecho, todos los centros de datos existentes en el mundo utilizan aproximadamente el **2% de la electricidad mundial**. Consciente de este impacto, Google trabaja intensamente para hacer que sus centros de datos sean lo más eficientes posible. Al igual que sus clientes, Google busca hacer lo correcto por el planeta. Comprendemos que los clientes de Google Cloud también tienen sus propios objetivos ambientales, y ejecutar sus cargas de trabajo en Google Cloud puede ayudarles a alcanzar dichas metas.

Por ejemplo:
- Google fue el primer proveedor en lograr la certificación **ISO 14001** en sus centros de datos. Esta norma internacional proporciona un marco para mejorar la eficiencia en el uso de recursos y reducir el desperdicio.
- Uno de los ejemplos destacados es el centro de datos de Google en **Hamina, Finlandia**, considerado uno de los más avanzados y eficientes de toda la flota de Google.

Este centro utiliza un sistema de refrigeración innovador que emplea agua del mar proveniente del Golfo de Finlandia, reduciendo así considerablemente el consumo de energía. Este método fue el primero de su tipo en el mundo.

### Compromiso Ambiental de Google

- Durante su primera década, Google se convirtió en la primera gran empresa en lograr la **neutralidad de carbono**.
- En su segunda década, fue la primera empresa en alcanzar el **100% de uso de energías renovables**.
- Mirando hacia el futuro, Google tiene como objetivo que para el año **2030** se convierta en la primera gran compañía en operar de manera completamente libre de carbono.

---

## Introducción a IaaS, PaaS y SaaS

Ahora cambiemos nuestro enfoque hacia **IaaS**, **PaaS** y **SaaS**.

La transición hacia los centros de datos virtualizados presentó a los clientes dos nuevos tipos de servicios:
- **Infrastructure as a Service (IaaS)**, o Infraestructura como Servicio.
- **Platform as a Service (PaaS)**, o Plataforma como Servicio.

### ¿Qué es IaaS?

Las ofertas de IaaS proporcionan capacidades básicas de cómputo, almacenamiento y red, organizadas de manera virtual en recursos que son similares a los de los centros de datos físicos tradicionales.

En este modelo:
- Los clientes pagan por los recursos que asignan por adelantado.
- Se mantiene un control más cercano sobre la infraestructura, pero ya no es necesario gestionarla físicamente.

### ¿Qué es PaaS?

Las ofertas de PaaS vinculan el código de las aplicaciones a bibliotecas que proporcionan acceso a la infraestructura necesaria.

Esto permite que:
- Los desarrolladores puedan centrarse más en la lógica de sus aplicaciones en lugar de ocuparse de los detalles de la infraestructura.
- El modelo de costos sea diferente, ya que los clientes pagan solo por los recursos que efectivamente utilizan.

### La Evolución hacia Infraestructura y Servicios Gestionados

A medida que la computación en la nube ha evolucionado, el impulso se ha desplazado hacia la **infraestructura gestionada** y los **servicios gestionados**.

Aprovechar recursos y servicios gestionados permite que las empresas:
- Se concentren más en sus objetivos comerciales, dedicando menos tiempo y dinero a la creación y el mantenimiento de su infraestructura técnica.
- Entreguen productos y servicios a sus clientes de manera más rápida y confiable, aumentando su competitividad y agilidad en el mercado.

### ¿Qué es Serverless?

El concepto de **Serverless** ("sin servidores") representa otro paso en la evolución de la computación en la nube.

La computación sin servidores permite a los desarrolladores:
- Concentrarse únicamente en su código, sin necesidad de preocuparse por la configuración o administración de servidores.
- Eliminar la gestión de infraestructura, ya que esta es manejada de forma automática por el proveedor de nube.

Entre las tecnologías serverless ofrecidas por Google se destacan:
- **Cloud Run**: permite a los clientes desplegar sus aplicaciones de microservicios contenarizadas en un entorno totalmente gestionado.
- **Cloud Run Functions**: gestiona código basado en eventos como un servicio de pago por uso.

### ¿Qué es SaaS?

También puede que hayas oído hablar de **Software as a Service (SaaS)**, o Software como Servicio, y te preguntes qué es y cómo encaja en el ecosistema de la nube.

Las aplicaciones SaaS:
- No se instalan en tu computadora local.
- Se ejecutan en la nube como un servicio y son consumidas directamente a través de Internet por los usuarios finales.

Algunos ejemplos muy populares de aplicaciones SaaS de Google incluyen:
- **Gmail**
- **Google Docs**
- **Google Drive**

Estos servicios, junto con otros, forman parte de lo que se conoce como **Google Workspace** y están completamente clasificados como aplicaciones SaaS.

---

## Tabla Comparativa: IaaS, PaaS, SaaS y Serverless

| **Modelo**   | **¿Qué ofrece?**                                                                 | **¿Quién lo gestiona?**                                                                 | **Ejemplos**                    |
|--------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|---------------------------------|
| **IaaS**     | Infraestructura virtual (servidores, redes, almacenamiento).                     | El cliente gestiona sistema operativo, aplicaciones y datos.                            | Google Compute Engine, Amazon EC2 |
| **PaaS**     | Plataforma para desarrollar y desplegar aplicaciones.                            | El proveedor gestiona infraestructura y middleware; el cliente solo su código.          | Google App Engine, Heroku       |
| **SaaS**     | Software funcional listo para usar.                                              | Todo es gestionado por el proveedor.                                                    | Gmail, Google Docs, Salesforce  |
| **Serverless** | Código que se ejecuta automáticamente, sin preocuparse por servidores.         | El proveedor gestiona infraestructura, escalado y eventos.                              | Google Cloud Run, AWS Lambda    |

---

## Ofertas Específicas de Google Cloud

Google Cloud se puede entender en tres capas principales:

1. **Capa base: Redes y Seguridad**  
   Esta capa constituye los cimientos para toda la infraestructura y aplicaciones de Google. Aporta conectividad segura y de alta velocidad.

2. **Capa media: Cómputo y Almacenamiento**  
   - Cómputo y almacenamiento están desacoplados, es decir, pueden escalar de manera independiente según la necesidad.  
   - Esto permite mayor flexibilidad para ajustar los recursos utilizados en cualquier momento.

3. **Capa superior: Big Data y Machine Learning**  
   - En esta capa se encuentran los productos que permiten ingerir, almacenar, procesar y entregar insights de negocio, así como desarrollar modelos de machine learning.  
   - Gracias a Google Cloud, se puede realizar todo esto sin necesidad de gestionar o escalar infraestructura directamente.

### Servicios de Cómputo de Google Cloud

Google ofrece un rango amplio de servicios de computación:
- **Compute Engine**
- **Google Kubernetes Engine**
- **App Engine**
- **Cloud Run**
- **Cloud Functions**

### Opciones de Almacenamiento de Google Cloud

Google Cloud también proporciona varias opciones de almacenamiento administrado:
- **Cloud Storage**
- **Cloud SQL** (base de datos relacional)
- **Spanner** (base de datos relacional escalable)
- **Bigtable** (base de datos NoSQL)
- **Firestore** (base de datos NoSQL)

### Productos de Big Data y Machine Learning

Google Cloud cuenta con una línea robusta de productos de Big Data y ML, que incluye:
- **Cloud Storage**
- **Dataproc**
- **Bigtable**
- **BigQuery**
- **Dataflow**
- **Firestore**
- **Pub/Sub**
- **Looker**
- **Spanner**
- **AutoML**
- **Vertex AI** (plataforma unificada de Machine Learning)

---

## Red de Google Cloud

La red de Google es la más grande de su tipo en el mundo:
- Google ha invertido miles de millones de dólares para construir su red.
- El objetivo es ofrecer el máximo ancho de banda y mínima latencia para los clientes.
- Google utiliza más de 100 nodos de caché de contenido distribuidos globalmente, acelerando la entrega de contenido.

### Infraestructura Geográfica

- Google Cloud opera en cinco ubicaciones principales:
  - América del Norte
  - América del Sur
  - Europa
  - Asia
  - Australia

- Cada ubicación está dividida en:
  - **Regiones**: áreas geográficas independientes (ej. Londres / europe-west2).
  - **Zonas**: subáreas dentro de cada región donde se implementan los recursos.

### Recursos Zonales y Regionales

- **Recursos zonales** operan en una sola zona.
- Si una zona falla, los recursos en ella se ven afectados.
- Google permite especificar el despliegue de servicios a nivel:
  - Zonal
  - Regional
  - Multi-regional

Esto mejora tanto el rendimiento (acercando apps a los usuarios) como la resiliencia ante desastres.

### Multi-Regionalidad

Algunos servicios permiten replicar datos entre múltiples zonas y regiones:
- Ejemplo: **Spanner** en configuración multi-región permite replicar datos en lugares como Países Bajos y Bélgica.
- Esto proporciona baja latencia para lecturas en distintos puntos geográficos.

Actualmente, Google Cloud cuenta con:
- **121 zonas en 40 regiones** (y sigue en expansión).

Para ver el estado actualizado:  
👉 [https://cloud.google.com/about/locations](https://cloud.google.com/about/locations)