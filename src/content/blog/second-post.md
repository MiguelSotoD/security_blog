---
title: 'Confidencialidad de la información'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Oct 04 2024'
heroImage: '/confidencialidad_inf.jpg'
---

#### <span style="color: #a31e1e">-Ley General de Protección de Datos Personales en Posesión de Sujetos Obligados (México)</span>
##### Descripción:
Esta ley establece las bases, principios y procedimientos para garantizar el derecho a la protección de datos personales en posesión de entidades públicas en México. Su objetivo es garantizar que los ciudadanos tengan control sobre sus datos personales y que estos no sean utilizados sin su consentimiento.
##### Aspectos clave
- Los sujetos obligados (entidades públicas) deben asegurar que los datos personales se usen solo para los fines establecidos y con el consentimiento del titular.
- La ley regula la recolección, manejo, almacenamiento y difusión de datos personales.
##### Impacto 
Protege la privacidad de los ciudadanos frente al uso indebido de su información por parte del gobierno y otras entidades públicas.
<!-- <div style="text-align: center;">
  <img src="/ddos.jpg" style="width: 55vh; height: 40vh;" />
</div> -->

#### <span style="color: #a31e1e">-Ley de Propiedad Industrial (México)</span>
##### Propósito
Proteger y regular los derechos sobre la propiedad industrial en México, incluyendo patentes, marcas, diseños industriales, y secretos comerciales.
##### Áreas Clave
- **Patentes:** Protege invenciones y mejoras en procesos industriales, asegurando que los inventores tengan derechos exclusivos sobre su uso.
- **Marcas:** Protege los signos distintivos utilizados en productos o servicios para diferenciarlos en el mercado.
- **Secretos** Industriales: Incluye la confidencialidad de la información técnica o comercial de valor económico para las empresas.
##### Relevancia para la confidencialidad
La ley protege la confidencialidad de los secretos comerciales y de fabricación, lo que es clave para la seguridad de la información en industrias altamente competitivas.

#### <span style="color: #a31e1e">-Ley Federal de Derechos de Autor (México)</span>
##### Objetivo
Salvaguardar los derechos de los creadores de obras literarias, artísticas y científicas, incluyendo software, bases de datos y otros productos digitales.
<div style="text-align: center;">
<img src="/derechos_autor.jpg" style="width: 60vh; height: 35vh;" />
</div>
<br>

##### Confidencialidad
Esta ley otorga a los autores el derecho exclusivo de controlar la divulgación de sus obras, protegiendo tanto su integridad como su uso no autorizado, lo que está directamente relacionado con la confidencialidad de la información creativa y técnica.
##### Ejemplo:
Un desarrollador de software tiene el derecho exclusivo sobre el código que escribe y puede decidir quién puede usar o modificar su obra.

#### <span style="color: #a31e1e">-Ley Federal de Protección de Datos Personales en Posesión de Particulares</span>
##### Propósito
Proteger los datos personales que se encuentran en posesión de personas físicas o morales, tales como empresas privadas.
##### Principios fundamentales:
- **Consentimiento:** Los titulares de los datos deben dar su consentimiento explícito para su uso.
- **Acceso, Rectificación, Cancelación y Oposición (ARCO):** Los ciudadanos tienen derecho a solicitar el acceso, rectificación, cancelación o a oponerse al uso de sus datos personales.
##### Motivaciones comunes:
- Financiera (robo de tarjetas de crédito).
- Política (hacktivismo).
- Espionaje (robos de propiedad intelectual).

**Importancia:** Asegura que las empresas manejen los datos personales de los clientes de manera confidencial y que tomen medidas para evitar su mal uso o filtración.

