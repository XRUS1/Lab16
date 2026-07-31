# Lab16; Lab 16: TransformControls + Xbox + Depth Guardarrail
Lo que hace bien: Este es el más sofisticado conceptualmente. Introduce tres capas que los otros no tienen:
Indirección: El joystick no toca el objeto. Mueve un cursor que apunta al objeto. Esto obliga al alumno a pensar en mapeos de input: ¿qué tan rápido debe moverse el cursor respecto al stick? ¿Qué pasa si hay latencia?
Control dual: El joystick mueve X/Y, el D-Pad mueve Z. El usuario debe coordinar dos inputs distintos para una misma tarea (posicionar en 3D). Esto enseña decomposición de tareas complejas en controles simples.
Guardarrail de profundidad: El depth sensing ya no es decorativo. Es un constraint dinámico que impide errores. El objeto no atraviesa la mesa porque el sistema sabe dónde está la mesa. Esto es diseño preventivo: el sistema protege al usuario de consecuencias físicas imposibles.
Su problema: Es el más lento. Mover un objeto en 3D con un joystick requiere más pasos mentales que con el dedo. Si la tarea es "pon el trofeo aquí", el dedo gana. Si la tarea es "pon el trofeo exactamente a 30 cm de la mesa, alineado con el borde", el Xbox gana.
