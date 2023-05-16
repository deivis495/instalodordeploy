<h1>REQUERIMIENTOS BASICOS</h1>

UBUNTU SERVER 20.04 (LIMPIO)
8GB RAM MINIMO
50GB DISCO-------

<h2>MANUAL PRIMERA INSTALACION</h2>

crear y direccionar 1 nombres de dominio para Backend y uno para Frontdend o sub dominios apuntando a el ip del servidor.

Ejemplo: 

front1.demo.com

back1.demo.com

ir copiando y pegando por linea 

```bash
sudo su
```

<h3>COMANDOS PARA ACTUALIZAR UBUNTU SERVER 20.04</h3>
si o yes a todo.

```bash
apt update
```
```bash
apt upgrade
```

(link admin para instalacion de la primera instancia ):
 
```bash
sudo apt install -y git && git clone https://github.com/deivis495/instalodordeploy.git && sudo chmod -R 777 instalodordeploy && cd instalodordeploy&& sudo ./install_primaria
```



primera pantalla opcion (0)

0 instalar unichat 

clave base datos: abc123456

colocar sin caracteres especiales ($%&/"!@?¡) preferiblemente minuscula*

Codigo de repositorio a instalar
```bash
https://github.com/deivis495/codigo.git
```
 
Nombre de empresa: 

EJEMPLO: EMPRESA CHAT

*numero de conexiones: 

(numero de conexiones requerida para lineas de Whatsapp)

*numero de cuentas de usuarios:

(numero de usuarios que pueden registrarse)

*ingrese el dominio front: el dominio para frontend registrado 

front1.demo.com;

*ingrese el dominio back: el dominio para backend registrado

back1.demo.com;

Cada instancia nueva debe realizarse con puertos distintos

*puerto para front: desde 3000 al 3999 escojer

3000

*puerto para back: desde 4000 a 4999 escojer

4000

*puerto para redisk : desde 5000 a 5999

5000

dejar que todo el proceso se realizara solo:







<h2>MANUAL INSTALACIONES SECUNDARIAS</h2>


crear y direccionar 1 nombres de dominio para Backend y uno para frondend o sub dominios apuntando a el ip del servidor.

ejemplo: 

frontsegundainstancia.demo.com

backsegundainstancia.demo.com

link de instancias: 

codigo de repositorio a instalar
```bash
cd && rm -rf instalodordeploy && git clone https://github.com/deivis495/instalodordeploy.git && sudo chmod -R 777 instalodordeploy && cd instalodordeploy && sudo ./install_instancia

```


primera pantalla opcion (0)

0 instalar unichat 

clave base datos: segunda123456

colocar sin caracteres especiales ($%&/"!@?¡) preferiblemente minuscula.

codigo de repositorio a instalar
```bash
https://github.com/deivis495/codigo.git
``` 
*Nombre de empresa: 

EJEMPLO: segundainstancia

*numero de conexiones:

(numero de conexiones requerida para lineas de Whatsapp)

*numero de cuentas de usuarios:

(numero de usuarios que pueden registrarse)

*ingrese el dominio front: el dominio para frontend registrado 

frontsegundainstancia.demo.com

*ingrese el dominio back: el dominio para backend registrado

backsegundainstancia.demo.com

Cada instancia nueva debe realizarse con puertos distintos

*puerto para front: desde 3000 al 3999 escojer

3001

*puerto para back: desde 4000 a 4999 escojer

4001

*puerto para redisk : desde 5000 a 5999

5001

dejar que todo el proceso se realizara solo:


