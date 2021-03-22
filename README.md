# Attenzione! Leggi prima di iniziare!

La nuova versione dell'Hacklog prevede un nuovo modo per mostrare i comandi da utente normale e da utente root.

---

Ogni riga di terminale può iniziare con $ (utente normale) o # (utente root o superadmin).
Da utente normale la linea del terminale si presenterà all'incirca in questo modo:
```
[username]@[domain]:~$
```
Da utente root la linea del terminale si presenterà all'incirca in questo modo:
```
root@[domain]:/#
```
Dunque, se vedi un comando così scritto:
```
# nano /etc/hosts
```
Significa che dovrai essere utente root per lanciarlo.
Ricorda quindi che puoi sempre elevare i tuoi permessi ad utente root lanciando:
```
$ su
```
quindi inserendo la password di root scelta in fase di installazione del Sistema Operativo. Da lì in poi, lancia tutti i comandi che vuoi!