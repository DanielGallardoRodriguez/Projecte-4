# T10: Servidor d’impressió Linux. CUPS (tasca individual)

## Breu descripció
**Objectiu:** Configurar un servidor d’impressió centralitzat amb CUPS en Ubuntu Server i compartir-lo amb clients Linux (Zorin OS), utilitzant una impressora virtual per demostrar la viabilitat de la solució.

---

## Introducció
A EverPia, la gestió d’impressores és un punt crític per reduir costos i simplificar processos. El client **DevOptimize Solutions** vol centralitzar la impressió en tots els seus departaments (entorn Linux mixt).

**Prova de concepte (PoC):**
- Simular una impressora de xarxa amb **cups-pdf** (impressió en fitxer PDF).
- Configurar un servidor Ubuntu amb CUPS i un client Zorin OS.
- Demostrar que el client pot enviar treballs d’impressió al servidor.

**Escenari:**
- **Servidor:** Ubuntu Server amb interfícies NAT + Host-Only.
- **Client:** Zorin OS amb la mateixa configuració de xarxa.

---

## Passos de la PoC
1. Instal·lació de **CUPS** al servidor.
2. Instal·lació de la impressora virtual **cups-pdf**.
3. Configuració de l’administració de CUPS i habilitar escolta en totes les interfícies.
4. Compartir la impressora via frontal web de CUPS.
5. Afegir la impressora al client Zorin.
6. Fer proves d’impressió amb diversos documents.
7. Comprovar al servidor la generació dels fitxers PDF corresponents.

**Documentació requerida:**
- Comandes utilitzades.
- Captures de pantalla que demostrin el correcte funcionament.

---

## Objectius específics
- Configurar un servidor d’impressió amb CUPS.
- Compartir la impressora amb clients Linux.
- Validar la funcionalitat amb proves reals.

---

## Competències treballades
- **f)** Instal·lar, configurar i mantenir serveis multiusuari en xarxa.
- **g)** Realitzar proves funcionals i diagnosticar disfuncions.
- **o)** Utilitzar mitjans de consulta adequats per resoldre dubtes.

---

## RA(s) de la tasca
- **0224.RA4:** Gestiona recursos compartits del sistema, determinant nivells de seguretat.

### CA(s)
- 4.4: Compartir impressores en xarxa.

### C(s)
- 4.4: Configuració d’impressores compartides en xarxa.

---

## Capacitats clau treballades
- Autonomia
- Innovació
- Organització del treball
- Responsabilitat
- Treball en equip
- Resolució de problemes

---

## Termini i forma de lliurament
- **Quan:** Segons la data indicada al Moodle.
- **Producte final:**
  - Carpeta al repositori amb:
    - `README.md` → Enunciat de la tasca.
    - `GUIA.md` → Documentació completa de la prova de concepte.
- **Forma:** Lliurar enllaç a la carpeta del repositori a la tasca corresponent del Moodle.

---

## Materials i links de suport
- Moodle: UD5. AA1. CUPS.