#### <span style="color: #a31e1e">-Código Penal Federal (México)</span>
El Código Penal Federal incluye varios delitos relacionados con la violación de la confidencialidad de la información, como el acceso no autorizado a sistemas informáticos y el uso indebido de información protegida o clasificada.
##### Artículos Relacionados:
- **Artículo 211 bis:** Sanciona a quien acceda a sistemas o equipos informáticos sin autorización.
- **Artículo 210:** Penaliza la divulgación no autorizada de secretos industriales.
#### <span style="color: #a31e1e">-Ley General de Transparencia y Acceso a la Información Pública</span>
Esta ley garantizar el acceso a la información pública en posesión de sujetos obligados (entidades gubernamentales), pero respetando la confidencialidad de datos personales y secretos de estado.
##### Excepciones a la transparencia:
- Datos que afecten la seguridad nacional.
- Información confidencial de personas (datos personales).

**Relevancia:** Esta ley busca equilibrar el derecho de acceso a la información pública con la necesidad de proteger la confidencialidad de ciertos datos sensibles.


### Criptografía y Técnicas de Cifrado
<br>
<div style="text-align: center;">
<img src="/tecnicas_cifrado.jpg" style="width: 80vh; height: 35vh;" />
</div>
<br>

#### <span style="color: #a31e1e">-Criptografía Simétrica</span>
Es un método de cifrado donde se utiliza la misma clave para cifrar y descifrar la información. Ambas partes (emisor y receptor) deben tener acceso a la misma clave de manera segura.
##### Ventajas:
- Alta eficiencia y rapidez en el proceso de cifrado y descifrado.
##### Desventajas:
Si la clave es interceptada, todo el sistema de seguridad queda comprometido.

**Ejemplos:** AES (Advanced Encryption Standard) y DES (Data Encryption Standard).

#### <span style="color: #a31e1e">-Criptografía Asimétrica</span>
Utiliza un par de claves: una clave pública y una clave privada. La clave pública se utiliza para cifrar la información, mientras que la clave privada, que solo el receptor conoce, se utiliza para descifrarla.
##### Ventajas:
No es necesario compartir la clave privada, lo que reduce el riesgo de comprometer la seguridad.
##### Desventajas:
Más lento en comparación con la criptografía simétrica debido a su complejidad matemática.

**Ejemplo:** RSA (Rivest-Shamir-Adleman), utilizado en la mayoría de las transacciones en línea seguras.

#### <span style="color: #a31e1e">-Cifrado por Bloques y por Flujo</span>
##### Cifrado por Bloques
**Descripción:** Divide el texto plano en bloques de un tamaño fijo y aplica el cifrado a cada bloque de datos de manera independiente.

[Ejemplo:] AES (tamaño de bloque de 128 bits).
<div style="text-align: center;">
<img src="/cifrado_bloques.jpg" style="width: 70vh; height: 30vh;" />
</div>

**Ventajas:**
Alta seguridad al cifrar grandes volúmenes de datos.

**Desventajas:**
El proceso puede ser más lento, especialmente con grandes cantidades de datos.

##### Cifrado por Flujo
**Descripción:** Cifra el texto plano de forma continua, bit por bit o byte por byte, usando una clave de flujo que genera una secuencia pseudoaleatoria de bits.

[Ejemplo:] RC4 (Rivest Cipher 4).

<div style="text-align: center;">
<img src="/cifrado_flujo.jpg" style="width: 70vh; height: 30vh;" />
</div>

**Ventajas:**
Más eficiente para el cifrado de datos en tiempo real o de tamaño variable.

**Desventajas:**
Menos seguro si no se usa correctamente, como ocurrió con vulnerabilidades en RC4.

#### <span style="color: #a31e1e">-Criptoanálisis</span>
##### Contexto histórico:
El criptoanálisis es la técnica utilizada para descifrar datos cifrados sin conocer la clave, mediante el análisis de patrones o debilidades en los algoritmos criptográficos.

**Métodos de Ataque:**
- Ataques por fuerza bruta: Probar todas las combinaciones posibles de claves.
- Ataques de texto plano conocido: Donde el atacante tiene acceso a un texto cifrado y su correspondiente texto en claro.

**Relevancia:** El criptoanálisis busca mejorar la seguridad al identificar las vulnerabilidades en los algoritmos de cifrado y proponer mejoras.
