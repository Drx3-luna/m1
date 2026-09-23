# Proceso ValidacionUmbrales

```
Proceso ValidacionUmbrales
    // Declaración de variables
    Definir stockActual, stockMinimo, capacidadMaximaEstante Como Entero;
    Definir requiereAuditoria Como Booleano;

    // Entrada de datos
    Escribir "Ingrese el stock actual:";
    Leer stockActual;

    Escribir "Ingrese el stock mínimo de seguridad:";
    Leer stockMinimo;

    Escribir "Ingrese la capacidad máxima de la estantería:";
    Leer capacidadMaximaEstante;

    // Regla de negocio sin condicionales
    requiereAuditoria <- (stockActual <= stockMinimo) O (stockActual > capacidadMaximaEstante);

    // Salida estricta según el requerimiento
    Escribir requiereAuditoria;
FinProceso
```
