## T01: DRP - Còpies de seguretat. Estudi cas client (treball cooperatiu)

### Breu descripció
**Objectiu:** Aprendre i aplicar estratègies de còpies de seguretat mitjançant un cas pràctic real, treballant de forma individual, en parelles i en grup.

---

### Introducció
- El responsable de seguretat presenta el tema de les còpies de seguretat amb material didàctic.
- Dinàmica cooperativa per treballar els aspectes clau.

---

### Cas Client: *Muntatges i Serveis Tècnics SL*
**Infraestructura tècnica:**
- **Servidor Ubuntu:**  
  - Documents de projectes (300 GB, creixement moderat).  
  - Bases de dades (Comptabilitat i Clients) (20 GB, canvi constant).  
  - Carpetes personals (100 GB).
- **10 equips clients (Windows 10/11):** Fitxers temporals en Documents.
- **Connexió:** Fibra òptica 600 Mbps simètrica.

**Requisits de recuperació:**
- **RTO:** Comptabilitat/Clients disponibles en < 4 hores.
- **RPO:** Pèrdua màxima 24h (excepte Comptabilitat/Clients: màxim 4h).
- **Retenció:** Historial mínim d’1 mes.

---

### Fase 1: Treball individual
Respon:
1. **Què copiar?** Prioritza dades crítiques. Cal copiar els equips clients? Justifica.
2. **Periodicitat i tipus de còpia:** Proposa calendari (diari/setmanal/mensual) i tipus (Completa, Diferencial, Incremental).
3. **Mitjans i ubicació:** Quin mitjà (discs externs, NAS, Cloud, cintes) i on guardar la còpia (Regla 3-2-1).

---

### Fase 2: Treball per parelles
- **Discussió i consens:** Comparar respostes individuals.
- **Proposta unificada:** Dissenyar esquema 3-2-1 (3 còpies, 2 mitjans, 1 fora de lloc).
  
**Taula de proposta:**
| Element        | Proposta Parella | Justificació |
|---------------|-------------------|--------------|
| Dades Crítiques |                   |              |
| Periodicitat (BD) |                |              |
| Tipus de Còpia (BD) |              |              |
| Mitjà 1 (Local) |                 |              |
| Mitjà 2 (Extern) |                |              |

---

### Fase 3: Treball en grup
- **Debat i selecció:** Cada parella presenta el seu esquema.
- **Política final:** Redactar la política definitiva per l’empresa.

**Document final ha d’incloure:**
1. **Dades objecte de còpia:** Servidor/Clients, crítiques/no crítiques.
2. **Cronograma setmanal detallat:**
| Dia      | Dades | Tipus de còpia | Mitjà |
|----------|-------|----------------|-------|
| Dilluns  |       |                |       |
| Dimarts  |       |                |       |
| ...      |       |                |       |
| Diumenge |       |                |       |

3. **Mitjans i ubicació (Regla 3-2-1):**  
   - Mitjà 1 (Local): Ex. Disc dur USB, NAS.  
   - Mitjà 2 (Extern): Ex. Cloud (Azure, Google Cloud).  
   - Ubicació fora de lloc: Qui gestiona la còpia externa.
4. **Estratègia de recuperació (RTO/RPO):** Garantir requisits per Comptabilitat/Clients.

---

### Materials i links de suport
- Moodle 0226 Seguretat Informàtica. RA2.AA3Còpies
- INCIBE: *Copias de seguridad. Una guía de aproximación para el empresario.*
- Xataka: *Backup 3-2-1, el método definitivo para mantener a salvo tus datos.*  

