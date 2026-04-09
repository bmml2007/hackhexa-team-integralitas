#  Sensor Variables

Variables elegidas:
- movimiento
- sonido
Son importantes porque detectan si alguien se mueve en un horario sospechoso o si hacen ruidos extraños.
Por ejemplo: Si se instala el sensor en una tienda, este detectaria movimientos o sonidos extraños despues de la hora de cierre.

int mov=0, son=0;
{
   if(mov)
   {

    mov=mov+1;
   } System.out.println("se detecto movimiento sospechoso")else{
    System.out.println("no se detecto movimiento sospechoso"
   }

   if(son)
   {
son=son+1;
   } System.out.println("se detecto sonido sospechoso")else{
    System.out.println("no se detecto sonido sospechoso"
   }
}
