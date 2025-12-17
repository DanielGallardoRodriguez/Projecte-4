# T07 – Accés remot  
## Serveis d’assistència remota (Helpdesk EverPia)

---

# Fase 1: Anàlisi comparativa i selecció de la solució

## Introducció
En el servei de Helpdesk d’EverPia, una part important de la feina consisteix a donar suport remot a usuaris finals que, en molts casos, no tenen coneixements tècnics. Per aquest motiu, és necessari disposar d’una eina d’assistència remota sota demanda que sigui fàcil d’utilitzar, ràpida i segura, sense requerir configuracions complexes com VPNs o l’obertura de ports.

L’objectiu d’aquesta fase és analitzar diferents eines d’assistència remota i seleccionar la més adequada per estandarditzar el servei de suport d’EverPia.

---

## Eines analitzades
Les eines analitzades en aquesta fase són:
- TeamViewer  
- AnyDesk  
- Google Chrome Remote Desktop  
- RustDesk  

---

## Taula comparativa

| Criteri | TeamViewer | AnyDesk | Google Chrome Remote Desktop | RustDesk |
|--------|-----------|---------|------------------------------|----------|
| **Facilitat d’ús (client)** | Molt alta. Mòdul QuickSupport sense instal·lació, amb ID i contrasenya visibles. | Molt alta. Executable portable molt lleuger i fàcil d’utilitzar. | Mitjana. Requereix compte de Google i configuració prèvia. | Mitjana. Portable, però menys intuïtiva per a usuaris no tècnics. |
| **Instal·lació necessària** | No (QuickSupport) | No (versió portable) | Sí | No |
| **Windows** | Sí | Sí | Sí | Sí |
| **macOS** | Sí | Sí | Sí | Sí |
| **Linux** | Sí | Sí | Limitada | Sí |
| **Model de preu** | Gratuït només per a ús personal. L’ús comercial requereix llicència. | Llicència de pagament per a ús comercial, amb un cost inferior a TeamViewer. | Gratuït, però amb funcionalitats limitades. | Gratuït i de codi obert. Possibilitat d’autoallotjament. |

---

## Recomanació

### Eina seleccionada: **AnyDesk**

Després de l’anàlisi comparativa, es considera que **AnyDesk** és la millor opció per a EverPia. És una eina molt senzilla per als clients, ja que no requereix instal·lació i permet iniciar una sessió de suport en pocs segons. A més, és compatible amb els principals sistemes operatius utilitzats a l’empresa.

Un altre factor important és el seu cost, que és més assequible que el de TeamViewer, oferint alhora funcionalitats suficients per a un entorn professional de Helpdesk.

---

## Conclusions de la Fase 1
AnyDesk ofereix un bon equilibri entre facilitat d’ús, compatibilitat multiplataforma i cost, fet que la converteix en la solució més adequada per al servei d’assistència remota d’EverPia.

---

# Fase 2: Creació de les guies d’ús (Documentació)

## Introducció
Un cop seleccionada l’eina d’assistència remota, s’han elaborat dues guies d’ús diferenciades: una adreçada als tècnics d’EverPia i una altra pensada per als clients finals. L’objectiu és facilitar l’ús correcte de l’eina i garantir un suport remot segur i eficient.

---

# Guia 1: Manual per al Tècnic (Intern d’EverPia)

## 1. Instal·lació de la versió tècnica d’AnyDesk
1. Accedir al web oficial d’AnyDesk.
2. Descarregar la versió corresponent al sistema operatiu.
3. Executar l’instal·lador i seguir els passos indicats.
4. Obrir AnyDesk un cop finalitzada la instal·lació.

**[Captura 1: Pàgina de descàrrega d’AnyDesk]**  
**[Captura 2: Procés d’instal·lació d’AnyDesk]**

---

## 2. Iniciar una sessió de suport remot
1. Demanar al client el seu **ID d’AnyDesk**.
2. Introduir l’ID al camp *Remote Desk*.
3. Fer clic al botó **Connect**.
4. Esperar que el client accepti la connexió.

**[Captura 3: Pantalla principal d’AnyDesk amb el camp Remote Desk]**

---

## 3. Gestió de funcions clau

### 3.1 Transferència d’arxius
- Utilitzar l’opció de transferència d’arxius o arrossegar fitxers entre dispositius.

**[Captura 4: Transferència d’arxius]**

### 3.2 Canvi de pantalla
- Seleccionar la pantalla desitjada si el client disposa de més d’un monitor.

**[Captura 5: Canvi de pantalla]**

### 3.3 Reinici remot
- Utilitzar l’opció de reinici remot quan sigui necessari.

**[Captura 6: Reinici remot]**

---

## 4. Bones pràctiques de seguretat
- Tancar sempre la sessió en finalitzar el suport.
- No desar contrasenyes ni dades dels clients.
- Demanar permís abans de fer canvis importants.
- Informar el client quan la sessió hagi finalitzat.

---

# Guia 2: Manual per al Client (Usuari Final)

## 1. Descarregar AnyDesk (sense instal·lació)
1. Obrir el navegador.
2. Accedir a l’enllaç facilitat pel tècnic.
3. Fer clic a **Download**.
4. Obrir el fitxer descarregat.

**[Captura 7: Descàrrega d’AnyDesk]**

---

## 2. Identificar l’ID i la contrasenya
- A la pantalla principal d’AnyDesk apareixen l’ID del dispositiu i la contrasenya temporal.
- Aquestes dades s’han de comunicar al tècnic.

**[Captura 8: ID i contrasenya]**

---

## 3. Acceptar la connexió
1. Quan el tècnic es connecti, apareixerà una finestra.
2. Fer clic a **Acceptar**.
3. Mantenir AnyDesk obert fins que el tècnic finalitzi.

**[Captura 9: Acceptar connexió]**

---

## 4. Finalització de la sessió
Un cop resolta la incidència, el tècnic tancarà la sessió i l’usuari podrà tancar AnyDesk amb normalitat. La contrasenya canviarà automàticament per seguretat.

---

## Conclusió final
Amb la implementació d’AnyDesk i la creació d’aquestes guies, EverPia disposa d’un sistema d’assistència remota clar, segur i fàcil d’utilitzar, tant per als tècnics com per als clients.
