# Análisis de las empresas con valuación superior a 1 Billón de Dólares en 2022 (Unicornios)

## Resumen:
Se recopilaron y se procesaron los datos de las empresas con valuación superior al billón de Dólares en 2022 y tras un proceso de transformacion de los datos los mismos fueron conectados a Looker Studio para realizar una visualización de los mismos. Se utilizaron a su vez datos de los unicornios en 2023 para evaluar la evolución en el tiempo de la composición a nivel mundial de este fenemoneo. El análisis realizado arrojó una visión muy interesante sobre la composición de naciones implicadas en el conjunto y su representación, el sector de la industria al que pertenecen y a la velocidad de crecimiento vinculada a cada sector. De los resultados mas notalbes obtenidos se destaca la polarización hacia los USA y la hegemonia occidental considerando que Norte America, Europa y SudAmerica representan el 70% del sector por sobre Asia y Oceania.

## Introducción:
Este informe presenta un análisis detallado de las empresas cuya valoración de mercado superó la impresionante cifra de 1 billón de dólares en el año 2022. El estudio se basa en datos publicos disponibles a la fecha de publicación de este reporte y los datos ocnsiderados han sido la valuación, el financiamiento obtenido en el año, la fecha de creación de la empresa, la fecha en que se convirtieron en "unicornios", quienes fueron los principales inversores y su vinculación geográfica original.

## Metodología:
Se obtuvo un dataset de CB-Insights correspondiente al año 2023 y un dataset de Mavenanalytics correspondiente al año 2022.
Se realizo un relevamiento de los datos presentes y faltantes en uno y otro dataset como asi también se relevo si las categorias de industria, nombres de pais, ciudades y continentes respondian a un mismo criterio. Resulto evidente que no era asi y se realizaron transformaciones para verificar, validar y estandarizar los datos.
Para ello fue necesario emplear la base de datos de Naciones Soberanas publicada en el sitio de las Naciones Unidas la cual se utilizo para asignar correctamente la relacion entre paises, regiones y continentes. 
Se volcaron los datasets a un archivo de Google Sheets donde fueron transformados mediante el uso de formulas y tecnicas de manipulación de datos de ejecución manual empleando las herramientas automatizadas de Spreadsheets. Asimismo se hizo uso del asistente automatizado de Spreadsheets para unificar bajo un unico nombre los nombres de las ciudades que se encontraban en el dataset en diferentes variantes.
A fines de evitar un exceso de granularidad se decidio emplear como categorización geografica los continentes Norte America, SudAmerica, Asia, Oceania, Africa y Europa.

## Resultados:
(Trabajo colaborativo en progreso de extensión - Favor de contactarme si existe algun inconveniente en la visualización al momento de su consulta)
https://lookerstudio.google.com/s/jZqkmggyNTo


Sectores Destacados: Las empresas con valoraciones superiores a 1 billón de dólares abarcaban diversos sectores, incluyendo tecnología, servicios financieros, salud y consumo, entre otros.

Datos Relevantes:
a. Financiamiento en 2022: Se analizó la cantidad de financiamiento que cada empresa obtuvo durante el año 2022 para evaluar su capacidad de crecimiento y expansión.
b. Fecha de Creación: Se observó la fecha de fundación de cada empresa para comprender su trayectoria desde su inicio hasta la obtención de una valoración excepcional.
c. Fecha de Conversión en "Unicornio": Se analizó el momento en que cada empresa alcanzó una valoración de 1 billón de dólares o más, para identificar el tiempo que les tomó alcanzar este hito.

Inversores y Ubicación:
a. Principales Inversores: Se investigaron los inversores clave que contribuyeron al financiamiento y desarrollo de cada empresa.
b. País y Continente: Se determinó la ubicación geográfica de cada empresa, identificando el país y continente al que pertenecen.

## Conclusiones:
De las 1074 empresas cuya capitalización de mercado superó 1 billón de dólares en 2022 el análisis mas superficial reveló que estas  ocupan diversos sectores de la industria y que si bien sus orígenes geográficos presentan una gran dispersión existe una gran polarización en algunos paises que coinciden con el top del ranking de potencias mundiales en poder politico y economico pero tambien en poder de mercado como es el caso de India. 
Se evidenció una clara predominancia del sector por parte de empresas fundadas en norteamerica seguido por empresas del continente asiatico y el continente europeo. USA, China, India y UK fueron respectivamente los paises con mayor generación de los llamados Unicornios. Con el detalle de que USA y China abarcan el 84% del total de Unicornios del planeta. Asimismo en Europa, UK, Alemania y Francia lideran el sector que comparten con el resto de los paises europeos quienes tienen una distribución a grandes rasgos homoegenea de representación en el sector de producción de Unicornios a diferencia de lo que sucede en continentes como Oceania y Sud America.
Esta concentración significativa de unicornios en ciertos países y continentes, sugiere la importancia de los ecosistemas empresariales locales para el desarrollo de "unicornios".
La valuación de estos unicornios también demostro representar una gran dispersión al encontrarse en un rango entre 1 y 200 billones. Algunas empresas alcanzaron el hito de ser unicornios en poco tiempo después de su fundación, mientras que otras tuvieron un crecimiento más gradual. Se hizo evidente que si bien cada empresa tuvo un camino único hacia formar parte de este club considerando sus fechas de fundacion y fecha de alcanzar el status de Unicornio, existe una correlación marcada con el sector de industria al cual pertenecen. Al analizar la dimensión de inversores, se sugiere también que existen intereses en ciertos grupos de inversión que favorecen el financiamiento en algunos rubros por sobre otros favoreciendo asi el crecimiento y expanción de las empresas beneficiadas al mercado global.
Este análisis proporciona una visión valiosa para inversores, líderes empresariales y profesionales interesados en comprender el panorama de las empresas más valiosas del mundo en 2022 y los factores clave que contribuyeron a su éxito.

## Referencias:
Dataset 1 - Unicornios en abril 2023 - https://www.cbinsights.com/research-unicorn-companies
Dataset 2 - Unicornios en mayo 2022 - https://mavenanalytics.io/
Dataset 3 - Base de datos de paises soberanos de las Naciones Unidas - https://unstats.un.org/UNSDWebsite/


