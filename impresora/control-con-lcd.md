# Control con LCD

La impresora puede operarse desde el panel LCD para mover ejes, ajustar temperaturas y lanzar impresiones desde tarjeta SD.

## Impresión desde SD

1. Seleccionar la opción de impresión desde SD.
2. Elegir el archivo G-code almacenado en la tarjeta.
3. Verificar que la cama y el hotend alcancen la temperatura configurada antes de iniciar.

## Auto home

1. Entrar en el menú de preparación.
2. Seleccionar la opción Auto Home.
3. Confirmar que los ejes regresen a la posición de referencia.

## Movimiento manual de ejes

1. Entrar en el menú Prepare.
2. Ir a Move axis.
3. Elegir el desplazamiento deseado: 10 mm, 1 mm o 0.1 mm.
4. Seleccionar X, Y, Z o extrusor.

## Deshabilitar steppers

1. Entrar en el menú Prepare.
2. Seleccionar Disable steppers para mover los ejes manualmente.

## Ajuste de temperatura

1. Si no configurás la temperatura del extrusor y de la cama caliente en el G-code, tenés que calentarlos manualmente a la temperatura adecuada antes de imprimir.
2. Si no indicás el auto home de todos los ejes en el G-code, tenés que hacer el auto home manualmente antes de iniciar la impresión.

* Extrusor: Control > Temperature > Nozzle > Girar perilla > Apretar botón.
* Cama caliente: Control > Temperature > Bed > Girar perilla.

## Observaciones

* El motor del extrusor no se mueve si la temperatura es menor a 180 °C.

## Información adiciona
[wiki con fotos y todos los pasos](https://wiki.geeetech.com/index.php/Prusa_I3_X)
