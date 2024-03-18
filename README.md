# Segunda práctica de integración sobre tu ecommerce

### Aspectos a incluir

- Crear un modelo User el cual contará con los campos:

```
first_name:String,
last_name:String,
email:String (único)
age:Number,
password:String(Hash)
cart:Id (con referencia a Carts)
role:String(default:’user’)
```

- Desarrollar las estrategias de Passport para que funcionen con este modelo de usuarios.

- Modificar el sistema de login del usuario para poder trabajar con session o con jwt (a tu elección).

- Agregar al router /api/sessions/ la ruta /current, la cual utilizará el modelo de sesión que estés utilizando, para poder devolver en una respuesta el usuario actual.