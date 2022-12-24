# login transparent

Realización de un login en el centro transparente con una imagen de fondo, el cual al intentar hacer *login* sin llenar el *Username* y *password* no te deja ingresar.

Tambien se hace uso de Js en los apartados de *Forgot password?* y *Sing up*.

---

[link](https://hydr0bius.github.io/login-transparent/) de la página.

![imagen](image/pexels-pixabay-301614.jpg)

Photo by Pixabay: https://www.pexels.com/photo/pagoda-in-gray-scale-shot-301614/

---

Para el Js se realizo lo siguiente:

```Js
const contra = document.getElementById("olvidado");
contra.addEventListener("click", olvido);

function olvido(){
    alert("Ya no se puede hacer nada...")
}
const boton = document.getElementById("button");
boton.addEventListener("click", alerta);

function alerta(){
    alert("No disponible")
}
```
