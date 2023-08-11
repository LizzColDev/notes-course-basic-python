# Curso Python

Created: August 11, 2023 4:33 PM

- **Por qué aprender Python?**
    1. **Fácil de aprender y legible:** Python es conocido por tener una sintaxis simple y legible, lo que lo hace ideal tanto para principiantes como para programadores experimentados. Su estilo de escritura claro y conciso permite a los desarrolladores concentrarse en la lógica del programa en lugar de en detalles sintácticos complejos.
    2. **Versatilidad:** Python es un lenguaje de programación versátil que se puede utilizar en una amplia gama de aplicaciones, desde desarrollo web y análisis de datos hasta inteligencia artificial y automatización. Puedes crear desde simples scripts hasta aplicaciones y proyectos más complejos.
    3. **Comunidad y bibliotecas:** Python tiene una comunidad activa y en crecimiento, lo que significa que hay una gran cantidad de recursos disponibles en línea, incluidos tutoriales, documentación y foros de ayuda. Además, Python cuenta con una amplia variedad de bibliotecas y módulos que facilitan tareas comunes y aceleran el desarrollo.
    4. **Aplicaciones en la vida real:** Python se utiliza en una variedad de campos y sectores, como desarrollo web (Django, Flask), análisis de datos (pandas, NumPy), inteligencia artificial y aprendizaje automático (TensorFlow, PyTorch), automatización de tareas (automatización de tareas, scripting), desarrollo de videojuegos y más.
    5. **Oportunidades laborales:** Dada su versatilidad y popularidad, el conocimiento de Python puede abrirte puertas en el mercado laboral. Muchas empresas buscan desarrolladores de Python para una amplia gama de proyectos, lo que puede brindarte oportunidades emocionantes y bien remuneradas.
    6. **Lenguaje de enseñanza:** Python se utiliza ampliamente como lenguaje de enseñanza en cursos de programación y ciencias de la computación. Esto se debe a su sintaxis amigable y a su capacidad para ayudar a los estudiantes a comprender los conceptos de programación sin abrumarlos con detalles técnicos.
    7. **Rápido desarrollo de prototipos:** Python permite desarrollar prototipos de manera rápida y eficiente. Esto es especialmente útil en entornos donde se necesita iterar rápidamente para probar ideas y conceptos antes de comprometerse con un desarrollo más extenso.
    8. **Gran cantidad de recursos educativos:** Hay una amplia gama de recursos educativos gratuitos y de pago disponibles para aprender Python, incluidos tutoriales en línea, cursos en plataformas educativas, libros y videos.
- **Variables en Python**
    
    En Python, una variable es un nombre que se utiliza para almacenar un valor o una referencia a un objeto en la memoria. Las variables son una parte fundamental de la programación, ya que te permiten almacenar y manipular datos de diferentes tipos. Aquí tienes algunos conceptos básicos sobre cómo trabajar con variables en Python:
    
    1. **Declaración de variables:** En Python, no necesitas declarar explícitamente el tipo de una variable antes de usarla. Puedes simplemente asignar un valor a un nombre y Python determinará automáticamente el tipo de datos.
        
        ```python
        
        edad = 25
        nombre = "Juan"
        pi = 3.14159
        ```
        
    2. **Nombres de variables:** Los nombres de variables deben seguir ciertas reglas. Deben comenzar con una letra (mayúscula o minúscula) o un guión bajo (_) y pueden contener letras, números y guiones bajos. No pueden comenzar con un número ni contener espacios ni caracteres especiales.
    3. **Asignación de valores:** Para asignar un valor a una variable, simplemente utiliza el operador de asignación (=).
        
        ```python
        
        x = 10
        mensaje = "Hola, mundo"
        ```
        
    4. **Tipos de datos:** Python tiene varios tipos de datos integrados, como enteros (int), flotantes (float), cadenas (str), listas (list), tuplas (tuple), conjuntos (set), diccionarios (dict), y más.
        
        ```python
        
        entero = 42
        flotante = 3.14
        cadena = "Hola"
        lista = [1, 2, 3]
        ```
        
    5. **Operaciones con variables:** Puedes realizar operaciones matemáticas y manipulaciones de datos utilizando variables.
        
        ```python
        
        suma = x + y
        concatenacion = nombre + " " + apellido
        ```
        
    6. **Reasignación de variables:** Puedes cambiar el valor almacenado en una variable después de su asignación inicial.
        
        ```python
        
        x = 5
        x = x + 1  # x ahora es 6
        ```
        
    7. **Concatenación de cadenas:** Puedes combinar cadenas utilizando el operador **`+`**.
        
        ```python
        
        nombre = "María"
        apellido = "García"
        nombre_completo = nombre + " " + apellido
        ```
        
    8. **Comentarios:** Puedes agregar comentarios en tu código utilizando el símbolo **`#`**. Los comentarios no se ejecutan y son útiles para explicar el propósito o la funcionalidad de tu código.
        
        ```python
        
        # Esto es un comentario
        edad = 30  # Esto es otro comentario
        ```
        
