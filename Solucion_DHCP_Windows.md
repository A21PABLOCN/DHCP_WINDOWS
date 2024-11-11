# Servidores DHCP Windows

### 1. Un ámbito para os equipos da rede privada lanister, con un intervalo de exclusión.
### 2. Deberás crear unha reserva estática que estará no rango de enderezos do seu ámbito correspondente.
### 3. Establece os nomes de dominio e servidores DNS primario de cada zona.
### 4. Deberás actualizar a zona primaria no servidor DNS tywin.
### 5. Engade outro ámbito para a rede primaria stark (necesitas outra interface de rede) que actualice a zona prinaria DNS definida no equipo arya.
### 6. Instala no equipo jaime un servizo DHCP failover para a subrede lanister.
### 7. Necesitarás polo menos tres clientes (Cercei,Joffrey, Myrcella) para a rede lannister e un para a  rede stark (jon). Inclúe capturas de:
- Configuración dos ambitos e rangos de enderezos

![imagen1](./imaxes_DHCP_Windows/Captura1.png)

![imagen2](./imaxes_DHCP_Windows/Captura2.png)
- Configuración de opcións

![imagen3](./imaxes_DHCP_Windows/Captura3.png)

![imagen4](./imaxes_DHCP_Windows/Captura4.png)

- Configuración da actualización

![imagen5](./imaxes_DHCP_Windows/Captura5.png)

![imagen6](./imaxes_DHCP_Windows/Captura6.png)

![imagen7](./imaxes_DHCP_Windows/Captura7.png)

![imagen8](./imaxes_DHCP_Windows/Captura8.png)

![imagen9](./imaxes_DHCP_Windows/Captura9.png)

- Vídeo no que o cliente renova a concesión, e se ve  a zona DNS unha vez que o DHCP actualiza o DNS. Tamén o cliente debe ser capaz de resolver o seu propio nome (non FQDN).

![imagen10](./imaxes_DHCP_Windows/Captura10.png)

![imagen11](./imaxes_DHCP_Windows/Captura11.png)

![imagen22](./imaxes_DHCP_Windows/Captura22.png)

![imagen12](./imaxes_DHCP_Windows/Captura12.png)

- Clientes das dúas subredes, amosando DNS, router e enderezo IP.

![imagen13](./imaxes_DHCP_Windows/Captura13.png)

![imagen14](./imaxes_DHCP_Windows/Captura14.png)

- Configuración dos servidores failover

![imagen15](./imaxes_DHCP_Windows/Captura15.png)

![imagen16](./imaxes_DHCP_Windows/Captura16.png)

- Capturas dos clientes obtendo enderezos cos dous servidores failover encendidos, e con un acendido e outro apagado (de forma alterna)

![imagen17](./imaxes_DHCP_Windows/Captura17.png)

![imagen18](./imaxes_DHCP_Windows/Captura18.png)

### 9. Elimina a interface de rede 192.168.11.8 de tyrion, e configura o servizo DHCP Relay no router. Comproba que os equipos da rede stark.lan reciben a configuración de rede de xeito correcto. Inclúe as capturas necesarias.

![imagen19](./imaxes_DHCP_Windows/Captura19.png)

![imagen20](./imaxes_DHCP_Windows/Captura20.png)

![imagen21](./imaxes_DHCP_Windows/Captura21.png)

