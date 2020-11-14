# API Testing para la aplicación Redmine

## Después de clonar este repo, ejecutar:
* ```mvn install...```
## Ejecución de pruebas
1. Ejecutar todos los features:
* ```mvn test -Dtest='ExamplesTest#testAll'```
2. Ejecutar un específico feature:
* ```mvn test -Dtest='ExamplesTest#testIssues''```
## Ejecución de pruebas de performance 
1. Ejecutar una prueba específica:
* ```mvn clean test-compile gatling:test```