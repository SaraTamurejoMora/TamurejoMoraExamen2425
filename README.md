### **Examen - RA6: Creació i Gestió d'un Projecte Web amb Git i Desplegament en Vercel**

#### **Durada máxima**: 1 hora i 30 minuts

---

### **Objectiu**  
Crear un projecte web amb documents HTML, CSS i JavaScript. 
Gestionar amb Git, utilitzar branques i publicar un projecte.

---

### **Documentació**  
Has de crear un document en format **Markdown** amb les imatges i l'explicació necessària que es demana a l'examen.  

En acabar l'últim pas de l'examen, hauràs de penjar aquest document a la branca de **documentació**, incloent-hi les fotografies corresponents.

---

### **Instruccions**

#### **1. Configuració inicial**

1. Comprova la versió instal·lada de Git, fes captura del terminal.

  ![VersionGit](https://github.com/user-attachments/assets/2baafa48-a84f-48cb-819e-dfab7bdc8efb)


2. Configura Git al teu sistema (opcional)
   
  ![ConfigUser_Gmail](https://github.com/user-attachments/assets/4eaa87ae-fcd0-4926-84fe-b2ea65f44387)

   

3. Mostra la configuració actual per verificar-ho, fes captura del terminal. Explica com veig que he configurat correctament el email i el nom.
  ![MostrarConfigGit](https://github.com/user-attachments/assets/1b502365-e78c-4e58-98da-d5e036f7e2fa)

- Puedes verlo usando el comando _git config --list_, estará bien configurado si en user.name está tu nombre y en user.email tu correo.

5. Inicia un nou repositori Git al directori de treball on consideris. El nom del directorio ha de ser `Cognom1Cognom2Examen2425`.
   
  ![InicializarRepo](https://github.com/user-attachments/assets/827cd955-c8b3-46a6-941a-13867f70602a)

5. Crea un document README.md, afegeix el document i fes un primer commit que amb el missatge `1 - Git init`

    ![GitAddReadMe](https://github.com/user-attachments/assets/7e1df943-4ca1-4092-8594-3491212d1a1b)

    ![GitCommit1](https://github.com/user-attachments/assets/4653841b-c67a-47d9-9148-d601454bae4a)

  
---

#### **2. Creació del projecte web**

1. **Crea els fitxers següents al directori del projecte:**  
   - `index.html`
   - `testunitari.html`
   - `style.css`  
   - `main.js`
     
   ![Contenido Archivos](https://github.com/user-attachments/assets/acd8dcf5-2f92-4f37-a41b-828b36889ec0)


3. Afegeix contingut bàsic a cada fitxer.

---

#### **3. Gestió amb Git**

1. **Afegir fitxers:**  
   - Utilitza un patró d'expressió regular per afegir tots els fitxers `.html` i `.css`. Fes captura del terminal   

2. **Verifica l'estat del repositori, fes captura del terminal**  

![ConAdd](https://github.com/user-attachments/assets/447ded8d-fecd-4469-b02e-4ad6086fc64b)

3. **Elimina `testunitari.html` del staging**  

![SacarTest](https://github.com/user-attachments/assets/43673f5e-eb90-4ebb-b5cd-653ecf4ea4d8)

4. **Fes un commit que amb el missatge '2- Estructura bàsica'**  

5. **Consulta l'historial de commits, fes captura del terminal.**

   ![ComitEstructura2](https://github.com/user-attachments/assets/1343c6f5-70d2-4db4-8a18-0a6b03337294)
   
---

#### **4. Creació de branques i documentació**

1. **Crea una nova branca per a la documentació** 

![CrearRama](https://github.com/user-attachments/assets/742709d0-feb5-4853-a522-28521361cb8d)

2. **Crea un fitxer `README.md` si es necessari:**  
   - Explica dins del fitxer el propòsit del projecte.  

![CambiarRamaYReadme](https://github.com/user-attachments/assets/da734a29-8830-4b01-a9de-eca6e405d3b2)

3. **Afegeix i fes commit dels canvis a la branca `documentacio`.**
El missatge del commit ha de ser "3 - README.md amb documentació inicial"

![CommitRamaDocu](https://github.com/user-attachments/assets/04a0e91c-f5a0-48fe-93fe-a6d83fcb2c3b)

4. **Torna a la branca principal (`main`) i fes un merge** 

![MergeRama](https://github.com/user-attachments/assets/3c98e57b-15e9-4ff5-b0a1-f7ad670f00c5)

   
---

#### **5. Remot i publicació**

1. Configura un remot per al repositori que has de crear en GitHub, el nom del repositorio de GitHub ha de ser `Cognom1Cognom2Examen2425`. Fes captura al terminal de com has configurat el repositori remot.

![EnlazarRepo](https://github.com/user-attachments/assets/957530ab-88a7-4228-a6f7-69c14344dabf)

2. **Puja els canvis al remot desde terminal**.Fes captura al terminal.
   
![Push](https://github.com/user-attachments/assets/263679a7-e991-4047-b8cc-c2d3f22ecb93)

3. **Publica el projecte a Vercel i indica l'enllaç en el document Markdown del examen.**

  [Enlace pagina Vercel](https://tamurejo-mora-examen2425.vercel.app/)
   
