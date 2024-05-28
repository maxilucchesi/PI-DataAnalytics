# Diccionario de datos

# Archivo ‘homicidios.xslx’

## Hoja: ‘HECHOS’

1. **ID**: identificador único del siniestro
2. **N_VICTIMAS**: cantidad de víctimas
3. **FECHA**: fecha en formato dd/mm/aaaa
4. **AAAA**: año
5. **MM**: mes
6. **DD**: día del mes
7. **HORA**: hora del siniestro
8. **HH**: franja horaria entera
9. **LUGAR_DEL_HECHO**: Dirección del hecho
10. **TIPO_DE_CALLE**: Tipo de arteria. En el caso de intersecciones, el tipo de ambas calles involucradas
   - calle: Arteria cuya calzada tiene un ancho comprendido entre cinco (5) y trece (13) metros. Inlcluye pasajes.
   - avenida: Arteria cuya calzada tiene un ancho total de por lo menos trece (13) metros.
   - autopista: Vía multicarril con calzadas para ambas manos separadas físicamente, sin cruces a nivel, con accesos controlados y sin ingreso directo desde los predios frentistas. Incluye AU 25 de mayo, AU Perito Moreno, AU Dellepiane, Av Lugones, Av. Cantilo, AU Frondizi, AU Buenos Aires - La Plata en el tramo que circula dentro de la Ciudad de Buenos Aires y Paseo del Bajo. Incluye ingresos y egresos de las mismas y distribuidores.
   - general paz: Avenida General Paz, ambos sentidos. Incluye ingresos y egresos de las mismas, distribuidores y calle colectora.
11. **Calle**: nombre de la arteria donde se produjo el hecho
12. **Altura**: altura de la arteria donde se produjo el hecho
13. **Cruce**: cruce en caso de que sea una encrucijada
14. **Dirección Normalizada**: dirección en formato normalizado USIG
15. **COMUNA**: Comuna de la ciudad (1 a 15)
16. **XY (CABA)**: geocodificación plana
17. **pos x**: longitud con separador punto. WGS84
18. **pos y**: latitud con separador punto. WGS84
19. **PARTICIPANTES**: conjunción de víctima y acusado
   - **MULTIPLE**: Cuando participan más de un vehículo como contrincantes o responsables del siniestro.
20. **VICTIMA**: Vehículo que ocupaba quien haya fallecido o resultado herido
   - **PEATON**: Víctima distinta de cualquier ocupante de un vehículo.
   - **MOTO**: Vehículo a motor no carrozado que incluye motocicletas y ciclomotores.
   - **AUTO**: Vehículo a motor destinado al transporte de personas, generalmente con cuatro ruedas.
   - **CARGAS**: Vehículo a motor destinado al transporte de cargas.
   - **BICICLETA**: Vehículo con al menos dos ruedas, que generalmente es propulsado por el esfuerzo muscular del usuario, a través de pedales u otro mecanismo similar.
   - **PASAJEROS**: Personas lesionadas que se encuentran dentro, ingresan o salen de un vehículo.
   - **MOVIL**: Vehículos de emergencia: móviles policiales, ambulancias, camiones de bomberos, etc.
   - **OTRO**: Otros vehículos.
   - **SD**: Sin datos sobre el tipo de víctima.
21. **ACUSADO**: Vehículo que ocupaba quien resultó acusado/a de provocar el siniestro
   - **AUTO**: Vehículo a motor destinado al transporte de personas, generalmente con cuatro ruedas.
   - **BICICLETA**: Vehículo con al menos dos ruedas, que generalmente es propulsado por el esfuerzo muscular del usuario, a través de pedales u otro mecanismo similar.
   - **CARGAS**: Vehículo a motor destinado al transporte de cargas.
   - **MOTO**: Vehículo a motor no carrozado que incluye motocicletas y ciclomotores.
   - **OBJETO FIJO**: Colisión contra objetos inmóviles fijados de manera permanente en la vía pública.
   - **PASAJEROS**: Personas lesionadas que se encuentran dentro, ingresan o salen de un vehículo.
   - **TREN**: Equipo móvil que se desplaza exclusivamente sobre rieles.
   - **OTRO**: Otros vehículos.
   - **SD**: Sin datos sobre el vehículo participante.

## Hoja: ‘VICTIMAS’

