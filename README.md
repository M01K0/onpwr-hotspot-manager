#Admin. mikrotik hotspot users.

 - soft para habilitar o deshabilitar usuarios hotspot ya creados en routers mikrotik.
 - Realizado en NodeJS 4.5 + AngularJS 1.5.8 + ngMaterial
 
##REQUISITOS
- NodeJs 4.5
- RouterOS 6.x

##Como instalar
- Instalar Node.js 4.x.x

- Instalar dependencias con los siguientes comandos:

```
cd node_modules
cd mikronode
npm install
cd ..
cd ..
npm install
```


- Editar config.js con parametros del router, interface con AMARRE IP, y usuario de hotspot que puede administrar el sistema.

Iniciar la aplicación con 
```
npm start
```

Compatible con todos los sistemas operativos

##Características

- Habilitar o deshabilitar a usuarios hotspot ya creados en mikrotik.
- Ver cantidad de dispositivos conectados por cada usuario.
- Cambiar contraseña usuario hotspot.
- Desloguear dispositivos conectados.
- Habilitar o deshabilitar a clientes mediante amarre ARP.
- Modificar Queues/Planes de velocidad asignadas a cada CLiente (determina queue mediante nombre para hotspot, y mediante address para ARP).

##Faltantes (TO-DO):
- Editar maximas conexiones de hotspot.
- Desloguear usuarios activos para el user al deshabilitarlo.
- Otros?.
