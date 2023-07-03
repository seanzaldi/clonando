# clonando
Repositorio para pruebas GIT del curso Sr. Programmer - Albert Capacitacion Digital

1) Prueba con Visual Code. Staging 1.
2) Prueba con Visual Code. Agrego nueva modificacion al Staging (2) y armo commit.
3) Los casos anteriores no funcionaron desde VSC, lo hice desde Git Bash. Intendo nuevamente desde VSC. Se configuro que use SSH en vez de HTTP.
4) Continuo probando si puedo hacer los commits desde VSC. Logre hacerlo fucionar pero tengo que iniciar "git bash" y desde dentro hacer "code" (abrir VSC desde alli). Ahora estoy probando con "start-ssh-agent" desde la terminal de windows para luego abrir VSC normalmente. veremos si funciona.
5) El comit 902411a (anterior) funciono con el SSH-AGENT nativo de Windows 10 (Open SSH). Se creo una variable de entorno "GIT-SSH". Se agreg la private key al agente mediante SSH-ADD y se lanzo el VSC inmediatamente desde la misma terminal (como en Git bash). Faltaria probar de Lanzar VSC no de la misma terminal para comprobar si la variable de entorno funciona correctamente. 
6) Tengo la terminal (CMD) cerrada, Agent SSH ejecutandose como proceso con la privada cargada. Probando VSC si funciona correctamente. 
7) Este "commit", a diferencia de los anteriores va a ser desde "git bash".