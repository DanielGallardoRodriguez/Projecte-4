# Fase 1

## 1. Què copiar? (Priorització)
Quines són les dades més crítiques del servidor? Cal fer còpia dels 10 equips clients? Justifica-ho.

- Copiar principalment tant la base de dades i si es pot els documents de projectes. Ja que les més crítiques són la base de dades i les Carpetes Personals dels Usuaris ja que són les diàries de cada usuari i les generals.
- No és necessari fer còpia completa dels equips clients, ja que les dades es desen al servidor de fitxers. Només caldria fer còpia parcial si hi ha informació local no sincronitzada.

---

## 2. Periodicitat i Tipus de Còpia
Proposa un calendari bàsic per a la setmana (Diari/Setmanal/Mensual) i quin tipus de còpia aplicaràs (Completa, Diferencial, Incremental) per a les dades crítiques.

**Calendari per setmana:**

| Tipus           | Diari                      | Setmanal                     | Mensual                   |
|-----------------|----------------------------|------------------------------|---------------------------|
| **Completa**    |                            | Bases de Dades              | Documents de Projectes    |
| **Diferencial** |                            | Especificacions tècniques   |                           |
| **Incremental** | Crítiques i d'ús diari    | Plànols                      |                           |

**Explicació:**
- **Diari**: Farem una còpia diària incremental sobre les dades crítiques i d’ús diari, ja que és informació que necessitem diàriament i es va actualitzant constantment.
- **Setmanal**:
  - Farem una còpia completa sobre les bases de dades, ja que és necessari per mantenir tot correctament i amb una a la setmana ja és suficient.
  - A part, farem una còpia diferencial sobre les especificacions tècniques per tal de mantenir aquestes dades, suficient fer una setmanal ja que no solen variar molt.
  - Finalment, farem una còpia incremental dels plànols una vegada per setmana per assegurar possibles intrusions.
- **Mensual**: Farem una còpia completa dels documents de projectes al mes, ja que és informació menys crítica i amb una còpia mensual és suficient.

---

## 3. Mitjans i Ubicació
Quin tipus de mitjà de còpia utilitzaries (Discs durs externs, NAS, Cloud, Cintes)? On s'hauria de guardar físicament la còpia més recent (Regla 3-2-1).

- Utilitzaria discs durs externs, ja que és la forma més segura de mantenir la informació correctament i recomano aquesta opció.
- S’hauria d’emmagatzemar en un backup al Cloud privat.

---

# Fase 2

| Element                | Proposta de la Parella | Justificació                     |
|------------------------|------------------------|----------------------------------|
| **Dades Crítiques**    | Base de dades         | És l’element més important ja que conté |
| **Periodicitat (BD)**  | 1 setmanal            | Evita pèrdua de dades            |
| **Tipus de Còpia (BD)**| Completa en xarxa     | Garantir integritat              |
| **Mitjà 1 (Local)**    | Disc durs externs     | Fiabilitat i rapidesa            |
| **Mitjà 2 (Extern)**   | Cinta magnètica       | Seguretat a llarg termini        |
