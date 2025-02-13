---
title: Conceptos Básicos de Redes
date: 2025-02-12 20:23
tags:
  - Redes
  - Básico
  - datos
---
## Como funciona un ordenador

Los ordenadores solo funcionan en **binario:** ``1 o 0``.

Un **bit** es solo puede tener uno de los dos posibles valores, para representar letras, números y caracteres especiales se representan una codificación de caracteres, donde cada símbolo tiene un valor numérico asignado, la codificación mas común es la **ASCII** en el cual cada carácter esta representado por 7 bits.

Ejemplo:
	**A** en ASCII se representa por el número **65** el cual a su vez se convierte en binario para que el ordenador pueda procesarlo, por lo que: **A** = **65** = **0100 0001**

>¿Si el sistema **ASCII** esta compuesto por 7 bits porque en binario la letra mayúscula A se presenta con 8 bits?

- Porque aunque esta basado en 7 bits, cuando se almacena un carácter en la memoria del ordenador o se transmite por la red, los datos se almacenan en bloques de 8 bits, cada paquete de 8 bits se llama Byte, porque los ordenadores están diseñados para trabajar con bytes, por eso se le añade un 0 a la izquierda.

> Forma abreviada de representar:

- bit = **b**
- byte = **B**
- Kilobyte (KB) = 1024B

> ¿Por qué los sistemas están diseñados para trabajar con bytes?

- Es una pregunta que excede mis conocimientos, pero tiene que ver con la arquitectura de la CPU, le eficiencia de la memoria.

Otra forma de codificación es **UNICODE** el cual puede representar caracteres en casi todos los idiomas, así como símbolos, emoticonos y caracteres especiales.

Ejemplo:
	**😀** tiene como valor **UNICODE = U+1F600**, ``U+`` solo es para identificar que es Unicode mientras que ``1F600`` es el valor hexadecimal que representa **😀**.
	Como **UNICODE** se convierte en binario desde hexadecimal tienes que pasarlo a decimal y de decimal a binario.
	**1F600** (hexadecimal) = **128512** (decimal) = **11111011011000000** (binario)

## Métodos comunes de Transmisión de datos

> Tipos de datos:
- **Datos voluntarios:** El usuario ``es consciente de que recopilan``.
- **Datos observados:** Datos que ``se generan por acciones del usuario``. Ejemplo: Uso de la ubicación del móvil.
- **Datos inferidos:** Datos que se ``deducen de los datos voluntarios y observados``. Ejemplo: El uso de la tarjeta de crédito implica que tu banco sabe en los sitios que sueles comprar con ella y la ubicación geográfica.

Los bits se deben convertir en señales para enviarlas por el medio.

 >El concepto de medio es el medio por el cual se transmites: cable de cobre, fibra óptica, ondas electromagnéticas.

Las señales están compuestas por patrones eléctricos u ópticos (pulsos eléctricos, señales ópticas, ondas de radio), estos patrones representan los bits.

## Ancho de banda y Rendimiento

### Ancho de banda

Los diferentes medios admiten la transferencia de bits a distintas velocidades. La velocidad de transferencia de datos se analiza en términos de ancho de banda y rendimiento.

El ancho de banda es la capacidad de un medio para transportar X cantidad de datos. Se mide en la cantidad de bits que (en teoría) puede enviarse a través de los medios en un segundo.

Las propiedades de los medios, las tecnologías y las leyes de la física intervienen para determinar el ancho de banda.

### Rendimiento

El rendimiento al igual que el ancho de banda es la medida de la transferencia de bits por los medios durante un período determinado, aunque generalmente no coinciden.

Influye:
- La cantidad de datos que se envían y reciben por la conexión.
- Los tipos de datos que se transmiten.
- La latencia creada por la cantidad de dispositivos de red encontrados entre origen y destino.

> El concepto de latencia se refiere a la cantidad de tiempo, incluida las demoras, que les toma a los datos transferirse desde el origen al fin.

El rendimiento no puede ser mas rápido que el enlace más lento de la ruta desde el dispositivo de origen hasta el destino.

Resumen:
- **Ancho de banda:** capacidad máxima teórica de la conexión, se mide en (Kbps, Mbps, Gbps)
- **Rendimiento:** es la velocidad real de la red.
- **Latencia:** mide el tiempo que tarda un dato en viajar desde origen hasta destino y se mide en milisegundos.

## Componentes, tipos y conexiones de red

### Clientes y servidores

