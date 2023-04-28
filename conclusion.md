# Conclusiones

El diagrama de clases consta de **4 clases** llamadas: **Persona**, **Cliente**, **Empleado**, **Directivo**.

## Persona

La clase persona consta de dos variables, **Nombre** y **Edad**, que son atributos **comunes** de la clase Cliente y la clase Empleado. Tambien consta de su contructor, sus get y set.

## Cliente

La clase Cliente tiene una variable **telefono** y **hereda de persona tanto el Nombre como la Edad**. Tambien consta de su contructor, su get y set de Telefono.

## Empleado

La clase Empleado tiene una variable **SueldoB** referente al sueldo bruto y **hereda de persona tanto el Nombre como la Edad**. Varios empleados pueden o no ser **subordinados** de un Directivo y para indicar eso añadimos **"0..*"** (ninguno o varios empleados son subordinados de Directivo) Tambien consta de su contructor con el SueldoB, sin el SueldoB (depende de si el empleado tiene sueldo o no), su get y set de SuedoB.

## Directivo

La clase Directivo tiene una variable **Categoria** y **hereda de Empleado** que a su vez **hereda de persona** tanto el Nombre como la Edad.
