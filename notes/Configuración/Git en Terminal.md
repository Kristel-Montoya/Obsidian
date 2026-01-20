---
tags:
  - Settings
  - Linux
  - Terminal
---
# metadata
git config –global user.name “nombre” 
git config –global user.email “email@email.com”
# Generar SSH key
shh-keygen -t ed25519 -C “email@email.com” 
		 ed25519 es el algoritmo para la creación de las llaves
	
ssh-agent -c | source # para fish
eval "$(ssh-agent -s)" # bash
		Para encender el agente
		
ssh-add ~/.ssh/id_ed25519 
		Le da la llave al agente
		
ssh-add -I 
		Muestra las llaves activas
		
cat ~/.ssh/id_ed25519.pub
		Muestra la llave pública
# Lo anterior meterlo en GitHub > Ajustes > SSH Keys
ssh -T git@github.com