# Ceneval Software Architecture
Created: 2021-10-12 14:28

- elementos tipicos del **proceso de requerimiento**: Analisis del probelma y Especificacion de comportamineto externo
- La **ingenieria de dominio** consisite en analisis, modelacion, y desarrollo de infraestructura
- antes de realizar el alojamiento de los requerimienots del sistema se debe de tener los requerimientos del sustema y la arquitectura de software
- el requerimiento no funcional de la confiabilidad va en todos los elementos del diseño arquitectonico
- segun el IEEE 830-1998 una buena especificaion de requerimeitnos de software debe de ser completa, verificable y rastreable
- requerimientos bien formados
	1. todo lo que supuestamente debe de hacer el software esta incluido en la especificacion
	2. cada reqerimeinto incluido en la especificaciontiene solo una interpretacion
	3. todos los requerimientos son entendibles por clientes no especialistas en computacion
-  un software que corre en varios ambientes de software y hardware es: **portable**
-  los elementos de una arquitectura de software de un sistema computacional incluyen:
	1. componenetes de software
	2. conectores expresando las relaciones enre componenetes de software
- la descripcion del dsieño de software detalla:
	1. descripcion de input-output para elementos de software
	2. base logica para el diseño de los elementos de software
	3. ejecucion conceptual, incluyendo flujo de datos y flujo de control
- los diagramas usados para un diseño orientado a objetos incluyen:
	1. class diagram
	2. activity diagram
	3. sequence diagram
- un buen diseño NO define una metodologia de revision de software
- un buen diseño SI:
	-  implementa todos los requsiitos implicitos y explicitos
	-  prove informacion para desarrolladores y testers
	-  menciona o incluye el dominio de daos, funcionalidad, y comportamiento desde una persepctiva de implementacion
-  el diseño para un programa de un componente incluye 
	-  estructuras de control
	-  algoritmos
	-  estructuras de datos
-  la principal ventaja de la programacion estructurada es que tiende a ser mas confiable
-  el aspecto mas importante de pruebas estructurales (caja blanca) es su habilidad para revelas la presencia de defectos en varias partes del codigo
-  las entradas para el proceso de pruebas de sistema incluye: requerimientos de rendimiento del sistema y requerimientos funcionales del sistema
-  un test oracle genera predicciones de resultados esperados de las pruebas
-  el **plan de preubas de aceptacion** se recomendaria para el proceso de especificacion de requerimientos
-  Un buen diseño basado en descomposicion modular tiene como caracteristica que sus modulos presenten bajo acoplamiento y alta cohesion
-  acoplamiento por datos es la mejor medida de acoplamiento ya que las estructuras se comunican a traves de parametros
-  behavioral design patterns: observer, iterator, strategy
-  structural design patterns: decorator, adapter, facade, proxy
-  creational design patterns:factory, abstract factory, singleton, prototype, builder
## Reference
1. 