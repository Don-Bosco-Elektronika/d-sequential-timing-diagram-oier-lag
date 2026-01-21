6y# 🛠️ Cronograma de Circuitos Secuenciales / Zirkuitu Sekuentzialen Kronograma / Sequential Circuit Timing Diagram

| **Alumnos** | **Curso** | **Módulo** |
|-------------|-----------|------------|
| 2ME         | 1º        | EEM (Equipos Microprogramables) |

---





**Ariketa (EU): (1)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
|  D maila gorakoa|   74100          | <img width="86" height="97" alt="image" src="https://github.com/user-attachments/assets/5ac023cb-f5f8-4fb9-9a9a-15f9edd12e54" />| Latch bat da. Enable sarrera "1" (goian) dagoen bitartean, irteerak sarrera kopiatzen du (gardena da). |  

**Ariketa (EU): (2)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
|  D flanco ascendente|   74175         | <img width="143" height="94" alt="image" src="https://github.com/user-attachments/assets/11589333-bc87-42a5-a08d-b08e63196ac9" />| Flip-Flop arrunta. Erlojuaren seinalea behetik gora igotzen den unean (subida) bakarrik hartzen du datua. |  

**Ariketa (EU): (3)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
| D flaco ascendente         |   74164          |<img width="134" height="104" alt="image" src="https://github.com/user-attachments/assets/db753b4f-c606-4a20-a9eb-cffd3def1f05" />|  Desplazamendu-erregistroa. Barruko D flip-flopek erlojua igotzean mugitzen dute datua. |  

**Ariketa (EU): (4)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
| D flaco ascendente         |   74165          |<img width="145" height="89" alt="image" src="https://github.com/user-attachments/assets/65c7474a-56a5-4f9a-b33f-39fa3a49a35f" />| Erregistroa da hau ere. Barruko logika D motakoa da eta goranzko flankoarekin funtzionatzen du. |  

## Tabla de la verdad

| Entrada A | Entrada B | Entrada C | Salida    | Salida |
|-----------|-----------|-----------|-----------|--------|
| 0         | 0         | 0         | ░0░       | ░0░    |
| 0         | 0         | 1         | ░1░       | ░1░    |
| 1         | 1         | 0         | ░1░       | ░1░    |
| 1         | 1         | 1         | ░0░       | ░0░    |

---

## 🔲 Circuitos a Simular / Simulatzeko Zirkuituak / Circuits to Simulate

*(<img width="648" height="401" alt="image" src="https://github.com/user-attachments/assets/30263f29-e56f-4d82-9da7-6264a3dd43c2" />
)*

*(<img width="638" height="489" alt="image" src="https://github.com/user-attachments/assets/a0b9ae88-d6fb-4cea-a5cb-bdbada6c8ff8" />
 )*
*(<img width="922" height="469" alt="image" src="https://github.com/user-attachments/assets/84d5e662-3ebe-4f86-ad0b-8c2c95c3d3c8" />
)*
*(<img width="540" height="255" alt="image" src="https://github.com/user-attachments/assets/4b7545bd-af0a-4e82-8e86-0ac99ffeb0ce" />
)*
## 🔲 Resultado del Cronograma / Kronogramaren Emaitza / Timing Diagram Result
Circuito A

*(<img width="598" height="278" alt="image" src="https://github.com/user-attachments/assets/349ca663-d6ef-42c9-83c8-a95c7064dd34" />
)*

Circuito B

*(<img width="588" height="347" alt="image" src="https://github.com/user-attachments/assets/20f13226-db84-42d4-9e6b-90039dfdae06" />
)*



*(Circuito c

*(<img width="588" height="347" alt="image" src="https://github.com/user-attachments/assets/20f13226-db84-42d4-9e6b-90039dfdae06" />
)*
)*

Circuito D
*(<img width="587" height="354" alt="image" src="https://github.com/user-attachments/assets/b2e04841-feb8-4c78-b8f4-fb0ef3fdd777" />

)*

## 🔲 Código del Cronograma / Kronogramaren Kodea / Timing Diagram Code
Circuito A

*({signal: [

  {name: 'clk', wave: 'P................'},
  
  {name: 'D', wave: '0101..0..1.0..1.0'},
  
  {},
  
  {name: 'Q', wave: '0.101..0..1.0..1.'},
  
  {name: '-Q', wave: '1.010..1..0.1..0.'}
  
]}
)*

Circuito B

*({signal: [

  {name: 'clk', wave: 'P................'},
  
  {name: 'D', wave: '0101..0..1.0..1.0'},
  
  {},
  
  {name: 'Q', wave: '0.101..0..1.0..1.'},
  
  {name: '-Q', wave: '1.010..1..0.1..0.'}
  
]}
)*
Circuito C

{signal: [

  {name: 'clk', wave: 'N................'},
  
  {name: 'D', wave: '10101..0.10.1..01'},
  
  {},
  
  {name: 'Q', wave: '1.0101..0.10.1..0'},
  
  {name: '-Q', wave: '0.1010..1.01.0..1'}
  
]}


)*
Circuito D

{signal: [

  {name: 'clk', wave: 'p................'},
  
  {name: 'D', wave: 'hlhlh..l.hl.h..lh'},
  
  {},
  
  {name: 'Q', wave: 'h.l.h.l.h.....l..'},
  
  {name: '-Q', wave: 'l.h.l.h.l.....h..'}
  
]}





## 📤 Entrega / Igo / Upload  

➡️ **Instrucciones:**  

- **ES:** Sube los siguientes archivos. Todos los archivos subidos han de tener tu nombre.  
  - Una foto del símbolo.  
  - El archivo en Proteus y una captura de imagen de cada circuito en Proteus.  
  - Capturas de cada resultado del Wavedrom (solo el gráfico).  
  - **ATENCIÓN:** El código del cronograma TIENE que ser código, no una imagen.

- **EU:** Igo hurrengo fitxategiak. Igotako fitxategi guztiek zure izena eduki behar dute.  
  - Sinboloaren argazki bat.  
  - Proteus fitxategia eta zirkuitu bakoitzaren irudia (captura) Proteusen.  
  - Wavedrom bakoitzaren emaitzaren kaptura (grafikoa bakarrik).  
  - **KONTUZ:** Kronogramaren kodea kodea izan behar da, ez irudi bat.

- **EN:** Upload the following files. All uploaded files must include your name.  
  - A photo of the symbol.  
  - The Proteus file and an image capture of each circuit in Proteus.  
  - Uno capture of each Wavedrom result (graph only).  
  - **ATTENTION:** The schedule code MUST be real code, not an image.



