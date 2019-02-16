# Vitalik Buterin descarta rumores nueva característica de Constantinopla permite el vector de ataque ...

###### 2019-02-16 09:02

El cofundador de Ethereum (ETH) Vitalik Buterin y otros desarrolladores principales han rechazado las acusaciones de que una nueva característica de creación de contrato inteligente que se lanzará en el próximo tenedor duro de Constantinopla tendrá implicaciones de seguridad negativas.

La característica en cuestión se denomina "Create2" — designada como propuesta de mejora de Ethereum (EIP) EIP-1014 — y está destinada a permitir interacciones con un contrato que aún no existe en la cadena de bloques, específicamente, "direcciones que aún no existen en se puede confiar en que posiblemente eventualmente contenga código ".

Varios ETH Devs había expresado preocupaciones que Create2 podría introducir un vector de ataque potencialmente serio a la red, dado la implicación que los contratos elegantes podrían supuestamente ser codificados para cambiar su dirección después de ser desplegado.

En una discusión de este y otros comentarios, dev Jeff Coleman subrayó que "una de las cosas que es contra-intuitiva acerca de Create2 es que teóricamente las reasignaciones pueden cambiar el código de byte del contrato, porque la dirección es sólo un compromiso con el código init.

Coleman enfatizó que aquellos que buscan auditar el código de otros necesitan mirar hacia fuera para potencialmente "fenómenos extraños \ [... \] especialmente si combinas Create2 con Create1, porque este último tiene una suposición muy débil alrededor de la identidad de la dirección lo que el nonce es."

Así que si llegamos al lugar donde Create2 es estándar, deshacerse de autodestrucción por completo \ [... \] podríamos tirar esta idea de un contrato nonce. "

Al igual que Coleman, Vitalik Buterin discutió Create2 con respecto a una hoja de ruta a largo plazo, diciendo: "la única cosa que debemos tener en cuenta es más para el futuro, al pensar en los alquileres y la eliminación; esa es una manera que puede conducir a que los contratos estén en un estado para no estar en un estado sin una operación de autodestrucción \ [... \].

[Original source](https://cointelegraph.com/news/vitalik-buterin-dismisses-rumors-new-constantinople-feature-allows-attack-vector)

![stats](https://c.statcounter.com/11760860/0/a89fa40b/1/ "stats")