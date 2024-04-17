#include<stdio.h>
int main()
{
int opcion;
int ruta;
printf("Bienvenido, por favor ingrese la opción que desea consultar: ");
printf("1. Saber rutas de buses");
printf("2. Conocer rutas que funcionan en feriados");
scanf("%d",&opcion);
if(opcion==2)
{
    printf("Las rutas que funcionan los dias feriado son: C73, L10, G22 y 6-1");
}
else if(opcion==1)
{
    printf("¿Cuál ruta desea consultar?");
    printf("1. F60-Portal Americas");
    printf("2. J23-Las Aguas");
    scanf("%d",&ruta);
if(ruta==1)
{
    printf("Paradas: Portal Américas, Tv. 86, Banderas, carrera 43, Ricaurte, De La Sabana, calle 26, calle 34, calle 45, Marly,calle 63 y calle 76");
}
else if(ruta==2)
{
    printf("Paradas: Portal americas, patio bonito, banderas, av americas, pradera, puente aranda, ricaurte, san fason, av jimenez y Aguas");
}
else if(opcion==2)
{
    printf("Las rutas que funcionan los dias feriado son: C73, L10, G22 y 6-1");
}



}
    
    
    
    
    
    
    
}