- **Tipos de datos**
    
    En Python, hay varios tipos de datos integrados que se utilizan para representar diferentes tipos de información. Aquí tienes una descripción de los tipos de datos más comunes en Python:
    
    1. **Enteros (int):** Representan números enteros positivos o negativos sin decimales.
        
        ```python
        
        edad = 25
        temperatura = -10
        ```
        
    2. **Flotantes (float):** Representan números con decimales.
        
        ```python
        
        altura = 1.75
        pi = 3.14159
        ```
        
    3. **Cadenas (str):** Representan texto y se definen entre comillas simples o dobles.
        
        ```python
        
        nombre = "Juan"
        mensaje = 'Hola, ¿cómo estás?
        ```
        
    4. **Booleanos (bool):** Representan valores de verdad, es decir, verdadero (True) o falso (False). Son fundamentales para la lógica y las decisiones en la programación.
        
        ```python
        
        esta_lloviendo = True
        es_de_dia = Fals
        ```
        
    5. **Listas (list):** Representan una colección ordenada y mutable de elementos. Pueden contener elementos de diferentes tipos.
        
        ```python
        
        numeros = [1, 2, 3, 4, 5]
        nombres = ["María", "Juan", "Luis"]
        
        ```
        
    6. **Tuplas (tuple):** Son similares a las listas, pero son inmutables, es decir, no se pueden modificar una vez creadas.
        
        ```python
        
        coordenadas = (10, 20)
        colores = ("rojo", "verde", "azul")
        ```
        
    7. **Conjuntos (set):** Representan una colección no ordenada de elementos únicos. No permiten elementos duplicados.
        
        ```python
        
        numeros_primos = {2, 3, 5, 7, 11}
        ```
        
    8. **Diccionarios (dict):** Representan una colección de pares clave-valor. Cada clave es única y se utiliza para acceder a su valor correspondiente.
        
        ```python
        
        persona = {"nombre": "Ana", "edad": 30, "profesion": "ingeniera"}
        ```
        
    9. **None:** Representa la ausencia de un valor. Se utiliza para indicar que una variable no tiene un valor válido.
        
        ```python
        
        resultado = None
        ```
        
    
    Estos son algunos de los tipos de datos más comunes en Python. Cada tipo de dato tiene sus propias características y métodos asociados para realizar operaciones específicas. Al comprender cómo funcionan estos tipos de datos, podrás manejar diferentes tipos de información en tus programas de manera efectiva.
    
- **Transformación de tipos**
    
    La transformación de tipos, también conocida como conversión de tipos, se refiere al proceso de cambiar un valor de un tipo de dato a otro. En Python, puedes realizar transformaciones de tipos utilizando funciones y operadores específicos. Aquí hay algunos ejemplos de cómo hacerlo:
    
    1. **Casting explícito:** Puedes utilizar funciones integradas para convertir explícitamente un valor de un tipo de dato a otro. Algunas de las funciones de conversión más comunes son **`int()`**, **`float()`**, **`str()`**, **`list()`**, **`tuple()`**, **`set()`**, **`dict()`**.
        
        ```python
        
        numero = 42
        numero_str = str(numero)  # Convierte el número a una cadena
        flotante = float(numero)  # Convierte el número a un flotante
        ```
        
    2. **Enteros y flotantes:**
        
        ```python
        
        entero = int(3.14)  # Convierte el flotante a un entero (resultará en 3)
        flotante = float(5)  # Convierte el entero a un flotante (resultará en 5.0)
        ```
        
    3. **Cadenas y números:**
        
        ```python
        
        numero_str = "123"
        numero_int = int(numero_str)  # Convierte la cadena a un entero
        numero_float = float(numero_str)  # Convierte la cadena a un flotante
        ```
        
    4. **Listas, tuplas y conjuntos:**
        
        ```python
        
        lista = [1, 2, 3]
        tupla = tuple(lista)  # Convierte la lista a una tupla
        conjunto = set(lista)  # Convierte la lista a un conjunto
        ```
        
    5. **Diccionarios:**
        
        ```python
        
        pares = [("a", 1), ("b", 2)]
        diccionario = dict(pares)  # Convierte una lista de pares clave-valor a un diccionario
        ```
        
    6. **Uso de operadores y funciones para transformación:**
        
        Puedes usar operadores aritméticos para transformar tipos, como convertir un entero a flotante mediante una operación:
        
        ```python
        
        x = 5
        y = x + 0.0  # Convierte x a un flotante
        ```
        
    7. **Manejo de errores en transformaciones:**
        
        Es importante tener en cuenta que algunas conversiones de tipos pueden causar errores si los valores no son compatibles. Por ejemplo, intentar convertir una cadena que no representa un número en un entero generará un error de tipo.
        
        ```python
        
        numero_str = "abc"
        try:
            numero_int = int(numero_str)
        except ValueError:
            print("No se pudo convertir la cadena a un entero")
        ```
        
    
    Recuerda que mientras que algunas transformaciones de tipos son directas y seguras, otras pueden requerir una manipulación más cuidadosa y estar sujetas a posibles errores. Siempre es recomendable verificar y validar los valores antes de realizar conversiones de tipos en tu código.
    
