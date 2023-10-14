### <span style="color:grey">UML State Chart:</span>

Un diagrama de estado es una máquina que cambia de un estado a otro en tiempo de ejecución. Los estados están unidos por transiciones, cada una de las cuales tiene una condición de guardia. Se pueden llamar acciones o métodos tanto en estados como en transiciones. Cuando una condición de guardia obtiene el valor TRUE(evento), se activará la transición. Esto ejecuta las acciones o métodos que pertenecen a la transición y luego cambia al siguiente estado. Las condiciones de guardia son simplemente variables booleanas que reflejan eventos o son una expresión. Los eventos son entradas del usuario de una visualización/interfaz de usuario, E/S, eventos de tiempo o eventos del sistema. Otro evento que a menudo se requiere es el evento de finalización que ocurre cuando se completan las acciones o métodos de un estado.

Inserta todos los estados requeridos en el editor de diagrama de estado e implementa el control de flujo. Para hacer esto, codifique las condiciones de protección para las transiciones especificando una variable booleana o una expresión ST. Implementas la funcionalidad real del diagrama de estado en las acciones y métodos que se llaman en los estados o durante las transiciones.

Por tanto, los métodos y acciones asignados a un diagrama de estado contienen los algoritmos. Así es como se implementa el concepto de clase orientada a objetos de forma convencional.

Durante la fase de diseño del software, ya puede utilizar el editor de gráficos de estado como herramienta de diseño. Por ejemplo, puede crear un archivo de gráficos ( BMP) a partir de un diagrama de estado para agregarlo a una especificación o un documento de diseño.

- Identifica todos los estados que tendrá la máquina.

- Identificar las posibles transiciones de estado de un estado a otro.

- Identificar los eventos que ocurren durante el tiempo de ejecución de la máquina y que desencadenan una transición de estado. Agrupa los eventos relevantes cronológicamente.

- Identifique las ENTRY acciones o métodos DO de , y EXIT para llamar durante un estado.

- Identifique acciones o métodos para llamar durante las transiciones.

- Definir el comportamiento en caso de error.
***
- En TwinCAT para utilizar UML State Chart, se podra utilizar con el TF1910, el cual tendra un coste de licencia segun el Performance Level (PL)
***
### <span style="color:grey">Links UML State Chart:</span>
- 🔗 [infosys.beckhoff.com, tf1910_tc3_uml](https://infosys.beckhoff.com/english.php?content=../content/1033/tf1910_tc3_uml/3161408011.html&id=)
- 🔗 [content.helpme-codesys.com, UML State Chart](https://content.helpme-codesys.com/en/CODESYS%20UML/f_uml_sc.html)
- 🔗 [content.helpme-codesys.com, uml_sc_simple_machine](https://content.helpme-codesys.com/en/CODESYS%20UML/_uml_sc_simple_machine.html)
- 🔗 [content.helpme-codesys.com, _ex_uml_sc_coffee_machine](https://content.helpme-codesys.com/en/CODESYS%20Examples/_ex_uml_sc_coffee_machine.html)
- 🔗 [www.infoplc.net, el-nuevo-uml-state-chart-en](https://www.infoplc.net/descargas/42-codesys/2080-lenguajes-de-programaci%C3%B3n-de-codesys-incluido-el-nuevo-uml-state-chart-en)
***
### <span style="color:grey">Link al Video de Youtube_NNN:</span>
- 🔗