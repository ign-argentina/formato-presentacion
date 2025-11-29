# Formato presentación
Formato para realizar presentaciones (slides) utilizando la clase beamer de LaTeX.
Respeta la tipografía y paleta cromática del [_Manual de Marca y Estilo_](recursos/Manual%20Marca%20Defensa.pdf) del Ministerio de Defensa, y la maquetación realizada por Relaciones Institucionales del IGN en febrero de 2024.

Se incluye una presentación de ejemplo y el código fuente para generarla.


## Tipografía y compilación

Los tipos de letra a utilizar no están disponibles en las distribuciones estándar de LaTeX.
Se proveen en `recursos/tipografia/` en formato OpenType Font (otf):
- tipo de letra con gracias (serif) [Lora](https://github.com/cyrealtype/Lora-Cyrillic)
- sin gracias (sans serif) [Montserrat](https://github.com/JulietaUla/Montserrat)

Utilizarles demanda compilar con `xelatex` o `lualatex` el código `presentacion.tex`. 

Los fondos para las primeras páginas, las de contenido y las de cierre de la presentación se ubican en `recursos/fondos/`.

Los logotipos se facilitan en `recursos/logotipos/`.

El material gráfico propio de la presentación se ubica en `figs/`.