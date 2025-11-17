# T09: Servidor de fitxers Linux. NFS (tasca individual)

## Breu descripció
**Objectiu:** Configurar un servidor de fitxers NFS (Network File System) i un client Linux per centralitzar dades en entorns Linux, simulant el cas real d’un client.

---

## Introducció
**Cas Client: DevOptimize Solutions**
- Startup de desenvolupament de programari que treballa exclusivament amb Linux.
- Problema: dispersió de codi font i documents → errors de versió i baixa eficiència.
- Solució: implementar un **servidor de fitxers centralitzat amb NFS**.

**Requisits:**
- Sense autenticació centralitzada (LDAP no previst).
- Crear un servidor NFS (NFSv3) i un client Linux.
- Configurar usuaris i grups per simular l’entorn del client.
- Control d’accés mitjançant:
  - Opcions d’exportació (`/etc/exports`).
  - Permisos del sistema de fitxers (`chmod`, `chown`).

**Repositori amb descripció completa:**  
[Projecte04-Nb.com/SMX2n/Projecte04-NFS

---

## Objectius específics
- Configurar un servidor NFS amb diversos nivells d’accés.
- Preparar el client per accés automàtic als recursos compartits.

---

## Competències treballades
- **f)** Instal·lar, configurar i mantenir serveis multiusuari en xarxa.
- **g)** Realitzar proves funcionals i diagnosticar disfuncions.
- **o)** Utilitzar mitjans de consulta adequats per resoldre dubtes.

---

## RA(s) de la tasca
- **0224.RA4:** Gestiona recursos compartits del sistema, determinant nivells de seguretat.

### CA(s)
- 4.1: Diferència entre permís i dret.
- 4.2: Identificació de recursos compartits i condicions.
- 4.3: Assignació de permisos.
- 4.5: Ús d’entorn gràfic per compartir recursos.
- 4.6: Establir nivells de seguretat per controlar accés.

### C(s)
- 4.1: Permisos i drets.
- 4.2: Compartir arxius i directoris en xarxa.
- 4.3: Configuració de permisos de recurs compartit.

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
- Moodle: UD5. AA1. NFS.
- [Instal·lació NFS servidor Ubuntu 20.04](httpsn-un-servidor-ubuntu-20-04-lts/
- [Instal·lació NFS client Ubuntu -instalacion-en-un-cliente-ubuntu-20-04-lts/
- [Documentació oficial Ubuntu NFS](https://documentation.ubuntu.com/server/how-to/networking/install-nfs/)

