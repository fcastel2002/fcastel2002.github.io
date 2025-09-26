# Como debuggear BluePill clone con OpenOCD y STLink

En esta guía pretende ser un recurso para lograr debuggear y flashear programas en los microcontroladores clon que vienen incorporados en las placas de desarrollo conocidas como BluePill.

## Por qué surge esta guía?

Basicamente al momento de comprarme muy ilusionado una *blue pill* me topé con la triste realidad de que el IDE oficial de STM (*STMCubeIDE*) no era capaz de debuggear mi placa, por lo que evidentemente, algo relacionado a la legitimidad de mi la misma. Entonces probe el otro debugger disponible en el ide, *OpenOCD*, tampoco funcionó, pero algunos códigos de error que ya no recuerdo insinuaban algo más que "target not found", por lo que insinuaba que se podia hacer algo al respecto. Asi que investigando un poco, no habia manera de que no pudiese debuggearlo con OpenOCD ya que es un debugger bastante documentado y conocido en la comunidad, además de que tiene la gran característica de ser de codigo abierto.

--- 
Entonces, se detallaran los pasos a seguir para lograr debuggear esta placa, lo interesante es que al final vamos a poder tener nuestro codigo en VSCode, aprovechandonos de la extensión *Cortex-Debug*, además trabajar en un entorno mucho mas liviano, nos vamos a abstraer un poco de lo que es el entorno de STM para entrar un poco más en el desarrollo con cualquier microcontrolador ARM.

