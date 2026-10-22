# parche-dev

Sitio oficial del encuentro Parche Dev 2026, construido solo con HTML semántico.
Reto individual del Módulo 1 · HTML y CSS, RIWI.

Sitio publicado: https://Diddier10.github.io/parche-dev/

## Páginas

- Inicio
- Agenda
- Ponentes
- Inscripción y confirmación
- Código de conducta

## Cómo verlo en tu computador

1. Clona el repositorio.
2. Ábrelo en VS Code.
3. Abre index.html con Live Preview.

## Decisiones que tomé

- Se usó <ol> para el índice principal y el flujo del reporte porque tienen una secuencia lógica y jerárquica explícita (paso 1, paso 2, etc.).
- En cambio, se eligió <ul> para las reglas de comportamiento y listas de expectativas porque los ítems tienen la misma relevancia y su orden no altera el significado.
- Por qué sí: Se utilizó <time datetime="2026-10-01"> para la fecha de actualización porque proporciona un dato estandarizado y legible por máquinas.
- 1. Aparecen todos los datos que introduje en el formulario. 2.Espacios: Se reemplazan por el signo más (+) o por %20.Arroba (@): Se convierte en %40.Tildes y caracteres especiales (ñ, á, é, etc.): Se convierten en secuencias de bytes precedidas por %.3.Los campos vacíos que tienen el atributo name sí se envían en la URL, pero su valor queda en blanco. 4.Nunca se debe usar GET para datos sensibles o contraseñas por que pueden ser expuestas en pantalla.

## Lo que aprendí

- Es importante mantener una estructura clara.
- Debo investigar las distintas funciones que puedo utilizar en mi codigo.
- Mantener un plan de trabajo claro y estructurado facilita el desarrollo del codigo
## Hecho por

Diddier Javier Muñoz Cuervo· [GitHub](https://github.com/Diddier10)