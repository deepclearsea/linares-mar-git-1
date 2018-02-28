# Práctica GIT

### Linares Gómez, Mar

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque ese comando deshace el commit y lo que hay en el Working copy

--

**2. ¿Qué comando utilizaste en el paso 12? ¿Por qué?**

`git reset + numero identificador de la acción` 

Para rehacer el commit, la etiqueta la consulte mirando el historial con el comando `git reflog`

--

**3. El merge del paso 13, ¿Causó algún conflicto?¿Por qué?**

No causó conflicto. Apareció el mensaje "already up to date" porque no se modifica la rama master.

--

**4. El merge del paso 19, ¿Causó algún conflicto?¿Por qué?**

La consola me ha pedido hacer un commit, ya que htmlify la hemos creado desde master y no desde styled, por lo tanto ninguna contenia a la otra. Pero una vez hecho el merge funcionó. 

--

**5. El merge del paso 21, ¿Causó algún conflicto?¿Por qué?**

Apparentemente no ha habido conflicto.

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git log --graph` 

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

En este caso, sí. Porque desde donde estamos, al crear title desde master, no se formo una estructura con varios caminos hacia los que continuar, es decir no había que unir title con otras ramas.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git reset --hard HEAD~1` 

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title` 

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog`para ver todos los commits, y `git reset + numero identificador`para volver al merge.


--

**12. ¿Qué comando o comandos usaste en el paso 32?**

`git reset + numero identificador`

--

**13. ¿Qué comando o comandos usaste en el punto 33?**

`git reset + numero identificador`


