## T02: DPR - Còpies de seguretat. Cas pràctic

### Breu descripció
**Objectiu:** Implementar la política de còpies de seguretat dissenyada a la tasca anterior mitjançant proves de concepte i guies tècniques per al client.

---

### Introducció al cas
- A partir de la política creada per "Muntatges i Serveis Tècnics SL", cal elaborar guies tècniques amb proves reals.
- Es treballarà en dos àmbits:
  1. **Equip client Windows (director)**
  2. **Servidor Linux (Ubuntu Server)**

---

### **Part 1: Còpia de seguretat dels equips clients Windows**
- Excepció: fer còpia de l’equip Windows del director (informació sensible fora del servidor).
- **Esquema 3-2-1:**
  - Còpia local en disc secundari.
  - Còpia al cloud (Google Drive) amb **Duplicati**.
- **Prova de concepte:**
  - Crear VM Windows 11 amb dos discos (SO + disc secundari 10 GB).
  - Configurar còpies:
    - Cada hora al disc secundari.
    - A les 18:00 al Google Drive.
  - Documentar:
    - Instal·lació de Duplicati.
    - Configuració dels plans de còpia.
    - Restauració des del disc secundari i des del cloud.
- **Accions:**
  - Afegir arxius a Documents.
  - Esborrar contingut i restaurar.
  - Comprovar restauració des del cloud.

---

### **Part 2: Còpia de seguretat servidor Linux**
- Eina: **Duplicity** + **cron** per automatitzar.
- **Prova de concepte:**
  1. Crear VM Ubuntu Server + disc addicional 10 GB.
  2. Formatar en **xfs** i muntar a `/media/backup`.
  3. Instal·lar duplicity.
  4. Crear usuaris addicionals i arxius de prova.
  5. Fer còpia de `/home`.
  6. Esborrar arxius i restaurar.
  7. Afegir nou arxiu i fer còpia incremental.
  8. Desmuntar unitat de backup.
- **Automatització amb scripts:**
  - `fullbackup.sh`: còpia completa + variable d’entorn `PASSPHRASE`.
  - Programar amb cron: diumenge 23:00.
  - `incrementalbackup.sh`: còpia incremental.
  - Programar amb cron: dilluns-dissabte 23:00.
- **Seguretat:** La unitat de backup ha d’estar desmuntada per defecte (muntar abans i desmuntar després).

---

### Materials i links de suport
- [Duplic/duplicati.com/
- [WayToIT: Creando archivos con fsutil](https://waytoit.wordpress.com/2015/03/15/crereando archivos de prueba en Linux](https://waytoit.wordpress.com/2015/03/21ity man page](http://manpages.ubuntu.com/manpages/trusty/man1/duplicity.1.html)

