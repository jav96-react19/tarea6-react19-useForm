# Tarea 6 React 19

**NOVEDADES respecto Tarea 5**

- Componente:

  - **Form** --> Gestión del estado del formulario con **useForm** de **react-hook-form**

- Directorio de **custom hooks**:

   - **FormData** --> Define el estado que almacenará los datos del usuario del formulario

- Directorio **models**:
  - **Logos.jsx** --> contiene el modelo de datos en formato JSON para cada logo.

- Directorio **utils**:

  - **ButtonDetails** --> contiene las funciones del botón de **¡Clicame!**:
     - **handleButtonClick**  --> Modifica el estado del botón de true a false y hace el recuento de veces que se ha clicado.
     - **handleButtonText** --> Modifica el texto del botón a partir de la referencia con **useRef** cuando el usuario se pone encima y sale
     del botón.

<br/>

![alt text](/src/assets/img/task6_preview.gif)


