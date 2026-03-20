---

# Lab 08 - Real Estate Web App (Parte 1: Comparación de Propiedades)

## Descripción del Proyecto
Esta es la primera parte de la aplicación web de bienes raíces que vimos en clase y donde aplicamos conceptos de Web del curso y posteriormente fue construida con React y TypeScript. El objetivo principal de esta entrega es implementar una herramienta interactiva que permita a los usuarios comparar múltiples propiedades lado a lado antes de tomar una decisión de compra o alquiler.

## Funcionalidades Implementadas (Definition of Done)
Se cumplieron todos los criterios establecidos en la rúbrica para la Parte 1:

*   **Selection UI & Max Limit:** Los usuarios pueden seleccionar propiedades a través de un botón dedicado (`CompareButton`). El sistema valida y restringe la selección a un máximo de 3 propiedades simultáneas.
*   **Comparison Table:** Una vista dedicada (`ComparePage`) que muestra las propiedades seleccionadas lado a lado.
*   **Métricas Clave:** La tabla expone de forma clara el Precio, Habitaciones, Baños, Área y Precio por metro cuadrado de cada propiedad.
*   **Best Highlighted:** Lógica matemática implementada para resaltar dinámicamente el **precio más bajo** y el **área más grande** entre las opciones seleccionadas.
*   **Remove from Compare:** Capacidad de deseleccionar y eliminar propiedades directamente desde la vista de comparación.
*   **Empty State:** Interfaz amigable que notifica al usuario cuando no hay propiedades seleccionadas en la tabla.

---
**Video de explicación de la parte 1:** [https://youtu.be/EOjnLaoc3go]
