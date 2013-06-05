# Estructura de mi Informe de Memoria

## 1. Introducción

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

### 1.1. Descripción del Proyecto

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

que cosas se esperan obtener luego del trabajo realizado

### 1.4. Alcances

que no va a incluir el trabajo de memoria

* manejo de redes sociales muy grandes

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
acá hablo de:

* littlesis
* poderopedia
* la memoria del manuel
* etc

### 3.2 Relevancia del problema
por qué es importante solucionar el problema?

### 3.3 Requisitos
se especifica en todo el detalle de los requisitos **(del informe del E)**

### 3.4 Criterios de Solución
definir los criterios de aceptación de una solución


## 4. Descripción de la Solución
Esto es una descripción conceptual de la solución

### 4.1. SNM, Social Network Model

* explicar como se consideró usar este modelo

#### 4.1.1. Definición

* definición del modelo de mauro como grafo, extrayendo esto de su tesis

#### 4.1.2. Representación Gráfica

* un ejemplo de red social en la representación gráfica de la solución (extrayendo esto de su tesis)

#### 4.1.3. Características de este modelo

* un listado resumen de los principales puntos fuertes de este modelo

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
#### Arquitectura de Hardware
arquitectura necesaria para que la aplicación corra en producción y por qué se eligió esta arquitectura
#### Arquitectura de Software
back-end y front-end, y por qué se eligió esta arquitectura
#### Diseño de la Base de Datos

* problemas enfrentados al implementar 
* representación modelo de mauro en BD relacional
* adiciones en términos de estilo y visualización de las redes

#### Diseño de Interfaz de Usuario

algunas muestras de los principales elementos gráficos de la app

* detalle de los modos de edición
* formulario de edición de nodos
* representación de actores y relaciones

### 4.4 Validación de la solución
analizar como la solución recién descrita cumple con los objetivos planteados anteriormente

## 5. Conclusiones
### 5.2. Dificultades encontradas
cosas técnicas y metodológicas que fueron complejas al momento de enfrentar la memoria
### 5.1. Trabajo Futuro

* agregar endpoint virtuoso
* mejorar la escalabilidad de la aplicación

<!-- TODO: agregar subsub section to index -->