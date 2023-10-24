# 3.1PicoW
<pre>

    <p align=center>

Tecnológico Nacional de México
Instituto Tecnológico de Tijuana

Departamento de Sistemas y Computación
Ingeniería en Sistemas Computacionales

Semestre:
Agosto - Diciembre 2023

Materia:
Lenguajes de interfaz

Docente:
M.C. Rene Solis Reyes 

Unidad:
3

Título del trabajo:
3.1 Simulador PicoW

Estudiante:
Diaz Berumen Maria de los Angeles 21210368

    </p>

</pre>

<pre>

    <p align=left>


/*
 * Autor:   Diaz Berumen Maria de los Angeles
 * Correo:  l21210368@tectijuana.edu.mx
 * Fecha:   23/octubre/2023
 * Curso:   Lenguajes de Interfaz, TECNM Campus ITT
 * Objetivo: Este programa está diseñado para familiarizarse con la Raspberry Pi pico haciendo un hola mundo con blink.
 *
 * Historial de Revisiones:
 * 23/octubre/2023        Diaz Berumen Maria de los Angeles - Creado
 * 
 *
 */

// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);  // turn the LED on (HIGH is the voltage level)
  delay(1000);                      // wait for a second
  digitalWrite(LED_BUILTIN, LOW);   // turn the LED off by making the voltage LOW
  delay(1000);                      // wait for a second
  Serial.print("Hola Mundo");               // imprime hola mundo

}
