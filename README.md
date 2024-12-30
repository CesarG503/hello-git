### Anotaciones de las pranticas de git y github

# Comandos básicos de terminal  
- `ls`: Muestra el contenido del directorio actual.  
- `cd <nombre_directorio>`: Navega a otro directorio.  
- `cd ..`: Retrocede al directorio anterior.  
- `pwd`: Muestra la ruta actual en la que te encuentras.  
- `mkdir <nombre_carpeta>`: Crea una nueva carpeta.  
- `touch <nombre_archivo>`: Crea un archivo con el nombre y extensión especificados.  

---

# Iniciar y gestionar repositorios con Git  
## 1. Inicializar un repositorio  
- `git init`: Inicia un nuevo repositorio de Git en el directorio actual.  

## 2. Ver estado y cambios  
- `git status`: Muestra el estado actual del repositorio.  
- `git diff`: Muestra los cambios que aún no han sido agregados.  

## 3. Cambiar nombre de la rama principal  
- `git branch -m main`: Cambia el nombre de la rama actual a "main".  

## 4. Agregar y guardar cambios  
- `git add <archivo>`: Agrega un archivo específico.  
- `git add .` o `git add *`: Agrega todos los archivos.  
- `git commit -m "<mensaje>"`: Guarda los cambios con un mensaje descriptivo.  

## 5. Ver historial de commits  
- `git log`: Muestra el historial de commits.  
- `git log --graph`: Muestra el historial de manera gráfica y cronológica.  
- `git log --graph --decorate --all --oneline`: Visualización simplificada de todo el historial.  

---

# Ramas en Git  
## 1. Crear y gestionar ramas  
- `git branch <nombre_rama>`: Crea una nueva rama.  
- `git switch <nombre_rama>`: Cambia a la rama especificada.  
- `git branch -d <nombre_rama>`: Elimina una rama.  

## 2. Fusionar ramas  
- `git merge <nombre_rama>`: Fusiona la rama especificada con la actual.  

---

# Configurar alias personalizados  
- `git config --global alias.tree "git log --graph --decorate --all --oneline"`: Crea un alias para ver el historial en formato gráfico y resumido.  

---

# Gestión de cambios con Git Stash  
- `git stash`: Guarda cambios temporales sin comprometerlos.  
- `git stash list`: Muestra los cambios guardados en el stash.  
- `git stash pop`: Recupera los cambios guardados.  
- `git stash drop`: Elimina cambios guardados en el stash.  

---

# Trabajar con repositorios remotos  
## 1. Conectar a un repositorio remoto  
- `git remote add origin <url_del_repositorio>`: Enlaza un repositorio remoto.  

## 2. Subir cambios al repositorio remoto  
- `git push origin main`: Envía los cambios a la rama "main".  

## 3. Traer cambios desde el repositorio remoto  
- `git fetch`: Descarga información del repositorio remoto.  
- `git pull origin main`: Sincroniza el repositorio local con el remoto.  

## 4. Clonar un repositorio  
- `git clone <url_del_repositorio>`: Descarga una copia completa de un repositorio remoto.  

---

# Resolución de conflictos y contribuciones  
## Fork y pull request  
- Realiza un fork de un repositorio para trabajar en una copia sin afectar el original.  
- Usa un pull request para proponer cambios al repositorio original.  

## Resolución de conflictos  
- Durante un merge o pull request, resuelve conflictos manualmente y guarda los cambios.  

---

# Otros comandos útiles de Git  
- `git checkout <commit_id>`: Muestra el contenido de un commit específico.  
- `git checkout HEAD`: Restaura un commit como principal.  
- `git reset`: Regresa al commit principal de la rama.  
- `git reset --hard <commit_id>`: Elimina todos los cambios posteriores al commit especificado.  
- `git tag <nombre_etiqueta>`: Crea una etiqueta en el commit actual.  

---

# Investigación adicional  
- **Git Flow**: Aprende cómo usar esta metodología para gestionar ramas y versiones en proyectos colaborativos.  
- **Markdown en GitHub**: Descubre cómo documentar proyectos eficientemente.  
- **Comandos avanzados**: Explorar `git cherry-pick`, `git rebase` y otros comandos avanzados.  

