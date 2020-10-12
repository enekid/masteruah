## Básico

En el trabajo uso git a diario, así que algunos de los puntos no los puedo realizar de nuevo.

Usuario GitHub: [enekid](https://github.com/enekid)

La configuración de usuario y email la realizo en el siguiente ejercicio de manera local.

![GitHub Desktop](/screenshots/github-desktop.png?raw=true)

## Medio. Ejercicios de Git, GitHub y Markdown

### Repositorio masteruah

https://github.com/enekid/masteruah

Creado vacío. No lo clono porque lo iniciaré en local.

### Init y configuración

```bash
git init
git config user.name "Eneko Lakasta"
git config user.email "enekolakasta@gmail.com"
```

### README.md, commit y push

```bash
git add README.md
git commit -m "commit inicial"
git branch -M main
git remote add origin git@github.com:enekid/masteruah.git
git push -u origin main
```

### Ignorar archivos

Editar `.gitignore`

```
privado.txt
privada/
```

### Añadir fichero 1.txt

```bash
git add 1.txt
```

### Crear el tag v0.1

```bash
git tag v0.1
```

### Subir cambios

```bash
git push origin main
git push origin v0.1
```

### Cuenta GitHub

![Foto](/screenshots/github-avatar.png?raw=true)

![2FA](/screenshots/github-2FA.png?raw=true)
