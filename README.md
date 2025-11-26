# Documentación Personal de Comandos en Terminal (Linux + Git)
## Autor: Iván Ramos de la Torre  
## Matrícula: 5072837  
## Universidad: Universidad Autónoma de Guadalajara

---

Este documento reúne los comandos esenciales de Linux y Git que utilizo en mis proyectos, junto con ejemplos simples y salidas simuladas. Su objetivo es servirme como una guía rápida y práctica mientras trabajo en la terminal y refuerzo mis habilidades como desarrollador.

---

# 🗂️ 1. Navegación y Sistema

## **pwd**
Muestra la ruta completa del directorio actual.

**Entrada:**
```
pwd
```
**Salida:**
```
/home/ivan/dev/projects
```

---

## **cd**
Permite moverme entre directorios.

**Entrada:**
```
cd documentos
pwd
```
**Salida:**
```
/home/ivan/documentos
```

---

## **ls**
Lista archivos y carpetas del directorio actual.

**Entrada:**
```
ls
```
**Salida:**
```
reportes  notas.md  imagenes  proyecto.py
```

---

## **clear**
Limpia la terminal.

---

## **whoami**
Muestra el usuario actual.

**Entrada:**
```
whoami
```
**Salida:**
```
ivan
```

---

# 📄 2. Creación, Lectura y Búsqueda de Archivos

## **echo**
Imprime texto o lo escribe en un archivo.

**Entrada:**
```
echo "Este semestre voy a sacar puro 10"
```
**Salida:**
```
Este semestre voy a sacar puro 10
```

---

## **nano**
Abre un editor en la terminal.

**Entrada:**
```
nano tareas.txt
```

---

## **touch**
Crea un archivo vacío.

**Entrada:**
```
touch practica1.txt
ls
```
**Salida:**
```
practica1.txt  notas.md  codigo  proyectos
```

---

## **cat**
Muestra el contenido de archivos.

**Entrada:**
```
cat tareas.txt
```
**Salida:**
```
Tareas pendientes:
- Terminar laboratorio de Linux
- Avanzar proyecto de Django
```

---

## **grep**
Busca texto dentro de un archivo.

**Entrada:**
```
grep "warning" build.log
```
**Salida:**
```
line 22: warning: unused variable ‘x’
line 89: warning: deprecated function
```

---

## **tree**
Muestra estructura de carpetas.

**Entrada:**
```
tree
```
**Salida:**
```
.
├── src
│   └── main.py
├── docs
│   └── readme.md
└── tests
```

---

# 🛠️ 3. Manipulación de Archivos y Permisos

## **mkdir**
Crea un directorio.

**Entrada:**
```
mkdir backend
ls
```
**Salida:**
```
backend  src  docs  notes.md
```

---

## **mv**
Mueve o renombra archivos.

**Entrada:**
```
mv notas.md docs/
ls docs
```
**Salida:**
```
readme.md  notas.md
```

---

## **rm**
Elimina archivos.

**Entrada:**
```
rm practica1.txt
```

---

## **chmod**
Cambia permisos de archivos.

**Entrada:**
```
chmod 755 deploy.sh
ls -l deploy.sh
```
**Salida:**
```
-rwxr-xr-x 1 ivan ivan 98 feb 15 14:22 deploy.sh
```

---

## **./ archivo**
Ejecuta un archivo.

**Entrada:**
```
./deploy.sh
```
**Salida:**
```
Despliegue completado exitosamente.
```

---

# ⚙️ 4. Administración del Sistema

## **sudo**
Ejecuta comandos como administrador.

**Entrada:**
```
sudo systemctl restart apache2
```

---

## **apt install**
Instala paquetes.

**Entrada:**
```
sudo apt install neofetch
```
**Salida:**
```
Descargando paquetes...
Instalación completa.
```

---

## **apt update**
Actualiza repositorios.

**Entrada:**
```
sudo apt update
```

---

## **apt upgrade**
Actualiza paquetes instalados.

**Entrada:**
```
sudo apt upgrade
```

---

## **ps**
Muestra procesos activos.

**Entrada:**
```
ps
```
**Salida:**
```
PID   TTY   TIME   CMD
1432  pts/0 00:00  bash
1901  pts/0 00:03  python3
2015  pts/0 00:00  ps
```

---

## **kill**
Termina un proceso.

**Entrada:**
```
kill 1901
```

---

## **man**
Abre manuales de comandos.

**Entrada:**
```
man mv
```

---

# 🔧 5. Comandos de Git

## **git config**
Configura nombre y correo global.

**Entrada:**
```
git config --global user.name "Ivan Ramos"
git config --global user.email "ivan@example.com"
```

---

## **git init**
Inicializa un repositorio.

**Entrada:**
```
git init
```
**Salida:**
```
Initialized empty Git repository in /home/ivan/dev/.git/
```

---

## **git add**
Envía archivos al área de staging.

**Entrada:**
```
git add .
```

---

## **git commit**
Guarda cambios en el historial.

**Entrada:**
```
git commit -m "Inicializando proyecto"
```
**Salida:**
```
[main 4b7a1d2] Inicializando proyecto
 2 files changed, 15 insertions(+)
```

---

## **git push**
Sube commits al repositorio remoto.

**Entrada:**
```
git push origin main
```
**Salida:**
```
Pushed to origin/main
```

---

## **git pull**
Descarga cambios del remoto.

**Entrada:**
```
git pull
```

---

# ✅ Conclusión  
Esta recopilación me permite consultar de manera sencilla los comandos más usados en Linux y Git, facilitando mi trabajo diario y ayudándome a mejorar mi dominio de la terminal. Seguiré ampliando este documento conforme avance en mi aprendizaje.

---

**Autor:** Iván Ramos de la Torre  
**Año:** 2025
