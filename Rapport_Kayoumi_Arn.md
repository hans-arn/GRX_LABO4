# Rapport GRX Labo 4

> Doran Kayoumi, Jérôme Arn

# Objectif 1 : Construire le réseau et réaliser la configuration de base des équipements.

> 4 Attribuez une adresse IP fixe à l’interface opérationnelle ens33.

````sh
# Avec la commande nmtui dans Edit a connection > ens33
nmtui
# puis après la configuration 
service network restart
````

![](img/Part1/3.png)

![](img/Part1/ip_a.jpg)

> Les trois nœuds cibles sont « pingables » depuis la station Nagios

Dans l'interface web on peut déjà vérifier que NAGIOS reconnaît toutes les machines grâce à l'auto discovery. Pour le réseau **192.168.1.0/24**.

![](./img/Part1/2.png)

![](./img/Part1/1.png)

Et dans la capture ci-dessous on peut voir que l'on faire un ping sur le serveur ubuntu, le routeur et la machine WINB. 

![](img/Part1/5.PNG)

# Objectif 2 : Configurer les nœuds cibles

## Routeur 

### SNMP + traps

### Syslog

## Ubuntu SRV

### Syslog

## Windows 10 B

### WMI


# Objectif 3 : Auto découverte d’un réseau 

> Capturez le trafic (Wireshark) sur l’interface ens33 de gestion de votre VM Nagios.



> Découvrez la topologie de votre réseau à l’aide de la fonction d’auto-découverte.

Dans l'interface web on peut déjà vérifier que NAGIOS reconnaît toutes les machines grâce à l'auto discovery. Pour le réseau **192.168.1.0/24**.

![](./img/Part1/2.png)

Pour le réseau **192.168.2.0/24**.![](./img/Part1/1.png)

> Pour chaque nœud découvert, montrez les caractéristiques découvertes par Nagios.

Pour le réseau **192.168.1.0/24**.

![](img/Part3/9a.jpg)

Pour le réseau **192.168.2.0/24**.

![](img/Part3/9b.jpg)

> A l’aide de la capture réalisée au point 7, expliquez la stratégie de découverte initiée par Nagios.



> A l’aide de l’attribut « parent », hiérarchisez la carte topologique Hypermap.




# Objectif 4 : Affinage de l’inventaire des nœuds cibles

