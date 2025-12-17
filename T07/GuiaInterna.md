# T07: Accés Remot – Serveis d’Assistència Remota

**Empresa:** Consultoria IT EverPia  
**Data:** Desembre de 2025  
**Eina seleccionada:** RustDesk (solució gratuïta i professional)

---

## Fase 1: Anàlisi comparativa i selecció de la solució

Per al servei de Helpdesk d’EverPia, és imprescindible disposar d’una eina d’assistència remota que permeti donar suport immediat a l’usuari final, sense costos elevats de llicència ni limitacions per ús comercial. Per aquest motiu, s’han analitzat diverses solucions populars del mercat.

### Taula comparativa

| Criteri | **TeamViewer** | **AnyDesk** | **Chrome Remote Desktop** | **RustDesk** |
|------|---------------|-------------|---------------------------|--------------|
| **Facilitat d’ús (client)** | Molt alta (QuickSupport). | Alta (versió portable). | Mitjana (requereix Chrome). | **Alta (portable i intuïtiva)**. |
| **Model de preu** | Molt car (llicència comercial). | Pagament per tècnic. | Gratuït. | **Gratuït i de codi obert**. |
| **Limitacions** | Tall de sessions per ús comercial. | Restriccions en versió gratuïta. | Cal compte de Google i extensió. | **Sense límits de temps ni ús**. |
| **Instal·lació** | Opcional. | No necessària. | Obligatòria (extensió). | **No necessària (executar i llest)**. |

### Recomanació: RustDesk

Després de l’anàlisi, s’ha seleccionat **RustDesk** com a eina d’assistència remota oficial d’EverPia. Es tracta d’una alternativa gratuïta i professional a TeamViewer que permet el control total de les connexions, és compatible amb Windows, macOS i Linux, i no requereix cap inversió inicial en llicències.

A més, el seu caràcter de codi obert garanteix transparència i flexibilitat, aspectes molt valorats en un entorn professional de suport tècnic.

---

## Fase 2: Guies d’Ús (Documentació oficial)

A continuació es presenten dues guies diferenciades: una per als tècnics interns d’EverPia i una altra pensada per als clients finals.

---

## Guia 1: Manual per al Tècnic (Intern d’EverPia)

Aquesta guia descriu el flux de treball habitual que ha de seguir un tècnic per connectar-se a un client mitjançant RustDesk.

### 1. Execució de l’eina
Obre l’executable de **RustDesk** al teu ordinador. No és necessari instal·lar el programa, ja que pot executar-se directament.

<img width="1377" height="764" alt="Pantalla principal de RustDesk" src="https://github.com/user-attachments/assets/f3c07c3b-6045-4119-ace4-57a908adc157" />

---

### 2. Connexió amb el client
- A la part dreta de la finestra, localitza el camp **“Control Remote Desktop”**.
- Introdueix l’**ID** que t’ha facilitat el client.
- Prem el botó **“Connect”**.

<img width="1358" height="754" alt="Connexió mitjançant ID" src="https://github.com/user-attachments/assets/121f2a08-2937-4e01-a6f9-1ba397bf69b9" />

---

### 3. Autenticació
- El sistema sol·licitarà la **contrasenya**.
- Aquesta pot ser facilitada pel client o bé el client pot acceptar manualment la connexió prement **“Accept”**.

<img width="1358" height="773" alt="Autenticació de la connexió" src="https://github.com/user-attachments/assets/bf0d18ac-73d9-467e-8e6b-5c6bfeabc7ca" />

---

### 4. Eines de suport disponibles
Durant la sessió, el tècnic disposa de diverses eines:

- **Transferència de fitxers:** arrossegar fitxers directament a la finestra de la sessió.
- **Xat integrat:** útil per comunicar-se amb el client en cas de problemes d’àudio o tall de trucada.

<img width="1392" height="792" alt="Eines de suport" src="https://github.com/user-attachments/assets/d685ba2d-7d48-4421-881b-a6f9696416e9" />

> **Important – Seguretat**  
> En finalitzar la intervenció, tanca sempre la sessió de RustDesk.  
> El programa genera una contrasenya nova automàticament després de cada connexió, garantint la seguretat del client.

---

## Guia 2: Manual per al Client (Usuari Final)

Aquesta guia explica de manera senzilla com permetre que un tècnic d’EverPia es connecti al teu ordinador per ajudar-te.

### 1. Descarregar el programa d’ajuda
Accedeix a la pàgina oficial de RustDesk i descarrega la versió corresponent al teu sistema operatiu.  
Només cal **obrir el fitxer descarregat**; no és necessari instal·lar res.

---

### 2. Comunicar l’ID i la contrasenya
En obrir el programa, veuràs a la part esquerra:

- **ID:** un número de 9 dígits (per exemple: 123 456 789)
- **One-time Password:** una contrasenya temporal

Facilita aquestes dades al tècnic d’EverPia.

<img width="802" height="609" alt="ID i contrasenya del client" src="https://github.com/user-attachments/assets/422beb41-6ad7-4436-a80d-6e7493933aed" />

---

### 3. Acceptar la connexió
Quan el tècnic intenti connectar-se, apareixerà una finestra emergent.  
Fes clic a **“Accept”** per permetre l’accés.

<img width="909" height="670" alt="Acceptar connexió" src="https://github.com/user-attachments/assets/6f493212-8a49-4350-8f6e-7a5a594d9498" />

---

### 4. Finalitzar la sessió
En qualsevol moment pots tancar el programa prement la **X**.  
La connexió es tallarà immediatament.

---

[Tornar enrere](README.md)

