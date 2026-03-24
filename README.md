# Simulacion-de-Red-en-Cisco-Packet-Tracer
Simulación de Red en Cisco Packet Tracer

En resumen
Se diseñó e implementó en equipo una red empresarial segmentada con múltiples subredes, se configuraron servicios FTP, DNS y HTTP, se analizaron amenazas de seguridad, se propusieron medidas de protección y se validó la conectividad mediante simulaciones en Cisco Packet Tracer.

Descripción Técnica del Proyecto — Gestión de Redes

En este proyecto se diseñó e implementó una infraestructura de red segmentada compuesta por seis subredes independientes interconectadas a una red central, utilizando direccionamiento privado IPv4 bajo el esquema 192.168.x.0/24. La comunicación entre redes se estableció con el objetivo de permitir el intercambio de datos entre sucursales, incluyendo transferencia de archivos y comunicación interna.

Implementación de Servicios de Red

Como equipo, se configuró un servidor FTP con autenticación básica mediante credenciales predeterminadas. Este servidor permitió la transferencia de archivos entre las distintas redes mediante comandos como:

put para subida de archivos
get para descarga de archivos
Conexión mediante ftp 192.168.1.3

Además, se integró un servicio DNS junto con HTTP para alojar una página web interna accesible mediante el dominio tecmi.com, simulando un entorno corporativo con servicios centralizados.

Análisis de Seguridad

Se realizó en equipo la identificación de amenazas comunes dentro de la red, incluyendo:

Acceso no autorizado
Phishing
Ataques DDoS
Explotación de vulnerabilidades
Malware

También se evaluaron posibles vectores de ataque como:

Man-in-the-Middle
Fuerza bruta
Vulnerabilidades en dispositivos de red

Y se propusieron medidas de mitigación como cifrado TLS, autenticación fuerte y políticas de contraseñas seguras.

Implementación de Medidas de Seguridad

Como parte del proyecto, se propusieron mecanismos de seguridad como:

Configuración de direcciones MAC estáticas
Segmentación de red mediante VLANs
Uso de cifrado AES-256 y TLS
Monitoreo con IDS (Snort / Suricata)
Políticas de seguridad y capacitación de usuarios
Mejora de Confiabilidad de Red

También se diseñaron estrategias para aumentar la disponibilidad y rendimiento:

Redundancia de enlaces
Control de acceso basado en roles (RBAC)
Sistema de monitoreo y alertas
Backups y recuperación ante desastres
Implementación de QoS para priorización de tráfico
