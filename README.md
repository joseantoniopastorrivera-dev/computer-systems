# 💻 Sistemas Informáticos

Operating systems, hardware, networks, and system administration coursework for 1st year of DAM (Desarrollo de Aplicaciones Multiplataforma) / Teoría, prácticas, redes, scripting en Bash, virtualización y administración de sistemas del módulo de Sistemas Informáticos impartido por Miguel Ángel Benito en el IES Isidra de Guzmán.

---

## 🗂️ Estructura del Repositorio

El repositorio está organizado de forma modular por evaluaciones y contenidos prácticos:

* **`1a-evaluacion/`**: Actividades 1 a 11 (iniciación, distribuciones, cableado, redes, primer servidor, subnetting) y primera red en Cisco Packet Tracer, más el resumen de teoría. Hardware, arquitectura de ordenadores, componentes, redes, cableado (UTP, FTP, STP, fibra), Wi-Fi (2.4 GHz y 5 GHz) y direccionamiento IP/Subnetting.
* **`2a-evaluacion/`**: Apuntes de comandos Bash y de servidores y DNS, chuleta de servidores y servicios (HTML), prácticas de `grep` y tuberías y el script de menú del examen. Administración de sistemas Linux, consola Bash, tuberías (`|`), filtros avanzados (`grep`, `awk`, `sort`, `wc`, `uniq`), permisos (octales), gestión de procesos (`ps aux`) y automatización mediante scripts (`.sh` y menús interactivos).
* **`3a-evaluacion/`**: Teoría del examen de la 3ª evaluación. Guías y configuraciones de servidores remotos, protocolos de acceso seguro (SSH), despliegue en la nube (AWS, IP elástica, Security Groups), servidores web (NGINX con wildcards y subdominios) y gestión de DNS.

---

## 📚 Resumen de Contenidos Técnicos

### 1. Hardware y Arquitectura (1ª Evaluación)
* **Modelo de Von Neumann**: Arquitectura de computación donde la memoria almacena datos e instrucciones en un espacio compartido, procesados secuencialmente por la CPU (Unidad de Control y ALU) a través de un sistema de buses.
* **Memorias**: 
  * *RAM*: Volátil y rápida, espacio de trabajo temporal.
  * *ROM*: No volátil, contiene el firmware de inicio (BIOS/UEFI).
  * *Caché*: Extremadamente rápida, situada cerca de la CPU para acelerar accesos frecuentes.
  * *Secundaria (HDD/SSD)*: No volátil, almacenamiento permanente.
* **Procesadores y Gráficas**: Funcionamiento basado en millones de transistores como interruptores electrónicos. Las GPU procesan datos en paralelo orientadas a gráficos e inteligencia artificial.
* **Redes y Conectividad**: 
  * *Cables de red*: UTP (sin blindaje), FTP (lámina general), STP (blindaje por par y global). Fibra óptica monomodo y multimodo.
  * *Wi-Fi*: Banda de 2.4 GHz (mayor alcance, más saturada) vs. Banda de 5 GHz (mayor velocidad, menos alcance).

### 2. Administración Linux y Scripting en Bash (2ª Evaluación)
* **Gestión de archivos y filtros**: Comandos esenciales (`ls`, `cd`, `mkdir`, `touch`, `rm`, `mv`) y procesamiento de texto en consola mediante tuberías (`|`) combinando `cat`, `grep`, `awk`, `sort`, `wc` y `uniq`.
* **Procesos**: Monitorización avanzada con `ps aux`, filtrado de columnas específicas y ordenación por consumo de CPU o memoria.
* **Permisos**: Gestión de usuarios, grupos y control de accesos mediante valores octales (lectura 4, escritura 2, ejecución 1) y comandos `chmod` / `chown`.
* **Automatización y Scripts (`.sh`)**: Creación de menús interactivos mediante bucles `while true`, sentencias condicionales `if-else`, validación de rutas y funciones modulares con Bash.

### 3. Servidores, Despliegue y Redes (Cloud & Web) (3ª Evaluación)
* **SSH (Puerto 22)**: Criptografía asimétrica mediante clave pública en el servidor (`~/.ssh/authorized_keys`) y clave privada en el cliente.
* **AWS & Seguridad**: Despliegue de instancias Ubuntu, uso de IP elástica para evitar rupturas de DNS tras reinicios, y configuración de *Security Groups* como cortafuegos.
* **NGINX**: Gestión de bloques de configuración en `/etc/nginx/sites-available/` y enlaces simbólicos en `/etc/nginx/sites-enabled/`. Implementación de expresiones regulares (Regex) para subdominios wildcard (`*`).
* **DNS**: Resolución de nombres mediante registros tipo `A` (IPv4), `AAAA` (IPv6), `CNAME` (alias), `MX` (correo) y comodines `wildcard`.

---

## 🛠️ Tecnologías y Herramientas
* **Sistemas Operativos**: Linux (Ubuntu Server / distribuciones de consola) y Windows.
* **Redes**: Protocolos TCP/IP, SSH, HTTP/HTTPS, DNS y direccionamiento IP.
* **Automatización**: Bash Scripting, GNU/Linux CLI, SFTP y SCP.
* **Web Servers**: NGINX y Certbot (SSL/TLS).
* **Cloud**: Amazon Web Services (AWS).

---
&copy; 2025-2026 José Antonio Pastor Rivera | IES Isidra de Guzmán (DAM)
