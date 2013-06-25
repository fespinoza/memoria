# Estructura de mi Informe de Memoria

## Introducción

toda esta información es casi todo lo que se puso en el informe final del E

* introducción a little sis
* origen del nombre de little sis
* fin de little sis
* presentación de poderopedia como clon chileno de littlesis
* estado actual de poderopedia
* lo bueno de la idea de littlesis y lo malo de no poder replicarlo en el área que quiera
* presentación del objetivo general de la memoria para llenar las falencias antes mencionadas
* posibles aplicaciones del trabajo de memoria
* aspectos técnicos importantes que resolver para realizar la memoria
* memoria basada en el trabajo de mauro san martín
* el uso de tecnologías RDF para publicar los datos generados
* guía de lectura del informe

## 1. Descripción del Proyecto

### 1.2. Objetivos

A continuación se enuncian los objetivos principales para este trabajo de memoria

#### 1.2.1. Generales

El objetivo de este trabajo consiste en crear una herramienta por la cual personas que estudian diversos tipos de redes
sociales como: sociólogos, periodistas, biólogos, etc; puedan representar, administrar y visualizar redes sociales
de mediana escala, contando además con la capacidad de combinar redes sociales con otros usuarios de la herramienta
para obtener redes sociales con información más completa ofreciendo esto como un servicio centralizado con la
capacidad de ser distribuido.

#### 1.2.2. Específicos

Enumeración de objetivos específicos extraídos del informe del E

### 1.3. Resultados esperados

* el resultado esperado **es una aplicación** que con **una interfaz amigable** me permita cumplir el objetivo general

### 1.4. Alcances

Especificar algunas limitaciones al problema a resolver con el fin de que la memoria sea un paso más acotado en la
solución final del problema:

* se resolverá el problema para redes sociales de menos de 100 actores **Tamaño pequeño, revisar este número**
* no se considerará la posible temporalidad de la red social

## 2. Marco Conceptual

*que conceptos debo manejar para entender la memoria, ej:*

* *nuevas tecnologías*
* *metodologías de desarrollo*
* *arquitectura estándar*

* explicación de lo que se trata esta sección
* indicación de saltar este capítulo si el lector maneja los conceptos

### 2.1 Conceptos de Redes Sociales

* explicación de que se van a reusar (copiar-pegar casi) los conceptos de redes sociales de la tesis de mauro

#### 2.1.1. Definiciones

* red social
* nodo
* actor
* atributo
* relación
* familia
* rol

### 2.2 Conceptos de Desarrollo

* que son los conceptos de desarrollo

#### 2.2.1 Desarrollo Web

* que es el desarrollo web
* arquitectura de cliente servidor
* que componentes típicos se encuentran en el desarrollo web
  * servidor
  * browser
    * web
    * movil
  * servidor de bases de datos
  * servidor de acceso a aplicaciones

#### 2.2.1.1 Desarrollo Front-End

* es el desarrollo que compone todos los aspectos de un sistema con los cuales interactúa un cliente, como el cliente
la arquitectura de cliente-servidor

#### 2.2.1.2 Desarrollo Back-End

* es desarrollo de software de la aplicación que guarda y procesa los datos del usuario

#### 2.2.2 El Modelo MVC

* definición, separación lógica de componentes de software en categorías de Modelo, Vista y Controlador
* explicación con ejemplo de que consiste un:
  * modelo
  * vista
  * controlador

#### 2.2.3 Frameworks de Desarrollo

* que se entiende como framework de desarrollo, que me proveen y quien los hace

##### 2.2.3.1. Server Side

* un framework server side es el cual cuyo código se ejecutará del lado del servidor y enviará la respuesta al cliente
* ejemplos para diversos lenguajes

##### 2.2.4.2. Client Side

* es una categoría de framework en donde el código se ejecuta en el mismo cliente, cúando es mejor usar esto y que gano
de esta forma
* ejemplos de estos frameworks

#### 2.2.5. HTML5

* a que se llama HTML5
* que entrega a diferencia de las versiones anteriores

##### 2.2.5.1 SVG, Gráficos Vectoriales en la Web

* que son y de que sirven estos gráficos (redimensión, formato común xml, etc)

## 3. Especificación del Problema
### 3.1 Antecedentes y soluciones existentes

A continuación se presentan algunas de las soluciones existentes que apuntan a resolver problemas similares al de esta
memoria.

#### LittleSis y Poderopedia

* que es littlesis
* screenshot de littlesis
* por que no cumplo el objetivo de la memoria con littlesis

* que es poderopedia: un clon chileno de littlesis en el cual se publican información sobre y de las relaciones entre
políticos y empresarios chilenos.
* screenshot de poderopedia
* screenshot de red social en forma de grafo
* por qué no sirve?: al igual que little sis

#### Memoria Alumno Manuel Bahamonde

