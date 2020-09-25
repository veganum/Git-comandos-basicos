# COMANDOS BASICOS PARA GIT Y GITHUB

POR JOSE FRANCO NIETO 

**version 1.0.0**


# Esenciales
---

- Crear repositorio: git init
- Borrar archivos de git : rm -rf .git


- Agrega a la Staging Area : git add .
- Commitear: git commit -m "primer commit"
- Subir cambios de local a remoto : git push
- Actualizar(de remoto a local): git pull

# Ramas
---
- Cambiar de rama: git checkout
- Crear rama local: git checkout -b nombreRama
- Crear rama remota:git push -u origin nombreRama
- Renombrar rama: git branch -m viejaRama nuevaRama


- Actualizar rama: git pull origin formacionOct19

# Ver estados de git
---
- Ver commits: git log
- Muestra en una linea los commit: git log --oneline
- Muestra commit de forma grafica: git log --oneline --decorate --all –graph
				 git log --pretty=format:"%h %s" --graph

- Ir a un commit especifico: Git reset --hard 207570e 

- Clonar repositorio remoto: git clone {enlace repositorio}

- Ver ramas remotas : git branch -vv

# Revisión de cambios en código
---

- Ver cambios hechos en el codigo: git status
				 git status –s
- Agregar cambios: git add <file>
- Rechazar cambios y dejarlo como estaba: git restore <file>
			  PULL REQUEST
- Mezclar rama actual con la que queramos: git checkout master
			                 gigit merge nuevafuncionalidad



- revisar cambios antes de fusionar : git diff <source_branch	> <target_branch>

# Eliminar
---
- rm -rf .git :eliminar repositorio

# Notacion para escribir en el readme.md
---
- # nombre : Para poner mayusculas(titulo)
- ## License & Copyright :Copiright
- © Jose Franco Nieto:Autor	
- ** **version 1.0** ** : Versión
- -: un punto