- **Operadores de comparación**
    
    Los operadores de comparación en Python se utilizan para comparar dos valores y determinar si una condición es verdadera o falsa. Estos operadores son fundamentales para la lógica y las decisiones en la programación. Aquí están los operadores de comparación más comunes:
    
    1. **Igual (==):** Comprueba si dos valores son iguales.
        
        ```python
        
        x == y  # Verdadero si x es igual a y, Falso en caso contrario
        ```
        
    2. **No igual (!=):** Comprueba si dos valores no son iguales.
        
        ```python
        
        x != y  # Verdadero si x no es igual a y, Falso en caso contrario
        ```
        
    3. **Mayor que (>):** Comprueba si un valor es mayor que otro.
        
        ```python
        
        x > y  # Verdadero si x es mayor que y, Falso en caso contrario
        ```
        
    4. **Menor que (<):** Comprueba si un valor es menor que otro.
        
        ```python
        
        x < y  # Verdadero si x es menor que y, Falso en caso contrario
        ```
        
    5. **Mayor o igual que (>=):** Comprueba si un valor es mayor o igual que otro.
        
        ```python
        
        x >= y  # Verdadero si x es mayor o igual que y, Falso en caso contrario
        ```
        
    6. **Menor o igual que (<=):** Comprueba si un valor es menor o igual que otro.
        
        ```python
        
        x <= y  # Verdadero si x es menor o igual que y, Falso en caso contrario
        ```
        
    
    Estos operadores devuelven un valor booleano, es decir, **`True`** (verdadero) o **`False`** (falso), dependiendo de si se cumple la condición de comparación. Puedes combinar operadores de comparación utilizando operadores lógicos como **`and`** (y) y **`or`** (o) para realizar comparaciones más complejas.
    
    ```python
    
    x = 10
    y = 5
    z = 7
    
    resultado = (x > y) and (z < y)  # Falso, ya que ambas condiciones no se cumplen
    ```
    
    También puedes usar los operadores de comparación junto con las estructuras de control, como los condicionales **`if`**, para tomar decisiones en tu código basadas en las comparaciones de valores.
    
- **Comparación de números flotantes**
    
    Comparar números flotantes en programación puede ser un poco complicado debido a la representación binaria de los números de punto flotante en la computadora. Debido a esta representación, pueden surgir problemas de precisión al comparar números flotantes directamente. Aquí hay algunos consejos para manejar comparaciones de números flotantes en Python:
    
    1. **Evita comparaciones directas:** En general, es una buena práctica evitar comparar números flotantes directamente utilizando operadores como **`==`**. En su lugar, puedes comparar la diferencia entre los números para determinar si son lo suficientemente cercanos.
        
        ```python
        
        a = 0.1 + 0.2
        b = 0.3
        
        if abs(a - b) < 1e-10:  # Comparación utilizando una pequeña tolerancia
            print("Los números son aproximadamente iguales")
        ```
        
    2. **Utiliza una tolerancia:** En lugar de comparar números flotantes exactos, compáralos utilizando una pequeña tolerancia. Esto tiene en cuenta la posible falta de precisión debido a la representación binaria.
    3. **Funciones de comparación personalizadas:** Puedes crear tus propias funciones para comparar números flotantes con una tolerancia específica.
        
        ```python
        
        def comparar_flotantes(a, b, tolerancia=1e-10):
            return abs(a - b) < tolerancia
        
        if comparar_flotantes(a, b):
            print("Los números son aproximadamente iguales")
        
        ```
        
    4. **Módulo `math.isclose()`:** En Python 3.5 y versiones posteriores, el módulo **`math`** proporciona la función **`isclose()`** que permite comparar números flotantes con una tolerancia específica.
        
        ```python
        
        import math
        
        if math.isclose(a, b, rel_tol=1e-10):
            print("Los números son aproximadamente iguales")
        ```
        
    
    Recuerda que la elección de la tolerancia dependerá del contexto y la precisión requerida en tu aplicación. Siempre es importante tener en cuenta las limitaciones de precisión al comparar números flotantes y utilizar enfoques que mitiguen los problemas de precisión inherentes a las operaciones con punto flotante.
    
