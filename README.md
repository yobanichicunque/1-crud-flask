# 1-CRUD_FLASK

## Flujo de trabajo:

1. Registro de Empresas (1 Abril)
    - Información de la empresa:
        Nombre
        Descripcion
        Imagen
        Celular
        Direccion
        Email
        Contraseña
    - Email de bienvenida y confirmación
    - Reenvio del email de confirmación
    - Validación de datos:
        Email no se encuentre registrado
        Contraseña cumpla unas politicas
            - Minimo 8 caracteres
            - Tenga una mayuscula
            - Tenga un número
            - Tenga un caracter especial
    - Encriptación de la contraseña

2. Inicio de sesión (8 Abril)
    - Formulario de Inicio
        - Email
        - Contraseña
    - Validación:
        - Usuario este confirmado

3. Reestablecer la contraseña
    - Formulario de Reestablecer la contraseña
        - Email
    - Correo con instructivo para recuperar la contraseña

4. Productos
    - Listado
    - Creación y edición: 
        Nombre
        Descripción
        Precio
        Estado
        Imagen
    - Eliminación

5. Perfil
    - Actualizar Información de la empresa:
        Nombre
        Descripcion
        Imagen
        Celular
        Direccion
        Email
        Contraseña

6. Carta virtual
    - Mostrar los productos activos de la empresa
    - Mostrar la Información basica de la empresa
    - Carrito compras
        - Agregar mas de un productos
        - Cambiar cantidades
        - Agregar una observacion general
    - Datos del consumidor
        - Nombre
        - Direccion
        - Celular
    - Notificación via WP a la empresa

7. Extras obligatorios
    - Validaciones en el servidor
    - Retroalimentaciones
    - Formularios sin perder informacion
    - Diseño
    - Arquitectura MVC
        - Modelo => SQL
        - Vista => templates
        - Controlador => 
    - Heroku => Maquina virtual