1. **ID_hecho**: identificador único del siniestro
2. **FECHA**: fecha en formato dd/mm/aaaa
3. **AAAA**: año
4. **MM**: mes
5. **DD**: día del mes
6. **ROL**: Posición relativa al vehículo que presentaba la víctima
7. **VICTIMA**: Vehículo que ocupaba quien haya fallecido o resultado herido
   - **PEATON**: Víctima distinta de cualquier ocupante de un vehículo, ya sea un conductor/a o un pasajero/a. Se incluyen los ocupantes o personas que empujan o arrastran un coche de bebé o una silla de ruedas o cualquier otro vehículo sin motor de pequeñas dimensiones. Se incluyen también las personas que caminan empujando una bicicleta o un ciclomotor.
   - **MOTO**: Vehículo a motor no carrozado que incluye motocicletas y ciclomotores.
   - **AUTO**: Vehículo a motor destinado al transporte de personas, generalmente con cuatro ruedas.
   - **CARGAS**: Vehículo a motor destinado al transporte de cargas.
   - **BICICLETA**: Vehículo con al menos dos ruedas, que generalmente es propulsado por el esfuerzo muscular del usuario, a través de pedales u otro mecanismo similar.
   - **PASAJEROS**: Personas lesionadas que se encuentran dentro, ingresan o salen de un vehículo.
   - **MOVIL**: Vehículos de emergencia: móviles policiales, ambulancias, camiones de bomberos, etc.
   - **OTRO**: Otros vehículos.
   - **SD**: Sin datos sobre el tipo de víctima.
8. **SEXO**: Sexo informado por fuente policial de la víctima
9. **EDAD**: Edad de la víctima al momento del siniestro
10. **FECHA_FALLECIMIENTO**: Fecha de fallecimiento de la víctima

# Archivo ‘lesiones.xslx’

## Hoja: ‘HECHOS’

1. **ID**: identificador único del siniestro
2. **N_VICTIMAS**: cantidad de víctimas
3. **FECHA**: fecha en formato dd/mm/aaaa
4. **AAAA**: año
5. **MM**: mes
6. **DD**: día del mes
7. **HORA**: hora del siniestro
8. **FRANJA_HORA**: franja horaria entera
9. **DIRECCIÓN_NORMALIZADA**: dirección en formato normalizado USIG
10. **COMUNA**: comuna de CABA con jurisdicción según la ubicación
11. **TIPO_CALLE**: Tipo de arteria. En el caso de intersecciones a nivel se clasifica según la de mayor jerarquía
   - calle
   - avenida
   - autopista
   - general paz
1. **OTRA_DIRECCIÓN**: dirección en formato alternativo
2. **CALLE**: nombre de la arteria donde se produjo el hecho
3. **ALTURA**: altura de la arteria donde se produjo el hecho
4. **CRUCE**: cruce en caso de que sea una encrucijada
5. **GEOCODIFICACIÓN_CABA**: geocodificación plana
6. **LONGITUD**: longitud con separador punto. WGS84
7. **LATITUD**: latitud con separador punto. WGS84
8. **VICTIMA**: Vehículo que ocupaba quien haya fallecido o se haya lastimado a raíz del hecho, o bien peatón/a
   - **AUTO**
   - **CAMION**
   - **UTILITARIO**
   - **CICLISTA**
   - **MIXTO**
   - **MONOPATIN**
   - **MOTO**
   - **MOVIL**
   - **PEATON**
   - **TAXI**
   - **TRANSPORTE PUBLICO**
   - **OTRO**
   - **SD**
1. **ACUSADO**: Vehículo que ocupaba quien resultó acusado/a del hecho, sin implicar culpabilidad legal
   - **AUTO**
   - **CAMION**
   - **UTILITARIO**
   - **CICLISTA**
   - **MONOPATIN**
   - **MOTO**
   - **MOVIL**
   - **OBJETO FIJO**
   - **SD**
   - **TAXI**
   - **TRANSPORTE PUBLICO**
1. **PARTICIPANTES**: conjunción de víctima y acusado
2. **MOTO**: participación de algún motovehículo, sea víctima u acusado
3. **AUTO**: participación de algún automóvil, sea víctima u acusado
4. **TRANSPORTE_PUBLICO**: participación de algún vehículo de transporte público de pasajeros, sea víctima u acusado
5. **CAMION**: participación de algún vehículo de cargas camión, sea víctima u acusado
6. **CICLISTA**: participación de algún ciclista, sea víctima u acusado
7. **GRAVEDAD**: Nivel máximo conocido de gravedad de la lesión de la(s) víctima(s) del siniestro en función del tiempo de hospitalización
   - **leve**
   - **grave**
   - **fatal**
   - **sd**

## Hoja: ‘VICTIMAS’

1. **ID_HECHO**: identificador único del siniestro
2. **AÑO**: año
3. **MES**: mes
4. **DIA**: día del mes
5. **FECHA**: fecha en formato dd/mm/aaaa
6. **VEHICULO_VICTIMA**: Vehículo que ocupaba quien haya fallecido o se haya lastimado a raíz del hecho, o bien peatón/a
   - AUTO
   - CAMION
   - UTILITARIO
   - CICLISTA
   - MIXTO
   - MONOPATIN
   - MOTO
   - MOVIL
   - PEATON
   - TAXI
   - TRANSPORTE PUBLICO
   - OTRO
   - SD
7. **SEXO**: Sexo de la víctima según registro policial
8. **EDAD_VICTIMA**: Edad en años enteros de la víctima en registro policial
9. **GRAVEDAD**: Nivel máximo conocido de gravedad de la lesión de la víctima del siniestro en función del tiempo de hospitalización
   - leve
   - grave
   - fatal
   - sd

