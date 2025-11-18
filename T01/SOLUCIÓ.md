# Pla de Còpies de Seguretat

## ✅ Fase 1: Estratègia de Còpies

### 1. Què copiar? (Priorització)
- **Dades més crítiques del servidor:**
  - **Base de dades**: Conté informació essencial per al funcionament de l’organització.
  - **Carpetes personals dels usuaris**: Documents diaris i informació general.
  - **Documents de projectes**: Informació important però menys crítica que la base de dades.

- **Cal fer còpia dels 10 equips clients?**
  - **No és necessari** fer còpia completa dels equips clients, ja que les dades es desen al servidor de fitxers. Només caldria fer còpia parcial si hi ha informació local no sincronitzada.

---

### 2. Periodicitat i Tipus de Còpia
**Calendari per setmana:**

| Tipus           | Diari                      | Setmanal                     | Mensual                   |
|-----------------|----------------------------|------------------------------|---------------------------|
| **Completa**    |                            | Bases de Dades              | Documents de Projectes    |
| **Diferencial** |                            | Especificacions tècniques   |                           |
| **Incremental** | Crítiques i d'ús diari    | Plànols                      |                           |

**Explicació:**
- **Diari**: Incremental per a dades crítiques i d’ús diari (canvis constants).
- **Setmanal**:
  - Completa per a la base de dades (garantir integritat).
  - Diferencial per a especificacions tècniques (canvis poc freqüents).
  - Incremental per a plànols (seguretat addicional).
- **Mensual**: Completa per a documents de projectes (informació menys crítica).

---

### 3. Mitjans i Ubicació (Regla 3-2-1)
- **Mitjà principal**: Discs durs externs (fiables i ràpids).
- **Mitjà secundari**: Cinta magnètica (per a còpies a llarg termini).
- **Ubicació**:
  - 1 còpia local (servidor intern).
  - 1 còpia externa (cloud privat).
  - 1 còpia fora de l’empresa (cinta magnètica en ubicació segura).

---

## ✅ Fase 2: Proposta resumida
| Element              | Proposta               | Justificació                |
|----------------------|------------------------|-----------------------------|
| **Dades Crítiques** | Base de dades          | Conté informació essencial |
| **Periodicitat (BD)**| Setmanal              | Evita pèrdua de dades      |
| **Tipus de Còpia (BD)**| Completa en xarxa   | Garantir integritat        |
| **Mitjà 1 (Local)** | Disc dur extern        | Fiabilitat i rapidesa      |
| **Mitjà 2 (Extern)**| Cinta magnètica        | Seguretat a llarg termini  |
