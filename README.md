[![Uide](https://th.bing.com/th/id/OIP.OdYsD-j7zmfUMkImH6fbYQAAAA?rs=1&pid=ImgDetMain "Uide")](https://th.bing.com/th/id/OIP.OdYsD-j7zmfUMkImH6fbYQAAAA?rs=1&pid=ImgDetMain "Uide")

# Evaluación en Contacto con el Docente

## El impacto de las nuevas tecnologías en la sociedad: visualización del futuro.

### Andrés Guerrero

<p>
Los temas que voy a tratar son:
</p>

- Software 
- Objetivo del Proyecto
- Pasos para resolver el Problema
- Diagrama Causa de Uso
- Diagrama Arquitectura de Software
- Diagrama de Flujo
- Presentación de Canva
- Código


### 1. Software

<p>
Yo escogí el software de: Generador de Contraseña Segura. Lo realice en el editor de código Visual Studio Code con el lenguaje de programación Python.
</p>

### 2. Objetivo

<p>
El objetivo de generar una contraseña segura es crear combinaciones únicas, aleatorias y difíciles de adivinar que protejan las cuentas e información sensible contra accesos no autorizados.
</p>

### 3. Pasos para Resolver el Problema

- **Identificar el Problema**
<p>
El problema principal es la mala gestión de contraseñas. Según un estudio de Verizon, el 70 % de empleados reutilizan sus contraseñas, lo que facilita ataques informáticos.
Datos clave incluyen:
-El 81 % de los incidentes relacionados con piratería se deben a contraseñas robadas o inseguras.
-80 % de los robos de datos en 2019 fueron causadas por vulnerabilidades de contraseñas, generando grandes pérdidas financieras.
</p>

- **Comprender el Problema**
<p>
Para mejorar la seguridad de la contraseña necesitamos caracteres aleatorios con letras mayúsculas y minúsculas, números y símbolos ya que tardan desde unos minutos hasta tres mil millones de años en descubrirse. También es importante que la contraseña tenga una longitud larga ya que genera más seguridad.
</p>

- **Identificar Soluciones Alternas**
  
  - No reutilizar contraseñas.
  - Utilizar una contraseña única para cada sitio web.   
  - No utilizar información personal en contraseñas.
  - Generar una contraseña aleatoria de caracteres utilizando Python.
   

- **Seleccionar la Mejor Solución**
<p>
La mejor solución es generar una contraseña aleatoria de caracteres utilizando python. Porque crea una contraseña de longitud específica mezclando letras, números y símbolos. Permitiendo dar seguridad al usuario.
</p>

- **Listar los Pasos de la Solución Seleccionada**

  1. Definir tipos de caracteres necesarios para construir la contraseña
  2. Incluir al menos un carácter de cada tipo
  3. Completar la longitud con caracteres aleatorios
  4. Evaluar la seguridad de la contraseña

### 4. Diagrama Caso de Uso
Visualice el [Diagrama Caso de Uso](http://drive.google.com/file/d/1_jFToZeKfE5DQ9bLyjpWeIyzqd2bDk2L/view?usp=sharing "Diagrama Caso de Uso")
elaborado en: [Aprendizaje Autónomo 1](https://github.com/Andydecori/UIDE_autonomo/tree/master/Aprendizaje_Aut%C3%B3nomo_1 "Aprendizaje Autónomo 1")

### 5. Diagrama Arquitectura de Software
Visualice el [Diagrama Arquitectura de Software](https://drive.google.com/file/d/16tgLvvbyPrCIG42yDYj65vOm8QJCTIRU/view?usp=sharing "Diagrama Arquitectura de Software")
elaborado en: [Aprendizaje Autónomo 1](https://github.com/Andydecori/UIDE_autonomo/tree/master/Aprendizaje_Aut%C3%B3nomo_1 "Aprendizaje Autónomo 1")

### 6. Diagrama de Flujo
Visualice el [Diagrama de Flujo](https://drive.google.com/file/d/1yAmPoPGwBUIoD90gTw3gqLRSmkESQmrS/view?usp=sharing "Diagrama de Flujo")
elaborado en: [Aprendizaje Autónomo 2](https://github.com/Andydecori/UIDE_autonomo/tree/master/Aprendizaje_Aut%C3%B3nomo_2 "Aprendizaje Autónomo 2")

### 7. Presentación de Canva 
Visualice la presentación del [Generador de Contraseña Segura](https://www.canva.com/design/DAGZeWQwoPI/B739HiQv5yclvWPw612Miw/view?utm_content=DAGZeWQwoPI&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h8133adfd3f "Generador de Contraseña Segura")

### 8. Código

```python

# Generador de contraseña segura

# Importa el módulo random para generar números o valores aleatorios
import random

minusculas = "abcdefghijklmnñopqrstuvwxyz"  
mayusculas = "ABCDEFGHIJKLMNÑOPQRSTUVWXYZ"  
numeros = "0123456789"                     
simbolos = "@#$&/?¿!}{<>\""       

print(" ----- Bienvenido a mi Generador de Contraseñas ----- ")

# Combina todos los tipos de caracteres 
caracteres_contraseña = minusculas + mayusculas + numeros + simbolos

# Solicita al usuario la longitud deseada para la contraseña
ancho_contraseña = int(input("Ingrese la longitud de la contraseña deseada: "))

# Bucle infinito para generar contraseñas hasta que el usuario decida salir
while True:
    # Genera una contraseña aleatoria tomando "ancho_contraseña" caracteres sin repetición
    contraseña = "".join(random.sample(caracteres_contraseña, ancho_contraseña))
    
    # Muestra la contraseña generada al usuario
    print("Tu contraseña segura es:", contraseña)
    
    # Pregunta si el usuario desea generar otra contraseña
    opcion = input("¿Te gustaría generar otra contraseña? (s/n): ").lower()
    
    # Si el usuario no responde con 's', el programa termina
    if opcion != "s":
        print("¡Gracias por usar mi generador de contraseñas!")
        break  # Sale del bucle


```
<p>
Ahora ejecutaré el código para confirmar su correcto funcionamiento.
</p>

Vizualizar la [Validación del Código](https://youtu.be/LnjgIUZwKRI "Validación del Código")
