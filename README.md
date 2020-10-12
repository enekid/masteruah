## Medio. Ejercicios de Git, GitHub y Markdown

```bash
git init
git config user.name "Eneko Lakasta"
git config user.email "enekolakasta@gmail.com"
```

Editar README.md

```bash
git add README.md
git commit -m "commit inicial"
git branch -M main
git remote add origin git@github.com:enekid/masteruah.git
git push -u origin main
```

### Ignorar archivos

editar `.gitignore`

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
