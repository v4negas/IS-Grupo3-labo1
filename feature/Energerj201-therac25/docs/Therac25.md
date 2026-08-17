@ -16,47 +16,3 @@ Como consecuencia, la máquina podía activar una configuración de alta potenci
Problema de Ingeniería de Software

Uno de los principales problemas fue la dependencia excesiva del software para controlar funciones críticas de seguridad.

También se pueden identificar los siguientes problemas:

Falta de pruebas rigurosas.
Errores de software que no fueron detectados oportunamente.
Dependencia excesiva de mecanismos de seguridad implementados mediante software.
Falta de mecanismos de seguridad independientes.
Problemas relacionados con condiciones de carrera.
Falta de consideración de diferentes formas de interacción del operador con el sistema.
Relación con la Crisis del Software

El caso Therac-25 demuestra la importancia de aplicar buenas prácticas de Ingeniería de Software, especialmente en sistemas críticos.

Un sistema que controla equipos médicos debe ser desarrollado considerando la seguridad, las pruebas y la calidad del software desde las primeras etapas del proyecto.

El caso también demuestra que confiar únicamente en el software para evitar situaciones peligrosas puede generar consecuencias graves cuando existen errores que no han sido detectados.

Principio Ágil #9

La atención continua a la excelencia técnica y al buen diseño mejora la agilidad. 

Este principio se relaciona directamente con el caso Therac-25 porque la calidad técnica y el buen diseño son fundamentales cuando se desarrolla software para sistemas críticos.

En este caso, la falta de pruebas suficientes y la existencia de un error relacionado con una condición de carrera muestran la importancia de revisar cuidadosamente el funcionamiento del software y detectar posibles fallos antes de que el sistema sea utilizado.

La excelencia técnica implica desarrollar, probar y revisar continuamente el software para reducir la posibilidad de errores, especialmente cuando estos pueden tener consecuencias graves.

Lecciones Aprendidas

Entre las principales lecciones que deja el caso Therac-25 se encuentran:

Realizar pruebas rigurosas antes de poner un sistema crítico en funcionamiento.
No depender exclusivamente del software para funciones importantes de seguridad.
Analizar posibles condiciones de carrera y otros errores de concurrencia.
Utilizar mecanismos de seguridad independientes cuando sea necesario.
Considerar diferentes formas de interacción del usuario con el sistema.
Corregir y dar seguimiento a los problemas encontrados durante el funcionamiento del sistema.
Conclusión

El caso Therac-25 demuestra que los errores de software pueden tener consecuencias graves cuando un programa controla sistemas críticos.

La Ingeniería de Software debe considerar la seguridad, las pruebas, la calidad técnica y el buen diseño durante todo el desarrollo.

Por esta razón, el Principio Ágil #9 tiene una relación importante con este caso, ya que resalta la necesidad de mantener una atención continua sobre la calidad técnica del software.