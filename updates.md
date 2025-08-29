# Updates
## General

<ins>**Hecho**</ins>
- Mover la base de datos de sqlite a mysql.
- Permitir que se editen los descuentos desde la página de Info en los configuradores.

<ins>**Pendiente**</ins>
- Permitir que se agreguen SKUs que no están en un Pricebook y ponerlos en rojo con un warning.

## Sightline/TMS

<ins>**Hecho**</ins>
- **Interno:** Mover toda la lógica de la planilla a la base de datos usando la table config_items.
- **Pricebook:** Dejar solo el Pricelist de Netsuite.
- **Cursos:** Actualizar los Cursos.
- **Servicios:** Corregir el cálculo de servicios de implementación.
- **Software TMS:** Revisar y corregir la lógica.
- **Sightline Appliance:** Dejar solo el SP-7500.
- **Insight Appliance:** Cambiar el tipo de nodos y poner los SKU de Avnet.
- **TMS Appliance:** Quitar los viejos y agregar el TMS8200.
- **DNS Probe:** Actualizar los ISNG que se permiten.

<ins>**Pendiente**</ins>
- **General:** Agregar ADP.
- **General:** Revisar como está funcionando la parte de AIF para TMS.
- **General:** Revisar que se agreguen los SKU de MNT para los appliance de Avnet.
- **Distributed TMS:** Agregar.

## AED

<ins>**Pendiente**</ins>
- **Subscripcion:** Habilitar la opción Subscription para los items que tengan SKUs en la lista (AED, vAED) o ponerlo como opción local.
- **AEDHD1000:** Cambio de la lógica para poner las opciones de los configurados en la tabla config_item de la DB.

## nGEniusONE

<ins>**Pendiente**</ins>

- **TAPs:** Revisar todo la parte de TAPs y Cables.
- **General:** Mover toda la lógica que aún queda a la tabla config_items.

## OCI

<ins>**Pendiente**</ins>
- **PFS:** Agregar PFS.
- **Servicios:** Agregar el calculo de servicios

## ASI Streamer

<ins>**Pendiente**</ins>
- **Crear el Configurador**
