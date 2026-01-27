---
tags:
  - Settings
  - Linux
  - Terminal
  - git
---
### Metadata
git config --global user.name “nombre” 
git config --global user.email “email@email.com”
### Generar SSH key
	ssh-keygen -t ed25519 -C “email@email.com” 
		 ed25519 es el algoritmo para la creación de las llaves
	
	ssh-agent -c | source # para fish
	eval "$(ssh-agent -s)" # bash
		Para encender el agente
		
	ssh-add ~/.ssh/id_ed25519 
		Le da la llave al agente
		
	ssh-add -l 
		Muestra las llaves activas
		
	cat ~/.ssh/id_ed25519.pub
		Muestra la llave pública
		
Lo anterior meterlo en GitHub > Ajustes > SSH Keys
ssh -T git@github.com

### Flujo Básico 
`git status`
`git add .`
`git commit -m "Notas actualizadas"`
`git push`
`git pull`
`git remote` 

### Clonar un repo 
Estar en la carpeta o crearla con un 
	`mkdir -p ~/Documents/Obsidian`
	`cd ~/Documents/Obsidian`
Clonarlo
	`git clone git@github.com:TU_USUARIO/mi-vault.git`

