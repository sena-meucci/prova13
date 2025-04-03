# Git - Working with Remotes
- I repository remoti sono versioni del tuo progetto che sono ospitate su Internet
- La collaborazione con altri programmatori implica la gestioni di questi repository remoti e il push e il pull di dati
  
Fondamentale è saper **sincronizzare il nostro lavoro locale con un repository remoto**

*comandi principali:*

```git remote -v``` --> visualizza i server remoti collegati al nostro repository
### Aggiungere o rimuovere un repository remoto
```git remote add <name> <url>```
### Caricare il lavoro locale sul repository remoto
```git push <remote> <local-branch>```
### Aggiornare la copia locale del repository, allineandola con la versione remota
```git pull <remote> <local-branch>```