* de qué se trata esta memoria y cual es la relación de esta memoria con la de manuel
* que me permite hacer
* screenshots del modelo de redes sociales
* que problemas tengo con la memoria de manuel?
  * no puedo unir redes sociales
  * establece restricciones en la aridad de las relaciones
  * no permite agregar atributos a los nodos y relaciones
  * no posee un formato de exportación genérico, sólo un formato único para una aplicación externa
  * necesita de que el computador del cliente tenga instalado java
  
#### Otras referencias

* que otras referencias de soluciones similares tengo?

### 3.2 Relevancia del problema

* el problema es relevante de tomar pues se le entrega a las personas una herramienta que les permite guardar datos de
redes sociales en forma interactiva y gráfica.
* permite que las personas puedan complementar su información con la información de otras personas
* permite la generación de información compatible con la web semántica por parte de personas con conocimientos básicos
de computación

### 3.3 Usuarios Objetivo

* quienes son mis usuarios objetivo

### 3.4 Requisitos / Criterios de Aceptación

se especifica en todo el detalle de los requisitos **(del informe del E)**

*Es una visión más funcional de los requisitos que se necesitan cumplir*

Se necesita un sistema que me permita crear y editar redes sociales y:
* crear, editar y borrar actores
* crear, edirar y borrar relaciones n-árias entre esos actores
* que me permita agregar, editar y borrar atributos de actores y relaciones
* que pueda unir redes sociales
* que pueda exportar mis redes sociales en formato RDF
* que pueda importar mis redes en formato RDF

En términos de requisitos de calidad se necesita:

* que la interfaz sea fácil de usar
* que la aplicación sea de fácil instalación

## 4. Descripción de la Solución

Esto es una descripción conceptual de la solución

### 4.1. SNM, Social Network Model

* explicar como se consideró usar este modelo

#### 4.1.1. Elementos de Redes Sociales

* una visión de algunas restricciones con los conceptos de redes sociales (actores, relaciones, atributos) que son necesarias para el modelo de mauro

#### 4.1.2. Definición Matemática

* definición formal del modelo de mauro, con todos sus elementos como grafo
* extracción de información a considerar (que es un nodo, que es una familia)

#### 4.1.3. Representación Gráfica

* un ejemplo de red social en la representación gráfica de la solución (extrayendo esto de su tesis)

#### 4.1.4. Representación Relacional del Modelo

* exponer la forma en que mauro representa este modelo en modelo relacional (para posterior comparación con lo realmente implementado)

### 4.2. Herramientas Elegidas


#### Rails

* que es rails (10 años de existencia)
* convenciones y distintos ambientes de desarrollo
* experiencia personal previa con la herramienta

#### EmberJS

* que es y como surgió
* que features claves entrega
* como esos features claves me sirven para desarrollar la memoria
* integración con rails

#### D3.js

* que es D3.js
* el paradigma de los 3 estados de D3: enter, update y exit


### 4.3. Arquitectura de la Aplicación

#### 4.3.1. Arquitectura de Hardware
arquitectura necesaria para que la aplicación corra en producción y por qué se eligió esta arquitectura

#### 4.3.2 Arquitectura de Software
back-end y front-end, y por qué se eligió esta arquitectura

#### 4.3.3. Diseño de la Base de Datos

* problemas enfrentados al implementar 
* representación modelo de mauro en BD relacional
* adiciones en términos de estilo y visualización de las redes

## 5. Funcionamiento Solución

Esta sección consiste básicamente en un manual de usuario de la aplicación, en donde se muestra en base a pantallazos como funciona la aplicación para lograr las tareas propuestas, respondiendo en todo momento:

1. qué feature estoy describiendo?
2. como funciona? (en términos de uso de la aplicación)
3. qué requisito cumple este feature? (hablando de ventajas de este enfoqu)

### 5.1 registro e ingreso de usuarios [screenshot]x2
### 5.2 creación de redes sociales [screenshot]
### 5.3 edición redes sociales
#### 5.3.1. creación y edición de familias [screenshot]
#### 5.3.2. creación y edición de actores [screenshot]
#### 5.3.2. creación y edición de relaciones [screenshot]
#### 5.3.2. creación y edición de atributos en nodos [screenshot]
### 5.4 exportación rdf [extracto de código]

* más vocabulario

### 5.5 importación rdf
### 5.6 unión de redes sociales [screenshot]
### 5.7 Casos de estudio

Algún ejemplo concreto de una red un poco más grande creada con esta aplicación


## 6. Conclusiones
### 6.1. Dificultades encontradas
cosas técnicas y metodológicas que fueron complejas al momento de enfrentar la memoria
### 6.2. Trabajo Futuro

* agregar endpoint virtuoso
* mejorar la escalabilidad de la aplicación
* habilitar un modo offline de la app
* evolución temporal de las redes sociales
