# Memorias-Estatica-Dinamica
Aca se presentan los dos tipos de Memorias tanto dinamica, como estatica, para la realizacion de este codigo se tomo de referencia el siguiente video: https://www.youtube.com/watch?v=Fzt1X5GNOb8&t=202s , este video nos da dos codigos en Java de los tipos de memorias, sin embargo en este repositorio encontras esos mismmos dos codigos solo que en esta ocasion estan pasados en python, donde para su realizacion hubieron modificaciones por el tipo de lenguaje donde los codigos tienen varaciaciones con respecto a los codigos en java, sin embargo en este mismo repositorio te explicare cuales son las modificaciones y diferencias de estos codigos.

Comenzaremos por el codigo en memoria dinamica:
Codigo (Python)

```python
def main():
    frutas = []
    frutas.append("Mango")
    frutas.append("Manzana")
    frutas.append("Platano")
    frutas.append("Uva")
    print(frutas)
    frutas.pop(0)
    frutas.pop(1)
    frutas.append("Sandia")
    print(frutas)

if __name__ == "__main__":
    main()
```

En el caso de este codigo, la vdd es muy similiar al codigo de java, en vez de crear una clase, se crea un metodo principal dondre agregaremos todas las frutas con el comando .append (en java es con .add) y para eliminar algun elemento usamos .pop (en java es con .remove) como tal el codigo es lo mismo, presentado casi que una misma sintaxis pero con diferentes comando que varian depende el lenguaje, y lo que hace este codigo es crear una matriz donde en este caso se iran agregando frutas, pero de igual forma va eliminando estas y agregando una nueva, en este caso sandia. 

A continuacion pasaremos con el codigo de memoria estatica:
Codigo(Python)

```python
calificaciones = []

for i in range(5):
    calificacion = int(input("Capture una Calificación: "))
    calificaciones.append(calificacion)

print("Las calificaciones guardadas son:", calificaciones)
```
Con este codigo en este caso de declara las variables calificaciones, aunque este codigo no presentan muchas similitudes con el codigo en java, debido a que en java se tiene que implementar una carpeta para el funcionamiento de este (dato importante esta parte de agregar una carpeta no es mencioanda en el video, tuve que investigar debido a que presente problemas con al ejecucion) y en este caso como entra la memoria estatica, pues al definir un valor especifico para la matriz (en este caso de 5) este al momento de ejecutar no cambia la matriz o la lista que se crea, dejando los valores ingresados, y para finalizar para demostrar que el codigo guardo la informacion ingresada, agregamos al codigo una impresion, que este arroja las calificaciones ingresadas.
