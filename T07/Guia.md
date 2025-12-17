# T07 – Accés remot  
## Fase 1: Anàlisi comparativa i selecció de la solució

## Introducció
En l’àmbit del Helpdesk d’EverPia, és habitual donar suport remot a usuaris finals que no tenen coneixements tècnics. Per aquest motiu, és necessari utilitzar una eina d’assistència remota que sigui fàcil d’utilitzar, ràpida i que no requereixi configuracions complexes per part del client, com ara la instal·lació de VPNs o l’obertura de ports al router.

L’objectiu d’aquesta fase és analitzar diverses eines d’assistència remota del mercat i seleccionar la que millor s’adapti a les necessitats d’EverPia.

---

## Eines analitzades
En aquesta anàlisi s’han tingut en compte les següents eines:
- TeamViewer  
- AnyDesk  
- Google Chrome Remote Desktop  
- RustDesk  

---

## Taula comparativa

| Criteri | TeamViewer | AnyDesk | Google Chrome Remote Desktop | RustDesk |
|--------|-----------|---------|------------------------------|----------|
| **Facilitat d’ús (client)** | Molt alta. Disposa del mòdul QuickSupport, que no necessita instal·lació i mostra clarament l’ID i la contrasenya. | Molt alta. És portable, molt lleuger i mostra l’ID de connexió de manera immediata. | Mitjana. Cal tenir un compte de Google i fer una configuració prèvia. | Mitjana. Tot i ser portable, la interfície és menys intuïtiva per a usuaris no tècnics. |
| **Instal·lació necessària** | No (QuickSupport) | No (versió portable) | Sí | No |
| **Windows** | Sí | Sí | Sí | Sí |
| **macOS** | Sí | Sí | Sí | Sí |
| **Linux** | Sí | Sí | Limitada | Sí |
| **Model de preu** | Gratuït només per a ús personal. L’ús comercial requereix una llicència de pagament. | De pagament per a ús comercial, però amb un cost més baix que TeamViewer. | Gratuït, però amb funcions limitades per a un ús professional. | Gratuït i de codi obert, amb opció de servidor propi. |

---

## Recomanació

### Eina seleccionada: **AnyDesk**

Després de comparar les diferents solucions, considera que **AnyDesk** és la millor opció per a EverPia. És una eina molt senzilla per als clients, ja que no requereix instal·lació i permet començar una sessió de suport en pocs segons. A més, és compatible amb Windows, macOS i Linux, fet que és molt important per a una empresa que treballa amb entorns diversos.

Un altre punt a favor és el seu cost, ja que és més econòmic que TeamViewer i ofereix funcionalitats suficients per a un servei de Helpdesk professional.

---

## Conclusió
En conclusió, AnyDesk ofereix un bon equilibri entre facilitat d’ús, compatibilitat amb diferents sistemes operatius i preu. Per aquests motius, es recomana com a eina estàndard d’assistència remota per al servei de suport tècnic d’EverPia.