- **Operadores lógicos**
    
    Los operadores lógicos en Python se utilizan para realizar operaciones lógicas entre valores booleanos (verdadero o falso) y para combinar y evaluar expresiones booleanas. Los operadores lógicos más comunes son:
    
    1. **Y lógico (and):** Devuelve **`True`** si ambos operandos son **`True`**, de lo contrario, devuelve **`False`**.
        
        ```python
        
        x = True
        y = False
        resultado = x and y  # Resultado será False
        
        ```
        
    2. **O lógico (or):** Devuelve **`True`** si al menos uno de los operandos es **`True`**, de lo contrario, devuelve **`False`**.
        
        ```python
        
        x = True
        y = False
        resultado = x or y  # Resultado será True
        
        ```
        
    3. **No lógico (not):** Devuelve el valor opuesto de un operando booleano. Si el operando es **`True`**, devuelve **`False`**, y si el operando es **`False`**, devuelve **`True`**.
        
        ```python
        
        x = True
        resultado = not x  # Resultado será Fals
        ```
        
    
    Estos operadores lógicos se utilizan para construir expresiones booleanas más complejas. También se pueden combinar en expresiones lógicas que involucren múltiples operaciones.
    
    Ejemplo de expresión lógica con operadores lógicos:
    
    ```python
    pythonCopy code
    edad = 25
    tiene_licencia = True
    
    puede_conducir = edad >= 18 and tiene_licencia
    ```
    
    En este ejemplo, la variable **`puede_conducir`** será **`True`** si la edad es mayor o igual a 18 y si la persona tiene una licencia de conducir.
    
    Los operadores lógicos son fundamentales para la toma de decisiones y la construcción de estructuras condicionales en la programación. Puedes usarlos para evaluar condiciones y controlar el flujo de tu programa en función de los valores booleanos resultantes.
    
- **Condicionales**
    
    Las estructuras condicionales en Python te permiten controlar el flujo de ejecución de tu programa en función de condiciones específicas. Esto te permite tomar decisiones y ejecutar diferentes bloques de código según se cumplan o no ciertas condiciones. Los condicionales se implementan principalmente mediante la instrucción **`if`**, y pueden incluir cláusulas adicionales como **`elif`** y **`else`**. Aquí hay un ejemplo básico de cómo funcionan las estructuras condicionales en Python:
    
    ```python
    
    edad = 18
    
    if edad >= 18:
        print("Eres mayor de edad")
    else:
        print("Eres menor de edad")
    ```
    
    En este ejemplo, se evalúa si la variable **`edad`** es mayor o igual a 18. Si la condición se cumple, se ejecuta el bloque de código indentado bajo **`if`**. Si la condición no se cumple, se ejecuta el bloque de código indentado bajo **`else`**.
    
    Puedes agregar condiciones adicionales utilizando la cláusula **`elif`** (que significa "else if"), lo que te permite evaluar múltiples condiciones en secuencia:
    
    ```python
    
    nota = 85
    
    if nota >= 90:
        print("Tienes una calificación A")
    elif nota >= 80:
        print("Tienes una calificación B")
    elif nota >= 70:
        print("Tienes una calificación C")
    else:
        print("Tienes una calificación inferior a C"
    ```
    
    En este ejemplo, el programa evalúa la nota y muestra el mensaje correspondiente según el rango en el que se encuentre.
    
    También puedes combinar condiciones utilizando operadores lógicos para crear expresiones más complejas:
    
    ```python
    pythonCopy code
    temperatura = 28
    humedad = 80
    
    if temperatura > 30 and humedad > 70:
        print("Hace calor y está húmedo")
    elif temperatura > 30:
        print("Hace calor")
    elif humedad > 70:
        print("Está húmedo")
    else:
        print("Las condiciones son normales")
    ```
    
    Estos son solo ejemplos simples de cómo puedes usar estructuras condicionales en Python. Las estructuras condicionales son fundamentales para controlar el flujo de tu programa y tomar decisiones basadas en diferentes situaciones. Puedes anidar múltiples estructuras condicionales y combinarlas con otros conceptos de programación para crear programas más complejos y funcionales.
    
