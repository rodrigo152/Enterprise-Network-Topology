# Enterprise Network Topology (NOC) - Cisco Packet Tracer

## Descripción del Proyecto
Este repositorio contiene el diseño, configuración y simulación de una arquitectura de red corporativa segura desarrollada en **Cisco Packet Tracer**. El proyecto emula un entorno NOC (Network Operations Center) aplicando segmentación lógica, protocolos de enrutamiento dinámico, políticas de seguridad perimetral y monitoreo centralizado.

## Tecnologías y Protocolos Implementados
* **Simulador:** Cisco Packet Tracer
* **Enrutamiento:** RIPv2
* **Capa 2:** VLANs, Trunking (802.1Q)
* **Seguridad (AAA):** Servidor RADIUS para autenticación centralizada y accesos por SSH.
* **Seguridad Perimetral:** Access Control Lists (ACLs) extendidas para mitigar ataques DoS (Ping Flood) y restringir tráfico entre redes.
* **Monitoreo:** SNMP y servidor Syslog para captura de eventos críticos de la red en tiempo real.

## Características Principales (Laboratorio de 12 pasos)
1. **Diseño de Topología:** Conexión WAN entre routers principales y distribución hacia switches multicapa.
2. **Segmentación:** Creación de VLANs separadas para Administración, Servidores y Usuarios.
3. **Control de Acceso:** Restricción de tráfico inter-VLAN (ej. VLAN 20 bloqueada hacia VLAN 10).
4. **Hardening de Dispositivos:** Configuración de credenciales encriptadas y accesos remotos seguros por SSH.
5. **Mitigación de Amenazas:** Implementación de ACLs perimetrales que interceptan y bloquean ataques de denegación de servicio (Destination Host Unreachable).

## Evidencias de Configuración y Mitigación

<img width="725" height="694" alt="Captura de pantalla 2026-09-22 211948" src="https://github.com/user-attachments/assets/f666177a-baec-4fd9-8f17-49532ea2359a" />
<img width="844" height="757" alt="Captura de pantalla 2026-09-21 095546" src="https://github.com/user-attachments/assets/51f045a9-a521-4e91-9000-d210e40ce19b" />


## Autor
**Rodrigo Huarcaya Berrios**
*Estudiante de Ingeniería de Software | Técnico en Desarrollo de Software*
