------
- Tags: #pivoting 
------
# Definición

> El **Pivoting** (también conocido como “hopping”) es una técnica utilizada en pruebas de penetración y en el análisis de redes que implica el uso de una máquina comprometida para atacar otras máquinas o redes en el mismo entorno.

Por ejemplo, si un atacante ha comprometido una máquina en una red corporativa, puede utilizar técnicas de pivoting para utilizar esa máquina como punto de salto para atacar otras máquinas en la misma red que de otra manera no serían accesibles. Esto se logra a través de la creación de túneles de comunicación desde la máquina comprometida a otras máquinas en la red.

El pivoting puede ser utilizado para superar restricciones de seguridad que de otra manera impedirían a un atacante acceder a determinadas máquinas o redes. Por ejemplo, si una red corporativa utiliza segmentación de red para separar diferentes partes de la red, el pivoting puede ser utilizado para superar esta restricción y permitir que un atacante salte de una red a otra.

----------

Veremos cómo desplegar un laboratorio práctico con diferentes máquinas conectadas a través de distintas redes internas, con el objetivo de poder practicar el concepto de pivoting. Esta clase es crucial para aprobar la certificación del **eCPPTv2**, pues se te presentará un laboratorio muy similar.

Aprovecharemos la ocasión para explicar varios TIPS, así como cosas a tener en cuenta de cara al examen. Veremos cómo representar la información de las máquinas comprometidas y las conexiones que estas tienen con otras máquinas a través de las redes internas configuradas, haciendo uso para ello de Obsidian.