- **Métodos de los strings**
    
    Los métodos de cadenas (strings) en Python son funciones incorporadas que te permiten realizar diversas operaciones y manipulaciones en las cadenas. Aquí tienes una lista de algunos métodos de cadenas comunes en Python:
    
    1. **`len()`:** Devuelve la longitud de la cadena (número de caracteres).
        
        ```python
        
        mensaje = "Hola, mundo"
        longitud = len(mensaje)  # Devuelve 11
        ```
        
    2. **`lower()`:** Convierte la cadena a minúsculas.
        
        ```python
        
        texto = "Hola, Mundo"
        en_minusculas = texto.lower()  # Devuelve "hola, mundo"
        ```
        
    3. **`upper()`:** Convierte la cadena a mayúsculas.
        
        ```python
        
        texto = "Hola, Mundo"
        en_mayusculas = texto.upper()  # Devuelve "HOLA, MUNDO"
        
        ```
        
    4. **`capitalize()`:** Convierte la primera letra de la cadena en mayúscula y el resto en minúsculas.
        
        ```python
        
        texto = "hola, mundo"
        capitalizado = texto.capitalize()  # Devuelve "Hola, mundo"
        ```
        
    5. **`title()`:** Convierte cada palabra en la cadena en mayúscula.
        
        ```python
        
        texto = "hola, mundo"
        titulado = texto.title()  # Devuelve "Hola, Mundo"
        ```
        
    6. **`strip()`:** Elimina espacios en blanco al inicio y al final de la cadena.
        
        ```python
        
        cadena = "   texto con espacios   "
        sin_espacios = cadena.strip()  # Devuelve "texto con espacios"
        ```
        
    7. **`split()`:** Divide la cadena en una lista de subcadenas utilizando un separador especificado.
        
        ```python
        
        frase = "Hola, cómo estás?"
        palabras = frase.split(", ")  # Devuelve ["Hola", "cómo estás?"]
        ```
        
    8. **`join()`:** Combina elementos de una lista en una cadena utilizando el separador especificado.
        
        ```python
        
        palabras = ["Hola", "cómo", "estás?"]
        frase = ", ".join(palabras)  # Devuelve "Hola, cómo, estás?"
        ```
        
    9. **`replace()`:** Reemplaza un subtexto por otro en la cadena.
        
        ```python
        
        texto = "Hola, mundo"
        modificado = texto.replace("mundo", "Python")  # Devuelve "Hola, Python"
        ```
        
    10. **`find()`:** Busca la posición de un subtexto en la cadena. Devuelve -1 si no se encuentra.
        
        ```python
        
        texto = "Hola, mundo"
        posicion = texto.find("mundo")  # Devuelve 6
        ```
        
    11. **`startswith()` y `endswith()`:** Comprueban si la cadena comienza o termina con un subtexto especificado.
        
        ```python
        
        texto = "Hola, mundo"
        comienza = texto.startswith("Hola")  # Devuelve True
        termina = texto.endswith("mundo")  # Devuelve True
        ```
        
    
    Estos son solo algunos ejemplos de los muchos métodos disponibles para trabajar con cadenas en Python. Cada método tiene su propio propósito y puede ser útil en diferentes situaciones. Puedes consultar la documentación oficial de Python para obtener una lista completa de los métodos de cadenas y aprender más sobre cómo usarlos: **[https://docs.python.org/3/library/stdtypes.html#string-methods](https://docs.python.org/3/library/stdtypes.html#string-methods)**
    
- **Indexing y Slicing**
    
    La indexación y el rebanado (slicing) son operaciones comunes que se realizan en secuencias, como las cadenas (strings), listas y tuplas en Python. Te permiten acceder a elementos individuales o a subconjuntos de una secuencia. Aquí te explico cómo funcionan:
    
    ### **Indexación:**
    
    La indexación se utiliza para acceder a un elemento individual dentro de una secuencia. En Python, los índices comienzan desde 0 para el primer elemento, -1 para el último elemento y así sucesivamente.
    
    Ejemplo de indexación en una cadena:
    
    ```python
    
    texto = "Python"
    primer_caracter = texto[0]     # Devuelve "P"
    ultimo_caracter = texto[-1]    # Devuelve "n"
    ```
    
    ### **Slicing (Rebanado):**
    
    El rebanado se utiliza para obtener una subsecuencia de elementos de una secuencia. Se especifica un rango utilizando dos índices separados por dos puntos (**`:`**). El índice de inicio está incluido, pero el índice de finalización no lo está.
    
    Ejemplo de rebanado en una cadena:
    
    ```python
    
    texto = "Python es genial"
    subcadena = texto[0:6]     # Devuelve "Python"
    parte_media = texto[7:9]   # Devuelve "es"
    
    ```
    
    También puedes omitir el índice de inicio o el índice de finalización para indicar que deseas comenzar desde el principio o llegar al final, respectivamente.
    
    ```python
    texto = "Python es genial"
    primeras_letras = texto[:6]    # Devuelve "Python"
    resto_del_texto = texto[7:]    # Devuelve "es genial"
    
    ```
    
    Además, puedes especificar un tercer índice para controlar el paso (step) en el que se seleccionan los elementos.
    
    ```python
    numeros = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
    pares = numeros[::2]     # Devuelve [0, 2, 4, 6, 8]
    impares = numeros[1::2]  # Devuelve [1, 3, 5, 7, 9]
    ```
    
    Estos conceptos son aplicables no solo a las cadenas, sino también a las listas y tuplas en Python. La indexación y el rebanado son herramientas poderosas para acceder y manipular los elementos de las secuencias de datos de manera eficiente.
    
- **Listas**
    
    En Python, una lista es una colección ordenada y mutable de elementos. Las listas pueden contener elementos de diferentes tipos, como números, cadenas, booleanos, otras listas y más. Las listas son una de las estructuras de datos más versátiles y utilizadas en Python. Aquí tienes una introducción a las listas y cómo trabajar con ellas:
    
    ### **Crear una Lista:**
    
    Puedes crear una lista utilizando corchetes **`[]`** y separando los elementos con comas.
    
    ```python
    
    numeros = [1, 2, 3, 4, 5]
    nombres = ["Juan", "María", "Luis"]
    mezclada = [1, "dos", True, 3.14]
    ```
    
    ### **Acceder a Elementos de una Lista:**
    
    Puedes acceder a elementos individuales de una lista utilizando la indexación.
    
    ```python
    
    nombres = ["Juan", "María", "Luis"]
    primer_nombre = nombres[0]  # Devuelve "Juan"
    ultimo_nombre = nombres[-1]  # Devuelve "Luis"
    ```
    
    ### **Modificar Elementos de una Lista:**
    
    Las listas son mutables, lo que significa que puedes cambiar sus elementos después de crearlas.
    
    ```python
    
    nombres = ["Juan", "María", "Luis"]
    nombres[1] = "Pedro"  # Modifica el segundo elemento
    ```
    
    ### **Operaciones con Listas:**
    
    - **Agregar Elementos:** Puedes agregar elementos al final de una lista utilizando el método **`append()`**.
        
        ```python
        
        numeros = [1, 2, 3]
        numeros.append(4)  # Agrega el número 4 al final
        ```
        
    - **Insertar Elementos:** Puedes insertar elementos en una posición específica utilizando el método **`insert()`**.
        
        ```python
        
        numeros = [1, 2, 3]
        numeros.insert(1, 1.5)  # Inserta 1.5 en la posición 1
        ```
        
    - **Eliminar Elementos:** Puedes eliminar elementos utilizando el método **`remove()`** o la instrucción **`del`**.
        
        ```python
        
        numeros = [1, 2, 3, 4, 5]
        numeros.remove(3)  # Elimina el número 3
        del numeros[1]     # Elimina el segundo elemento
        ```
        
    - **Longitud de la Lista:** Puedes obtener la longitud de una lista utilizando la función **`len()`**.
        
        ```python
        
        numeros = [1, 2, 3, 4, 5]
        longitud = len(numeros)  # Devuelve 5
        ```
        
    - **Ordenar una Lista:** Puedes ordenar una lista utilizando el método **`sort()`**.
        
        ```python
        
        numeros = [4, 2, 1, 3, 5]
        numeros.sort()  # Ordena la lista en orden ascendente
        ```
        
    - **Reversar una Lista:** Puedes invertir el orden de los elementos utilizando el método **`reverse()`**.
        
        ```python
        
        numeros = [1, 2, 3, 4, 5]
        numeros.reverse()  # Invierte el orden de la lista
        ```
        
    
    Estos son solo algunos ejemplos de las operaciones que puedes realizar con listas en Python. Las listas son fundamentales en la programación y te permiten almacenar, manipular y organizar datos de manera eficiente.
    
- **Tuplas**
    
    En Python, una tupla es una colección ordenada e inmutable de elementos. A diferencia de las listas, las tuplas no pueden modificarse una vez que se crean, lo que significa que no se pueden agregar, eliminar o cambiar elementos después de su creación. Las tuplas se utilizan para almacenar elementos que no deben cambiar, como coordenadas, datos constantes, etc. Aquí tienes una introducción a las tuplas y cómo trabajar con ellas:
    
    ### **Crear una Tupla:**
    
    Puedes crear una tupla utilizando paréntesis **`()`** y separando los elementos con comas.
    
    ```python
    
    coordenadas = (3, 4)
    nombres = ("Juan", "María", "Luis")
    mezclada = (1, "dos", True, 3.14)
    ```
    
    ### **Acceder a Elementos de una Tupla:**
    
    Puedes acceder a elementos individuales de una tupla utilizando la indexación, al igual que con las listas.
    
    ```python
    
    nombres = ("Juan", "María", "Luis")
    primer_nombre = nombres[0]  # Devuelve "Juan"
    ultimo_nombre = nombres[-1]  # Devuelve "Luis"
    ```
    
    ### **Ventajas de las Tuplas:**
    
    1. **Inmutabilidad:** La principal ventaja de las tuplas es que son inmutables, lo que significa que una vez creadas, no se pueden modificar. Esto puede ser útil para garantizar que ciertos datos no cambien accidentalmente.
    2. **Uso en Diccionarios:** Las tuplas se pueden utilizar como claves en diccionarios de Python debido a su inmutabilidad, mientras que las listas no pueden utilizarse como claves.
    3. **Eficiencia:** Dado que las tuplas son inmutables, pueden ser más eficientes en términos de memoria y rendimiento en ciertos casos.
    
    ### **Operaciones con Tuplas:**
    
    - **Indexación y Slicing:** Puedes acceder a elementos individuales o rebanadas de una tupla de manera similar a las listas.
        
        ```python
        
        coordenadas = (3, 4)
        x = coordenadas[0]  # Devuelve 3
        y = coordenadas[1]  # Devuelve 4
        ```
        
    - **Longitud de la Tupla:** Puedes obtener la longitud de una tupla utilizando la función **`len()`**.
        
        ```python
        nombres = ("Juan", "María", "Luis")
        longitud = len(nombres)  # Devuelve 3
        ```
        
    - **Desempaquetado de Tuplas:** Puedes asignar los elementos de una tupla a variables individuales mediante el desempaquetado de tuplas.
        
        ```python
        
        punto = (3, 4)
        x, y = punto  # x = 3, y = 4
        ```
        
    - **Concatenación de Tuplas:** Puedes concatenar tuplas utilizando el operador **`+`**.
        
        ```python
        
        tupla1 = (1, 2)
        tupla2 = (3, 4)
        concatenada = tupla1 + tupla2  # Devuelve (1, 2, 3, 4)
        ```
        
    
    En resumen, las tuplas son colecciones inmutables de elementos en Python. Si tienes datos que no deben cambiar después de su creación, las tuplas pueden ser una buena opción. Sin embargo, si necesitas estructuras que puedan modificarse, las listas son más apropiadas.
    
- **Diccionarios**
    
    En Python, un diccionario es una estructura de datos que permite almacenar y organizar pares de elementos clave-valor. Cada clave en un diccionario está asociada a un valor, y puedes usar la clave para acceder rápidamente al valor correspondiente. Los diccionarios son muy útiles cuando necesitas mapear información o realizar búsquedas eficientes basadas en claves. Aquí tienes una introducción a los diccionarios y cómo trabajar con ellos:
    
    ### **Crear un Diccionario:**
    
    Puedes crear un diccionario utilizando llaves **`{}`** y separando los pares clave-valor con comas. Cada par clave-valor se separa con dos puntos **`:`**.
    
    ```python
    
    persona = {
        "nombre": "Juan",
        "edad": 30,
        "profesion": "ingeniero"
    }
    ```
    
    ### **Acceder a Valores por Clave:**
    
    Puedes acceder al valor de un diccionario utilizando la clave correspondiente.
    
    ```python
    
    persona = {
        "nombre": "Juan",
        "edad": 30,
        "profesion": "ingeniero"
    }
    
    nombre = persona["nombre"]  # Devuelve "Juan"
    edad = persona["edad"]      # Devuelve 30
    ```
    
    ### **Modificar Valores de un Diccionario:**
    
    Puedes cambiar el valor asociado a una clave específica en un diccionario.
    
    ```python
    
    persona = {
        "nombre": "Juan",
        "edad": 30,
        "profesion": "ingeniero"
    }
    
    persona["edad"] = 31  # Cambia la edad a 31
    ```
    
    ### **Agregar Nuevos Elementos a un Diccionario:**
    
    Puedes agregar nuevos pares clave-valor a un diccionario.
    
    ```python
    
    persona = {
        "nombre": "Juan",
        "edad": 30,
        "profesion": "ingeniero"
    }
    
    persona["ciudad"] = "Lima"  # Agrega la clave "ciudad" con el valor "Lima"
    ```
    
    ### **Eliminar Elementos de un Diccionario:**
    
    Puedes eliminar un par clave-valor utilizando la instrucción **`del`**.
    
    ```python
    
    persona = {
        "nombre": "Juan",
        "edad": 30,
        "profesion": "ingeniero"
    }
    
    del persona["edad"]  # Elimina la clave "edad" y su valor
    ```
    
    ### **Métodos de Diccionarios:**
    
    1. **`keys()`:** Devuelve una vista de las claves en el diccionario.
        
        ```python
        
        diccionario = {"a": 1, "b": 2, "c": 3}
        claves = diccionario.keys()  # Devuelve dict_keys(['a', 'b', 'c'])
        ```
        
    2. **`values()`:** Devuelve una vista de los valores en el diccionario.
        
        ```python
        
        diccionario = {"a": 1, "b": 2, "c": 3}
        valores = diccionario.values()  # Devuelve dict_values([1, 2, 3])
        ```
        
    3. **`items()`:** Devuelve una vista de los pares clave-valor en el diccionario.
        
        ```python
        
        diccionario = {"a": 1, "b": 2, "c": 3}
        items = diccionario.items()  # Devuelve dict_items([('a', 1), ('b', 2), ('c', 3)])
        ```
        
    4. **`get()`:** Devuelve el valor asociado a una clave específica. Si la clave no existe, puedes proporcionar un valor predeterminado.
        
        ```python
        
        diccionario = {"a": 1, "b": 2, "c": 3}
        valor = diccionario.get("b")  # Devuelve 2
        valor_default = diccionario.get("d", 0)  # Devuelve 0 porque "d" no existe
        ```
        
    5. **`pop()`:** Elimina y devuelve el valor asociado a una clave específica.
        
        ```python
        
        diccionario = {"a": 1, "b": 2, "c": 3}
        valor = diccionario.pop("b")  # Elimina "b" y devuelve 2
        ```
        
    6. **`popitem()`:** Elimina y devuelve un par clave-valor arbitrario del diccionario.
        
        ```python
        
        diccionario = {"a": 1, "b": 2, "c": 3}
        par = diccionario.popitem()  # Elimina un par arbitrario, como ('c', 3)
        ```
        
    7. **`update()`:** Actualiza el diccionario con pares clave-valor de otro diccionario o de una secuencia de pares clave-valor.
        
        ```python
        
        diccionario = {"a": 1, "b": 2}
        diccionario_nuevo = {"b": 3, "c": 4}
        diccionario.update(diccionario_nuevo)  # Actualiza con {"b": 3, "c": 4
        ```
        
    8. **`clear()`:** Elimina todos los elementos del diccionario, dejándolo vacío.
        
        ```python
        pythonCopy code
        diccionario = {"a": 1, "b": 2, "c": 3}
        diccionario.clear()  # El diccionario ahora está vacío
        ```
        
    
    Estos son solo algunos de los métodos disponibles para trabajar con diccionarios en Python. Puedes consultar la documentación oficial de Python para obtener una lista completa de los métodos y aprender más sobre cómo utilizarlos: **[https://docs.python.org/3/library/stdtypes.html#dict](https://docs.python.org/3/library/stdtypes.html#dict)**
    
- **Loops**
    
    Los bucles (loops) son una parte fundamental de la programación que te permiten repetir un bloque de código varias veces. En Python, existen dos tipos principales de bucles: el bucle **`for`** y el bucle **`while`**. Aquí te proporciono información sobre ambos tipos de bucles:
    
    ### **Bucle `for`:**
    
    El bucle **`for`** se utiliza para iterar sobre una secuencia (como una lista, una tupla o una cadena) o cualquier objeto iterable. Cada elemento de la secuencia se toma uno por uno y se ejecuta un bloque de código para cada elemento.
    
    ```python
    nombres = ["Juan", "María", "Luis"]
    
    for nombre in nombres:
        print(nombre)
    ```
    
    ### **Bucle `while`:**
    
    El bucle **`while`** se utiliza para repetir un bloque de código mientras una condición sea verdadera. Se ejecutará el bloque de código una y otra vez hasta que la condición se vuelva falsa.
    
    ```python
    contador = 0
    
    while contador < 5:
        print(contador)
        contador += 1
    ```
    
    ### **Instrucciones de Control de Bucles:**
    
    - **`break`:** Se utiliza para salir de un bucle de manera prematura, incluso si la condición del bucle aún es verdadera.
        
        ```python
        numeros = [1, 2, 3, 4, 5]
        
        for num in numeros:
            if num == 3:
                break
            print(num)
        ```
        
    - **`continue`:** Se utiliza para omitir el resto del ciclo actual y continuar con la siguiente iteración.
        
        ```python
        numeros = [1, 2, 3, 4, 5]
        
        for num in numeros:
            if num == 3:
                continue
            print(num)
        ```
        
    - **`else` en bucle `for` y `while`:** Puedes usar la cláusula **`else`** para ejecutar un bloque de código después de que el bucle haya terminado normalmente (sin usar **`break`**).
        
        ```python
        numeros = [1, 2, 3, 4, 5]
        
        for num in numeros:
            print(num)
        else:
            print("Fin del bucle")
        ```
        
    
    ### **Bucles Anidados:**
    
    Puedes anidar bucles dentro de otros bucles para realizar iteraciones más complejas.
    
    ```python
    
    for i in range(3):
        for j in range(3):
            print(i, j)
    ```
    

“Notas generadas con la asistencia de ChatGPT de OpenAI.”