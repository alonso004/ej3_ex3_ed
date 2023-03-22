# ej3_ex3_ed
Git branch refactorizacion
Echo "Refactoring is a systematic process of improving code without creating new functionality that can transform a mess into clean code and simple design." > refactorizacion.txt
Git add .
Git commit -m “Añadido concepto de refactorizacion”
Git status
Git branch patrones
Echo "Los patrones de diseño (design patterns) son soluciones habituales a problemas comunes en el diseño de software." > patrones.txt
Git add patrones.txt
Git commit -m “Añadida primera definición de patrones de diseño”
Git status
Git checkout main
Git merge patrones
Git status
Git branch -D patrones
Git status
Git branch patrones
Git checkout patrones
Echo "Cada patrón es como un plano que se puede personalizar para resolver un problema de diseño particular de tu código." > patrones.txt
Git commit -a -m “Añadida definición 2 de patrones de diseño”
Git checkout main
Echo "Los patrones son un juego de herramientas que brindan soluciones a problemas habituales en el diseño de software. Definen un lenguaje común que ayuda a tu equipo a comunicarse con más eficiencia." > patrones.txt
Git commit -a -m “Añadida definición 3.”
Git checkout main
Git merge patrones
Vim patrones.txt
Git merge patrones
Git commit -a -m “Resuelto conflicto de patrones.”
Git log
Git branch
