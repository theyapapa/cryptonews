# Investigadores descubren la amenaza de la minería criptográfica de máquinas virtuales 'inusuales' ...

###### 2019-06-24 04:06

La empresa de ciberseguridad ESET ha detectado lo que describe como un minero de criomoneda inusual y persistente distribuido para macOS y Windows desde agosto de 2018.

Según ESET, el nuevo malware, apodado "LoudMiner", utiliza software de virtualización — VirtualBox en Windows y QEMU en macOS — para extraer cripto en una máquina virtual Tiny Core Linux, con lo que tiene el potencial de infectar computadoras a través de múltiples sistemas operativos.

El minero en sí utiliza XMRig - un software de código abierto utilizado para la minería de la privacidad centrada en altcoin monero (XMR) - y una piscina minera, por lo que supuestamente frustrar los intentos de los investigadores para volver a realizar transacciones.

La investigación reveló que tanto para macOS como para Windows, el minero opera dentro de aplicaciones pirateadas, que se agrupan junto con software de virtualización, una imagen de Linux y archivos adicionales.

ESET señala que el minero se dirige a aplicaciones cuyos propósitos están relacionados con la producción de audio, que generalmente se ejecutan en computadoras con una potencia de procesamiento robusta y donde el alto consumo de CPU, en este caso causado por la minería criptográfica sigilosa, podría no golpear a los usuarios como Sospechoso.

ESET ha identificado tres cepas del minero dirigidas a sistemas macOS, y sólo una para Windows hasta ahora.

Las conexiones de red a nombres de dominio inusuales, debido a scripts dentro de la máquina virtual que se comunican con el servidor C&C para actualizar la configuración del minero, son otro sorteo, añaden los investigadores.

[Original source](https://cointelegraph.com/news/researchers-uncover-threat-of-unusual-virtual-machine-crypto-mining)

![stats](https://c.statcounter.com/11760860/0/a89fa40b/1/ "stats")