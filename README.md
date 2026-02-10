# Calculadora en Python con Flet

Este repositorio contiene el desarrollo de una **calculadora básica con interfaz gráfica**, creada utilizando **Python** y el framework **Flet**.  
El proyecto fue realizado con fines académicos para la materia **Tópicos Avanzados de Programación**.

La calculadora permite realizar operaciones matemáticas básicas mediante botones interactivos y una interfaz visual sencilla.

 🛠️ Tecnologías utilizadas

- **Python**: Lenguaje de programación principal.
- **Flet**: Framework para crear interfaces gráficas usando Python.
- **Visual Studio Code**: Editor de código.
- **Git Bash**: Terminal utilizada para ejecutar el programa y manejar Git.
- **GitHub**: Plataforma para alojar el repositorio del proyecto.

📋 Descripción general del proyecto

La aplicación es una calculadora que permite realizar las siguientes operaciones:

- Suma (+)
- Resta (-)
- Multiplicación (*)
- División (/)
- Porcentaje (%)
- Cambio de signo (+/-)
- Reinicio de valores (AC)

La interfaz está compuesta por botones organizados en filas y columnas, así como un área donde se muestra el resultado de las operaciones.


⚙️ ¿Cómo funciona la calculadora?

 1. Estructura general
El programa está dividido en varias clases que representan los distintos tipos de botones y la aplicación principal:

- `CalcButton`: Botón base.
- `DigitButton`: Botones numéricos.
- `ActionButton`: Botones de operaciones matemáticas.
- `ExtraActionButton`: Botones adicionales como AC, %, +/-.
- `CalculatorApp`: Contenedor principal de la calculadora.



 2. Interfaz gráfica
La interfaz se construye usando componentes de Flet como:

- `Container`: Contenedor principal de la calculadora.
- `Row`: Organiza los botones en filas.
- `Column`: Organiza toda la interfaz de manera vertical.
- `Text`: Muestra el resultado de las operaciones.

Cada botón tiene asignado un evento `on_click`, el cual se ejecuta cuando el usuario presiona un botón.

 3. Manejo de eventos
Cuando se presiona un botón:

- Se obtiene el valor del botón presionado.
- Dependiendo del tipo de botón (número, operación o acción), se ejecuta una lógica diferente.
- Los resultados se muestran en pantalla en tiempo real.

Esto se controla principalmente desde el método `button_clicked`.

4. Lógica de cálculo
La lógica matemática se maneja mediante:
- Variables para guardar el primer operando.
- Variables para guardar el operador seleccionado.
- Una función `calculate()` que realiza la operación correspondiente.
- Una función `reset()` que reinicia los valores de la calculadora.


 🎨 Modificaciones realizadas al tutorial original

Aunque el proyecto está basado en un **tutorial oficial de Flet**, se realizaron varias modificaciones para personalizarlo:

- Cambio del color de fondo de la calculadora.
- Cambio de colores en los botones numéricos y de operación.
- Modificación del color, tamaño y estilo del texto del resultado.
- Ajustes visuales para diferenciar el diseño del ejemplo original.

Estas modificaciones permiten que la calculadora no sea idéntica al tutorial base.

<img width="380" height="312" alt="image" src="https://github.com/user-attachments/assets/ce2503d5-9867-4798-a62a-7708a825a6ed" />

