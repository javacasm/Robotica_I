# 📗 SESIÓN 3: Robótica Educativa con la Placa Echidna

**Duración:** 2 horas y 30 minutos (Presencial)

  

**Bloque de Contenidos:** Introducción al hardware educativo avanzado, sensores, actuadores y control físico a través de la placa Echidna Shield.

  

## 1. Introducción y Objetivos de la Sesión

En esta tercera sesión avanzamos hacia el uso de microcontroladores y electrónica integrada diseñada específicamente para entornos educativos. Utilizaremos la placa **Echidna**, un escudo (_shield_) que se acopla a microcontroladores y que destaca por incorporar múltiples sensores y actuadores directamente en la placa, evitando cableados complejos y facilitando su uso directo en el aula.

  

### Objetivos Específicos:

1. Conocer la arquitectura, componentes y funcionamiento de la placa Echidna Shield.
    
      
    
2. Diferenciar y programar elementos de entrada (sensores) y de salida (actuadores) de forma visual.
    
      
    
3. Comprender los conceptos básicos de señales digitales y analógicas en robótica educativa.
    
      
    
4. Diseñar y programar proyectos prácticos interactivos aplicados al aula (sistemas de alarma, semáforos, control lumínico).
    
      
    

## 2. Desarrollo de Contenidos y Guion de la Sesión

### ⏱️ Bloque 1 (45 min): Conociendo la Placa Echidna Shield

#### A. ¿Qué es Echidna Shield y por qué utilizarla en el aula?

- **Concepto:** Echidna Shield es una placa de expansión de hardware educativo diseñada en España que integra una gran variedad de sensores y actuadores comunes en una sola placa compacta.
    
      
    
- **Ventajas pedagógicas:**
    
      
    - Evita la frustración del montaje mediante protoboards (prototipos de circuitos con cables sueltos que suelen desconectarse fácilmente).
        
          
        
    - Permite empezar a programar de inmediato sin necesidad de soldar ni realizar conexiones complejas de circuitería.
        
          
        
    - Es altamente robusta y está pensada para resistir el trasiego diario del aula de Infantil, Primaria o Secundaria.
        
          
        

#### B. Análisis de los Componentes Integrados en la Placa

- **Actuadores (Salidas):**
    
      
    - LEDs de diferentes colores (para señalización y avisos lumínicos).
        
          
        
    - Zumbador o Buzzer (para emitir tonos, notas musicales o alarmas sonoras).
        
          
        
- **Sensores (Entradas):**
    
      
    - Sensor de luz (LDR): Mide la intensidad lumínica del ambiente.
        
          
        
    - Pulsadores integrados: Botones físicos de interacción directa.
        
          
        
    - Acelerómetro / Sensor de inclinación: Detecta la orientación y el movimiento de la placa en el espacio.
        
          
        
    - Joystick analógico: Permite capturar movimientos en ejes horizontal y vertical.
        
          
        
    - Conectores adicionales para pinzas de cocodrilo o sensores externos.
        
          
        

### ⏱️ Bloque 2 (45 min): Entornos de Programación y Comunicación

#### A. Conexión Hardware-Software

- Configuración del puerto de comunicación USB entre el ordenador y el microcontrolador con la placa Echidna.
    
      
    
- Uso de lenguajes de programación visual basados en bloques adaptados para placas compatibles con Arduino (como mBlock, ArduinoBlocks o entornos específicos compatibles).
    
      
    

#### B. Lógica de Programación con Hardware: Entradas y Salidas

- **Señales Digitales:** Valores discretos de encendido/apagado (Estados Alto/Bajo o $1$ y $0$). Ejemplo: Pulsar un botón o encender un LED.
    
      
    
- **Señales Analógicas:** Valores continuos dentro de un rango determinado. Ejemplo: La lectura de la intensidad de luz del sensor LDR o la posición de un joystick.
    
      
    
- **Estructuras Condicionales con Sensores:** Programación de reglas del tipo _"Si el sensor de luz detecta oscuridad, entonces enciende el LED automáticamente"_.
    
      
    

### ⏱️ Bloque 3 (45 min): Taller Práctico de Proyectos con Echidna

En este bloque, el profesorado realiza montajes prácticos guiados utilizando las capacidades de la placa:

  

#### A. Proyecto 1: El Alarmero Lumínico y Sonoro

- **Objetivo:** Crear un sistema de seguridad básico utilizando el sensor de luz o el acelerómetro.
    
      
    
- **Lógica:** Si alguien levanta la placa (detectado por el acelerómetro) o cambia la luz ambiente de forma brusca, el zumbador emite una alarma intermitente y los LEDs parpadean en rojo.
    
      
    

#### B. Proyecto 2: El Semáforo Inteligente

- **Objetivo:** Simular la lógica de regulación de tráfico urbana.
    
      
    
- **Lógica:** Secuencia automatizada de luces (Verde $\rightarrow$ Ámbar $\rightarrow$ Rojo) combinada con el uso de un pulsador físico que actúa como "botón de peatones" para cortar el tráfico de vehículos de forma segura.
    
      
    

#### C. Proyecto 3: Mini Consola de Control por Joystick

- **Objetivo:** Utilizar el joystick analógico integrado para interactuar con un objeto en pantalla o controlar melodías musicales según la dirección en la que se incline la palanca.
    
      
    

### ⏱️ Bloque 4 (15 min): Puesta en Común, Resolución de Dudas y Cierre

#### A. Puesta en Común y Debate

- Análisis de las posibilidades didácticas de integrar placas con sensores y actuadores frente al uso exclusivo de pantallas o software bidimensional.
    
      
    
- Compartir posibles aplicaciones en asignaturas de ciencias, tecnología o proyectos de centro.
    
      
    

#### B. Conexión con la Sesión 4

- Avance de la última sesión: introduciremos los conceptos básicos de **Inteligencia Artificial** aplicados al aula mediante la plataforma _LearningML_ y su integración en proyectos educativos.