# KAZER (CAMPAÑA DE PHISHING)

Repositorio final de proyecto para la clase de automatizacion de redes digitales.

**Equipo:** Misael Alejandro Haro Marquez y Raul Jesus Vasquez Garcia  
**Grupo:** 10D

---

## Phishing Automation Platform

Plataforma completa para campañas de phishing simuladas con fines educativos. Automatiza el envio, monitoreo y analisis de campañas usando Docker, Jenkins, Zabbix.

---

## Arquitectura del Proyecto

La infraestructura se compone de los siguientes servicios orquestados con Docker:

| Servicio | Descripcion |
|----------|-------------|
| **GoPhish** | Servidor principal para crear y gestionar campañas de phishing |
| **Jenkins** | Automatiza la creacion de campañas y el pipeline de trabajo |
| **Zabbix** | Monitorea las metricas clave (clics, credenciales) y genera alertas |
| **Portainer** | Interfaz grafica para la gestion de contenedores Docker |

---

## Accesos Rapidos a los Servicios

| Servicio | URL | Username | Password |
|----------|-----|----------|----------|
| GoPhish | https://localhost:3333 | admin | Phishing2026! |
| Jenkins | http://localhost:8081 | admin | Jenkins |
| Zabbix | http://localhost:8090 | Admin | zabbix |
| Portainer | https://localhost:9443 | admin | Blackmisael1@ |

---

## Tecnologias Utilizadas

- Docker / Docker Compose
- GoPhish
- Jenkins
- Zabbix
- Portainer
- Ubuntu / WSL2

---

## Repositorio

https://github.com/misaeldxd2000/GoPhish
