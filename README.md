# Documentación Personal de Comandos en Terminal (Linux + Git)

## Autor: Iván Ramos de la Torre  
## Matrícula: 5072837  
## Universidad: Universidad Autónoma de Guadalajara  

Este documento reúne los comandos esenciales de Linux y Git que utilizo en mis proyectos, junto con ejemplos simples y salidas simuladas. Su objetivo es servirme como una guía rápida y práctica mientras trabajo en la terminal y refuerzo mis habilidades como desarrollador.

---
# Lectura y Edición de Archivos

## **echo**
Escribe texto en pantalla o dentro de un archivo. Ideal para crear archivos de forma rápida.

**Entrada:**
```
echo "Hola mundo" > saludo.txt
```

---

## **nano**
Abre un editor de texto simple dentro de la terminal. Perfecto para editar archivos de configuración.

**Entrada:**
```
nano config.ini
```

---

## **touch**
Crea un archivo vacío. Útil para iniciar rápidamente un archivo antes de editarlo.

**Entrada:**
```
touch app.py
```

---

## **grep**
Busca texto dentro de un archivo o salida. Excelente para revisar logs extensos.

**Entrada:**
```
grep "ERROR" sistema.log
```



# Git

## **git init**
Inicia un repositorio Git en un directorio. Activa el control de versiones.

**Entrada:**
```
git init
```

---

## **git add**
Añade archivos al área de staging. Se usa antes de hacer un commit.

**Entrada:**
```
git add .
```

---

## **git commit**
Guarda los cambios con un mensaje descriptivo. Es el corazón del historial de versiones.

**Entrada:**
```
git commit -m "Inicializando proyecto"
```

---

## **git push**
Envía los cambios al repositorio remoto. Permite sincronizar tu trabajo con GitHub o GitLab.

**Entrada:**
```
git push origin main
```

---
## **git pull**
Descarga y fusiona cambios del repositorio remoto.

**Entrada:**
```
git pull
```


# Administración del Sistema

## **sudo**
Ejecuta comandos con permisos de administrador. Es necesario para instalar software o modificar configuraciones críticas.

**Entrada:**
```
sudo systemctl restart nginx
```

---

## **apt update**
Actualiza la lista de paquetes disponibles en los repositorios instalados.

**Entrada:**
```
sudo apt update
```

---

## **apt install**
Instala programas desde los repositorios oficiales de Linux.

**Entrada:**
```
sudo apt install curl
```

---

## **ps**
Muestra procesos activos. Sirve para identificar programas que consumen recursos o procesos que se han quedado congelados.

**Entrada:**
```
ps
```



# Manipulación de Archivos

## **mv**
Sirve para mover o renombrar archivos. Es útil para organizar proyectos o reestructurar carpetas.

**Entrada:**
```
mv notas.txt documentos/
```

---

## **rm**
Elimina archivos del sistema. Debe usarse con cuidado, ya que no pasa por la papelera.

**Entrada:**
```
rm viejo.log
```

---

## **chmod**
Cambia los permisos de un archivo. Permite dar permisos de ejecución, lectura o escritura.

**Entrada:**
```
chmod 755 servidor.sh
```
**Salida:**
```
-rwxr-xr-x 1 ivan ivan 120 feb 20 10:31 servidor.sh
```

---

## **mkdir**
Crea un nuevo directorio. Útil para empezar módulos, proyectos o separar archivos.

**Entrada:**
```
mkdir backend
```



# Navegación y Sistema

## **pwd**
Muestra la ruta completa del directorio actual. Útil para orientarte cuando trabajas entre muchas carpetas.

**Entrada:**
```
pwd
```
**Salida:**
```
/home/ivan/dev
```

---

## **clear**
Limpia la pantalla de la terminal para mantener el espacio de trabajo ordenado, especialmente después de mucha salida de texto.

**Entrada:**
```
clear
```

---

## **cd**
Permite cambiar entre directorios. Es uno de los comandos más usados para desplazarte dentro del sistema.

**Entrada:**
```
cd proyectos
pwd
```
**Salida:**
```
/home/ivan/proyectos
```

---

## **ls**
Lista los archivos presentes en un directorio. Ideal para visualizar qué tienes disponible.

**Entrada:**
```
ls
```
**Salida:**
```
api  notas.txt  imagenes  script.sh
```




# Conclusión  
Esta recopilación me permite consultar de manera sencilla los comandos más usados en Linux y Git, facilitando mi trabajo diario y ayudándome a mejorar mi dominio de la terminal. Seguiré ampliando este documento conforme avance en mi aprendizaje.

---

**Autor:** Iván Ramos  
**Año:** 2025
