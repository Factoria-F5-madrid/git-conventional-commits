# Conventional Commits
Aunque con un simple mensaje descriptivo basta para realizar un buen commit, está bien ir un paso más allá y sumarse a las convenciones para unificar buenas prácticas a la hora de hacer nuestros commits:


[Documentación Oficial📖](https://www.conventionalcommits.org/es/v1.0.0/)

¿Cómo hacer commits siguiendo la convención?

Para hacer tu commit, tus mensajes deben estár formados por estas tres partes

```bash
<tipo de commit> (donde hemos trabajado): <descripción de lo que hemos hecho>
```

 - 👉**Tipo de commit**
(  hay más pero estos son los más utilizados. )

1. **fix:** un commit de *tipo* `fix` **corrige un error** en la base del código
2. **feat:** un commit de *tipo* `feat` introduce una **nueva funcionalidad** en la base del código 
3. **docs:** **actualizaciones de documentos** , un claro ejemplo es el README



 - 👉 **(donde hemos trabajado)**

El área del proyecto donde estamos trabajando:

puede ser algo genérico como `backend`

hasta algo más concreto como el nombre de una carpeta `Models`

depende de lo grande sea el proyecto podremos ser más o menos específicos

- 👉 **<descripción de lo que hemos hecho>**

resumir en una línea lo que acabamos de hacer

`update-foreingkey-userModel`

Ejemplo

```bash
git commit -m"fix(backend):update-foreingkey-userModel"
```

recuerda el esquema: tipo de commit:(dónde hemos trabajado):descripción de lo que hemos hecho

+info [https://carlosazaustre.es/conventional-commits](https://carlosazaustre.es/conventional-commits)

+info [artículo midudev sobre conventional commits](https://midu.dev/buenas-practicas-escribir-commits-git/)
