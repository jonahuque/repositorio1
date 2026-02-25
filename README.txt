Ejercicio 3

Public static int calcularPrecioFinal(int precioBase, int descuento) { 
if (precioBase < 0 || descuento < 0 || descuento > 100) {
 		System.out.println("Valores de entrada inválidos"); 
} 
return precioBase - (precioBase * descuento / 100); 
}

Ejercicio 5
public static int maximo(int[] datos) {
    if (datos == null || datos.length == 0) throw new IllegalArgumentException();
    int max = datos[0]; // Usamos el primer elemento como referencia inicial
    for (int i = 1; i < datos.length; i++) {
        if (datos[i] > max) {
            max = datos[i];
        }
    }
    return max;
}
