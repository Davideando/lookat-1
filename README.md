# Look-At

Aquest projecte consisteix en construir un robot capaç de seguir una cara.

## Simulació en rviz

Per a executar la simulació és necessari obrir un terminal i escriure la següent comanda:

```shell 
$ roslaunch lookat_description display.launch
```

S'obrirá el programa rviz i una finestra petita que ens permetrá moure les joints.

## Robot real

Per a fer funcionar el robot cal fer el segent:

1. Compilar i carregar el codi al Arduino fent servir Arduino IDE. Trobareu el codi a lookat/lookat/lookat_control/Arduino/LookAt_control_Arduino/

2. Executar el fitxer launch: 

```shell 
$ roslaunch lookat main.launch
```

