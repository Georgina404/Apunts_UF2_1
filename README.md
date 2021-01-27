# Apunts_UF2_1 - Diseño y realización de pruebas
### Introducción 
#### Objetivos de las pruebas
Las pruebas buscan validar si el software hace lo que debe hacer. Para ello existen diferentes frameworks que nos ayudan con la realización de las pruebas.

#### Framework
En general se compone por:
- conjunto de mejores prácticas y suposiciones
- herramientas comunes
- bibliotecas

Los framework permiten unificar el proceso de desarrollo entre desarrolladores.

### Pruebas
#### Forma de las pruebas
- Dinámicas: requieren ejecutar la aplicación y permiten medir el comportamiento de la misma.
- Estáticas: se realizan sin ejecutar el código (se examina el código fuente).

#### Estratégias de prueba
- Caja negra: el sistema se estudia desde fuera (se mira la funcionalidad). Se trabaja sobre la interfaz, se proporcionan entradas y se estudian las salidas. Principales técnicas: particiones de equivalencia, valores límite.
- Caja blanca: se examina el código fuente y su ejecución (se mira la estructura). Pueden comprobarse los flujos entre unidades y subsistemas. Principales técnicas: cobertura de código, pruebas de bucles.

#### Tipos de pruebas
- Funcionales: evaluan el cumplimiento de los requisitos. Ejemplos: pruebas unitarias, de regresión, de integración, de humo.
- No funcionales: evaluan aspectos adicionales. Ejemplos: pruebas de usabilidad, rendimiento, estrés, seguridad.

#### Mecanismos de prueba
- Manual: Las realiza el personal de la empresa o externo.
- Automático: es realizada a través de un software que ejecuta código de forma automatizada.

#### Frameworks
- Java: JUnit, TestNG
- C++: CppUnit, Google Test
- PHP: PHPUnit
- Javascript: Mocha

#### TDD
Test Driven Developement (TDD) (desarrollo guiado por pruebas de software)

### Integración
#### Formas de integración
- Big bang
- Descendente
- Ascendente
- Continua (CI)

#### Servidores de integración continua
CI -> Integración continua
CD -> Entrega continua

Servidores: Jenkinf, Bamboo, TravisCI, CircleCI

#### Cobertura del código
Medida que controla el porcentaje de código ejecutado durante las pruebas. El 100% indica que se ha ejecutado todo el código.

### Calidad
#### Control de calidad
A través de las pruebas podemos medir la calidad de un producto.
QA (procesos) o QC (productos)

#### Factores de calidad 
Según el modelo de calidad de McCall existen 11 factores: 
##### OPERACIÓN DEL PRODUCTO (afectan al uso del software)
    • Corrección: cumple especificaciones
    • Fiabilidad: software confiable, no tiene fallos
    • Eficiencia: mínimos recursos en software y hardware
    • Seguridad: control de acceso a los datos
    • Facilidad de uso: facilidad para usar el software
##### REVISIÓN DEL PRODUCTO
    • Mantenibilidad: esfuerzo para localizar y solventar un error
    • Flexibilidad: esfuerzo de modificar el programa
    • Facilidad de prueba: esfuerzo para realizar pruebas
##### TRANSICIÓN DEL PRODUCTO
    • Portabilidad: facilidad para migrar el software
    • Reusabilidad: facilidad para reutilizar el programa o parte de él
    • Interoperatividad: facilidad para que opere conjuntamente con otros sistemas
