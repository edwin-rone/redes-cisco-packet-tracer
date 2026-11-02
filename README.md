# Redes de computadoras — Cisco Packet Tracer

Diseño, configuración y pruebas de redes empresariales en Cisco Packet Tracer (Cisco IOS). Incluye el proyecto final del curso de Redes de Computadoras (Facultad de Ciencias, UNAM, 2026) y las prácticas de enrutamiento, switching, seguridad y servicios de red.

## Proyecto final: topología empresarial

Archivos: [`proyecto-final/topologia-final.pkt`](proyecto-final/topologia-final.pkt) · [reporte con evidencias (PDF)](proyecto-final/reporte-topologia-final.pdf)

| Área | Qué se configuró |
| --- | --- |
| Segmentación | VLANs por área de usuarios |
| Enrutamiento | Routers interconectados con enrutamiento dinámico |
| Salida a Internet | PAT (NAT con sobrecarga) en el router de borde |
| Seguridad de acceso | SSH en líneas VTY restringido por VLAN con `access-class` y ACL estándar |
| Filtrado de tráfico | ACL extendidas: bloqueo de ICMP y acceso HTTP/HTTPS solo para VLANs autorizadas |
| Seguridad de switches | Port-security y BPDU Guard, con estado err-disable ante violaciones |
| Monitoreo | Servidor Syslog que registra los eventos de seguridad |
| Servicios | DHCP, DNS, servidor web interno y correo (SMTP/POP3) |
| Inalámbrico | Router inalámbrico y Access Point con asignación por DHCP |

## Prácticas

| Archivo | Tema |
| --- | --- |
| `01-switching-vlans.pkt` | Switching y VLANs |
| `02-enrutamiento-estatico.pkt` | Enrutamiento estático |
| `03-etherchannel.pkt` | EtherChannel |
| `04-ospf.pkt` | OSPF de un área |
| `05-ospf-multiarea.pkt` | OSPF multiárea |
| `06-acls.pkt` | Listas de control de acceso |
| `07-nat.pkt` | NAT |
| `08-servicios-web-dns.pkt` | Servidores web y DNS |
| `09-servicio-ftp.pkt` | Servidor FTP |

## Cómo abrirlos

Instala [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer) y abre cualquier archivo `.pkt`.

## Autor

Edwin Rodríguez Nevárez · edrodnev@gmail.com
