Laboratorio 11: Vercel

1- ¿Cuál es la finalidad del archivo vercel.json?

    Configurar el comportamiento del despliegue en Vercel, incluyendo rutas, funciones, y configuraciones específicas del proyecto.

2- ¿Qué ventajas tiene desplegar en Vercel frente a un servidor tradicional?

    -Despliegue automatizado y rápido.
    -Escalabilidad integrada.
    -HTTPS por defecto.
    -Integración con Git.
    -Menor necesidad de mantenimiento.
    
3- ¿Qué propiedades del archivo vercel.json son necesarias para que una aplicación Express funcione correctamente en Vercel?

    -"rewrites": Para redirigir todas las rutas a una función serverless.
    -"builds": Para definir el archivo de entrada (generalmente server.js).
    -"routes": Para configurar endpoints específicos si es necesario.

