# Tarea: Mi prompt profesional

## Funcionalidad elegida
Sistema de registro de clientes para una tienda (Backend en Java).

## Version 1: prompt basico
```text
Hazme un código en Java para registrar clientes.
```

## Version 2
Actúa como desarrollador Java. Crea un programa en Java para gestionar el registro de clientes de una tienda. Usa una clase Cliente con los atributos: nombre, DNI y correo electrónico.

## Version 3: prompt final
Actúa como un desarrollador Java Senior. Tu tarea es crear un módulo para gestionar el registro de clientes en el backend de nuestra tienda llamada "TiendaTec".
Contexto: Estamos usando Java puro y necesitamos una clase Cliente y una clase RegistroClientes que permita agregar clientes a una lista y mostrarlos.
Ejemplos: Para los métodos, utiliza el estilo camelCase, por ejemplo: agregarCliente(Cliente c), listarClientes().
Formato: Explica primero la estructura lógica en un párrafo y luego presenta el código Java dentro de un bloque de código.
Restricción: No uses librerías externas, solo la librería estándar de Java (java.util).

## Componentes del prompt final

| Icono | Componente | Texto en mi prompt |
| :---: | :--- | :--- |
| 🎭 | **Rol** | Actúa como un desarrollador Java Senior. |
| 🎯 | **Instrucción** | Tu tarea es crear un módulo para gestionar el registro de clientes... |
| 📚 | **Contexto** | ...en el backend de nuestra tienda "TiendaTec". Estamos usando Java puro... |
| 💡 | **Ejemplos** | Para los métodos, utiliza camelCase, por ejemplo: `agregarCliente(Cliente c)`. |
| 📝 | **Formato** | Explica primero la estructura lógica en un párrafo y luego el código en un bloque. |
| 🚫 | **Restricción** | No uses librerías externas, solo la librería estándar de Java (`java.util`). |

## Evaluación del resultado

| Criterio | Resultado |
| :--- | :---: |
| ¿Se definió la clase `Cliente` con los 3 atributos? | ✅ Sí |
| ¿Se evitó el uso de librerías o dependencias externas? | ✅ Sí |
| ¿Se respetó el formato de bloque de código Markdown? | ✅ Sí |
| ¿Se incluyó una explicación previa a la estructura? | ✅ Sí |
| ¿Se usó camelCase en los nombres de los métodos? | ✅ Sí |

## Errores que evité

| Error frecuente | ¿Cómo lo evité en mi prompt final? |
| :--- | :--- |
| **Ser demasiado general** | Evité frases vagas como "hazme un programa". En su lugar, definí el problema exacto: *"crear un módulo para gestionar el registro de clientes"*. |
| **No indicar el formato** | Agregué una instrucción estricta de formato: *"presenta el código Java dentro de un bloque de código"* y *"explica primero la estructura"*. |