# Evidencia-3-Proyecto-final

Este proyecto implementa el **método numérico de la secante** en Java para encontrar una raíz aproximada de una función no lineal. El programa permite al usuario ingresar los datos necesarios desde la consola y muestra paso a paso el proceso de cálculo hasta encontrar la raíz o alcanzar el número máximo de iteraciones.

---

## 📌 Descripción del Proyecto

El programa aplica el **método de la secante**, una técnica iterativa utilizada para encontrar raíces de funciones reales. A diferencia del método de Newton-Raphson, no requiere el cálculo de derivadas, lo que lo hace útil para funciones donde derivarlas es complejo o incómodo.

El usuario puede definir:
- Los valores iniciales `x0` y `x1`.
- La tolerancia deseada.
- El número máximo de iteraciones.

---

## ⚙️ Instrucciones de Uso

1. **Clona el repositorio** o descarga el archivo `.java`.
   ```bash
   git clone https://github.com/tu_usuario/nombre_del_repositorio.git
   cd nombre_del_repositorio
## Codigo:
import java.util.Scanner;

public class MetodoSecante {

    // Definimos la función f(x) cuya raíz se busca
    public static double f(double x) {
        // Puedes cambiar esta función según sea necesario
        return Math.pow(x, 3) - x - 2; // f(x) = x^3 - x - 2
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

       
