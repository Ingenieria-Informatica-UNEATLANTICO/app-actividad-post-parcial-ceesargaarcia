# Sistema de Transporte Público - Documentación de Diagramas UML

## Índice
* [PDF del Examen Parcial Original](/documents/examen_parcial_cesar.pdf)
  * [Diagrama de Clases](/modelosUML/examenParcial/diagramaClases.puml)
  * [Diagrama de Objetos](/modelosUML/examenParcial/diagramaObjetos.puml)
  * [Diagrama de Estados](/modelosUML/examenParcial/diagramaEstados.puml)
* [Examen Parcial Mejorado](/modelosUML/examenMejorado/)
  * [Diagrama de Clases](/modelosUML/examenMejorado/diagramaClases.puml)
  * [Diagrama de Objetos](/modelosUML/examenMejorado/diagramaObjetos.puml)
  * [Diagrama de Estados](/modelosUML/examenMejorado/diagramaEstados.puml)

## Examen Parcial Original

### Diagrama de Clases Original

![Diagrama de Clases Original](/images/diagramaClasesBase.svg)

El diagrama representa las clases básicas del sistema:
* Vehiculo
* Conductor
* Pasajero
* Ruta
* Tarifa

Con relaciones simples entre ellas.

### Diagrama de Objetos Original

![Diagrama de Objetos Original](/images/diagramaObjetosBase.svg)

Muestra instancias específicas de las clases con datos de ejemplo:
* Autobus: Vehículo
* Juan: Conductor
* Ruta Santander-Maliaño
* Varios pasajeros
* Tarifa de 2.20€

### Diagrama de Estados Original

![Diagrama de Estados Original](/images/diagramaEstadosBase.svg)

Este diagrama muestra los estados básicos de los tres componentes principales del sistema

## Examen Parcial Mejorado

### Diagrama de Clases Mejorado

![Diagrama de Clases Mejorado](/images/diagramaClasesMejorado.svg)

Mejoras implementadas:
* Atributos detallados para cada clase:
  * Identificadores únicos
  * Propiedades específicas
  * Tipos de datos apropiados
* Métodos específicos para cada clase
* Cardinalidad en las relaciones
* Nuevos tipos de datos y enumeraciones
* Relaciones más precisas entre clases

### Diagrama de Objetos Mejorado

![Diagrama de Objetos Mejorado](/images/diagramaObjetosMejorado.svg)

Mejoras implementadas:
* Más instancias de objetos
* Datos más detallados y realistas:
  * IDs específicos
  * Valores concretos
* Múltiples tipos de tarifas
* Diferentes tipos de pasajeros
* Relaciones más completas entre objetos

### Diagrama de Estados Mejorado

![Diagrama de Estados Mejorado](/images/diagramaEstadosMejorado.svg)

Mejoras implementadas:
* Integración de los estados entre los tres componentes
* Sincronización de eventos entre estados
* Manejo de incidencias y situaciones excepcionales
* Flujo más detallado y coherente del sistema completo

## Notas Adicionales

Las mejoras implementadas en cada diagrama buscan:
1. Mayor claridad en la representación del sistema
2. Mejor manejo de casos de uso reales
3. Mayor detalle en las relaciones y atributos
4. Mejor representación de la lógica de negocio
5. Mayor facilidad de implementación

Los diagramas mejorados proporcionan una base más sólida para el desarrollo del sistema, considerando aspectos como:
* Gestión de incidencias
* Diferentes tipos de pago
* Estados del sistema
* Relaciones entre componentes
* Casos de uso específicos