6y# 🛠️ Cronograma de Circuitos Secuenciales / Zirkuitu Sekuentzialen Kronograma / Sequential Circuit Timing Diagram

| **Alumnos** | **Curso** | **Módulo** |
|-------------|-----------|------------|
| 2ME         | 1º        | EEM (Equipos Microprogramables) |

---





**Ariketa (EU): (ZENBAKIA IDATZI)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
|  D|   74100          | <img width="86" height="97" alt="image" src="https://github.com/user-attachments/assets/5ac023cb-f5f8-4fb9-9a9a-15f9edd12e54" />| Latch bat da. Enable sarrera "1" (goian) dagoen bitartean, irteerak sarrera kopiatzen du (gardena da). |  

**Ariketa (EU): (ZENBAKIA IDATZI)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
|  D flanco ascendente|   74175         | <img width="143" height="94" alt="image" src="https://github.com/user-attachments/assets/11589333-bc87-42a5-a08d-b08e63196ac9" />
| Flip-Flop arrunta. Erlojuaren seinalea behetik gora igotzen den unean (subida) bakarrik hartzen du datua. |  

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

## 🔲 Resultado del Cronograma / Kronogramaren Emaitza / Timing Diagram Result
Circuito A

*(<img width="598" height="278" alt="image" src="https://github.com/user-attachments/assets/349ca663-d6ef-42c9-83c8-a95c7064dd34" />
)*

Circuito B

*(<img width="588" height="347" alt="image" src="https://github.com/user-attachments/assets/20f13226-db84-42d4-9e6b-90039dfdae06" />
)*

... AÑADE LO MÁS CIRCUITOS

---


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

... AÑADE LO MÁS CIRCUITOS

---


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



