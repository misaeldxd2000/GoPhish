# KAZER (CAMPAÑA DE PHISHING)
Repositorio final de proyecto para la clase de automatizacion de redes digitales.

Equipo: Misael Alejandro Haro Marquez y Raul Jesus Vasquez Garcia

10D
# Phishing Automation Platform

Plataforma completa para campañas de phishing simuladas con fines educativos. Automatiza el envío, monitoreo y análisis de campañas usando Docker, Jenkins, Zabbix.

## Arquitectura del Proyecto

La infraestructura se compone de los siguientes servicios orquestados con Docker:

*   **GoPhish**: Servidor principal para crear y gestionar campañas de phishing.
*   **Jenkins**: Automatiza la creación de campañas y el pipeline de trabajo.
*   **Zabbix**: Monitorea las métricas clave (clics, credenciales) y genera alertas.
*   **Portainer**: Interfaz gráfica para la gestión de contenedores Docker.


## Accesos Rápidos a los Servicios

| Servicio | URL | Username | Password |
|----------|-----|----------|----------|
| GoPhish | https://localhost:3333 | admin | Phishing2026! |
| Jenkins | http://localhost:8081 | admin | Jenkins |
| Zabbix | http://localhost:8090 | Admin | zabbix |
| Portainer | https://localhost:9443 | admin | Blackmisael1@ |
