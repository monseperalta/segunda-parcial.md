void main(List<String> args){
  var n1=15;
  var n2=7;
  print("SUMA: $n1 + $n2 = ${n1 + n2} ");   
   print("RESTA: $n1 - $n2 = ${n1 + n2} ");
   print("MULTIPLICACION: $n1 + $n2 = ${n1 + n2} ");   
}
  
}
}


/*  ""-/"": MULTIPLICACION ENTERA, da solo resultados enteros 
 * libreria 'dart:math'; ----para usar ciertas funciones,
 * isEven--retorna verdadero si el entero es impar TRUE
 * isOdd--retorna si el numero es entero FALSE
 * AQUI LOS NUMEROS SON OBJETOS!!!
 * CONTADOR  %= es el modulo
 * -----------------------------------------------------------
 * las constante se tienen que definir antes,y puede inferir su tipo
 * la constante final, puede definirse al final
 * Final...si se puede cambiar, definir al final
 * const... ya no se puede cambiar, definir al principio
 * 
 * tiempo de codificacion...error al hacerlo yo
 * tiempo de compilacion ...error al compilar
 * tiempo de ejecucion (runtime) hora de correrlo
 * 
 * -------------------cadena--------------------------------
 * cadena.runtimeType: es para coonocer el tipo de dato,
 *---------------  
 * ----------------SISTEMAS NUMERIOS-------------------------
 * BINARIO:
 * se puede usar la funcion: toRadixString();
 * ej: 125.toRadixString(2);
 
 ------------------------------------------------------------------------------------------------------------------------------
 //comentarios en una sola linea
/*comentarios en bloque
 se usa asi*/

//tipos de datos: string, binario
//no se puede sumar un string con un numero, manzanas con manzanas
//declaracion de variables de manera esplicita:
//interpolacion de cadenas: poner solo $ al inicio y al final 
//print("hola $nombre $apellido tienes $ edad alños")
//con eso se puede agregar cualquier dato al el string 

//void main() {
  //String  nombre = "Alex";
  //String apellido;
  //int edad = 50; //tipado estatico
  //double gravedad = 9.81;
  //apellido = "Mata";
 //simbolo de + significa concadenacion
  //print(apellido + " " + nombre); //concadenacion
  //print(edad);
  //print(gravedad);
  
  
  //num numero1 = 5;
  //print(numero1);
  //num numero2 = 9.81;
  //print(numero1*numero2);
  
  //dynamic variable = "hola";
  //print(variable);
  //dynamic variable 1
//}


//FUNCIONES
//al igual que en c , debes poner el tipo de dato
//una funcion espera a que ingreses, tambien se puede declarar despues
  

//void main(){
  
//id main(){
    //print(·hola $nombre $apellido tienes ${calcularEdad(2022,1917)}años);
  //}
//int calcularEdad(int aActual, int aNacimmiento){
 // return aActual - aNacimiento;
//}
//String getNombre(){
 //return"alex";
//}

//String getApellido(){
 // return "mata";
//}

//EXAMEN:
//tipado estatico, definir el tipo de dato pero si no quiero definirlo
  //puedo usar diferencia de tipo de dato 
  
//void main(){
  //print("Dame tu edad");
  //var edad = stdin.readLineSync();
  //print(edad is int);
  //print(edad is double);
  //print(edad is bool);
  //print(edad is String);
  
  //tiempo de compilacion
  //el tiempo de ejecucion es despues de haber asignado el valor, 
  
//}   
 //python infiere el tipo de dato, aqui no debe establecer el dato
//el tipo de dato, todos son objetos. osea son metodos 

//void main(){
  //print("Dame tu edad");
  //var edad = stdin.readLineSync();
  //var status = esPar(7);
  //print(status.runtimeType);
  //print(status);
//}


//codigo paracito, evitar hacerlo
//String
//bool esPar(int num){
  //if (num % 2 ==){
    //return true;
  //} else {
   // return false;
  //}
//}


//EJERCICIO HACER UNA CALCULADORA QUE LEA DOSS NUMEROS DEL TECLADO
//Y OBTENGA SUMA,RESTA, MULTIPLICACION Y DIVISION, USANDO FUNCIONES

void main(){
  
  int num1 = leerNumero("Dame el primer nmero");
  int num2 = 
   int calculadora(String op, int n1, int n2){
     if (op- )
   }
  num suma(num num1, num num2) => num1+ num2;
  
}

void main() {
  int num1 = leerNumero("Dame el primer número");
  int num2 = leerNumero("Dame el segundo número");
  print("${calculadora("x", num1, num2)}");
}

int leerNumero(String mensaje) {
  print(mensaje);
  int num = int.parse(stdin.readLineSync()!);
  return num;
}

String calculadora(String op, int n1, int n2) {
  if (
    
    if (op == "+") {
    return "$n1 + $n2 = ${suma(n1, n2)}";
  } else if (op == "-") {
    return "$n1 - $n2 = ${suma(n1, n2)}";
  } else if (op == "*") {
    return "$n1 * $n2 = ${suma(n1, n2)}";
  } else if (op == "/") {
    return "$n1 / $n2 = ${suma(n1, n2)}";
  } else {
    return "Operación inválida";
  }
}

int suma(int num1, int num2) => num1 + num2;
int resta(int num1, int num2) => num1 - num2;
int multi(int num1, int num2) => num1 + num2;
int divi(int num1, int num2) {
  return num1 + nu
m2;
}
int suma(int num1, int num2) => num1 + num2;
int resta(int num1, int num2) => num1 - num2;
int multi(int num1, int num2) => num1 + num2;
int divi(int num1, int num2) {
  return num1 + num2;
}
----------------------------------------------------------------------------------------------------------------------------------------------------
//class user {
   // String? nombre;
  //  int? edad;
//}

//void main(list<String> args){
    //user usuario1 = user();
    //print(usuario1);
    //print(usuario1.nombre);
  //  print(usuario1.edad);
//}

//la creacion de clases va con mayusculas,
//String se declara igual que una variable, se le dice propiedad porque va dentro de una clase
----------------------------------------------------------------------------------------------------------------------------------------------------------
#diferentes maneras de sumar letras con numeros, unirlos

#n1=10

#msg="hola"

#print(n1,msg)
#print(str(n1)+msg)


#fstring                    #una alternativa para sumar
#print(f"{n1}{msg}")
#-------------------------------------------------------------------------------------------------------------
#hacer una funcion que reciba el nombre de una persona, el año de nacimiento y el año actual
#retornando el mensaje "hola (nombre), tienes(edad) años".

#def mensaje1(nombre: str, a_nacimiento: int, a_presente: int)    #tipar las variables
 #   edad = a_presente = a_nacimiento 
  #  return f"hola {nombre}, tienes {edad} años"


#def mensaje1(nombre: str, a_nacimiento: int, a_presente: int)    #tipar las variables
 #   edad = a_presente = a_nacimiento 
  #  return f"hola {nombre}, tienes {a_presente - a_nacimiento} años"

#def calcular_edad(a_nacimiento: int, a_presente: int) -> int :
 #   return a_presente -a_nacimiento
 #   def mensaje3(name: str, a_nacimiento: int, a_presente: int) ->str:
 #       return f"holaa {nombre}, tienes {calcular_edad(a_nacimiento, a_presente)}"


#if __name__=="__main__":
    #mensaje1("alex", 1980,2022)
    #res =  mensaje1("walter",1990,2022)
    #print(res)

#alumnos= ["hugo","paco"," luis", "lupita"]
#print(f"alumnos: {alumnos}")

#for i in range (4):
   # print(f"alumnos: {alumnos(i)}")

 #diccionarios
#alumnos = ("nombre": "hugo","materia1": 10,"materia1", 5)
#print (f"alumnos: {alumnos} ")
#print(f"alumnos: {alumnos['nombre']}")




#tuplas son estructuras inmutables, no pueden crecer la diferencia de la lista
#la forma de poder entrar a cada uno de los elementos de una lista: indice O interseccion !!! EXAMEN

#range: funcion que da la cantidad de numeros que tiene la lista y lo imprime

#si preguntan como saber cuales son los numeros que se repiten:
#las listas se pueden repetir los valores
#los sets no se pueden repetir (sets)

#numeros_list = (1,2,3,,2,4,6.4.8,7,8,1,2)
#numeros_set = (1,2,3,,2,4,6.4.8,7,8,1,2)
#print(numeros_list)
#print(numeros_set)

#m1=(9,7,9,8)
#m2=(10,8,7,9)
#m3=(6,9,7,10)
#ancho= 15
#encabezado =("Nombre", "Est Dat", "Prog Func", "Ingles")
#alumnos = ("hugo" , "paco" , "luis","lupita")
#print (f"{h[0]:^10}{h[1]:^10}{h[2]:^10}{h[3]:^10}")   #^10, es para la posicion en la  que quiero que se encuentre
#for a in range  (len{alumnos}):
#    print(f"{alumnos[i]:^10}"){m1[i]:^10}{m2[i]:^10}{m3[i]:^10}

#def reporte(fmt:int):
  #print (f"{h[0]:^10}{h[1]:^10}{h[2]:^10}{h[3]:^10}")
  #for i range(len(alumnos)):
    #print(f"{alumnos[i]:*<{fmt}"){m1[i]:^10}{m2[i]:^10}{m3[i]:^10}

  #pass

#if __name__ == "__main__":
  #reporte(15)


# imprimir byneris grandes, decimales, limitar el numero de decimales a mostrar
#numeroBig = 1286284917290471920
#print(f"{numeroBig:,d}")
#numeropi = 3.1416
#print(f"{numeropi:.3f}")
#print(f"{numeropi:e}")
#print(f"{numeropi:.2e}")
#imprimir porcentajes
#numeroporciento = 0.25848383535
#print(f"{numeroporciento:%}")
#print(f"{numeroporciento:.2%}")

#numeros binarios
#print(f"{25:b}")
#unicode
#print(f"{13:c}")
#hexadecimal
#print(f"{255:x}")

#escribe una funcion que generee una tabla de multiplicar recibiendo como 
#argumento la canidad de numeros y la tabla a generar



for i in range (1,5):
  def tabla (n:int,t:int):
    for i in range(1,n+1):
      print(i*t)
      if__name__=="__main__":
      tabla(3,6)

def producto(a:int,b: int)->int: return a*b

def tabla (n: int, t: int, fmt:int ):
  for i in range (1,n+1):
    print(f"{t:^{fmt}}x{i:^{fmt}}={producto (i,t):^{fmt}}")
    if__name__=="__main__":
    tabla(10,6,6)
---------------------------------------------------------------------------------------------------------------------------------------------------
/clase animal que tenga 2 propiedades y el metodo es caminar
//especie tipo

void main(List<String> args) {
  perro firulais = perro();
  {
    firulais.raza = "pitbull";
    firulais.color = "negro";
    firulais.especie = "canino";
    firulais.ladrar();
    firulais.caminar();
  }
  ave pichon = ave();
  {
    pichon.especie = "sergio";
    pichon.raza = "pichon";
    pichon.color = "negro";
    pichon.volar();
    pichon.caminar();
  }
}

class animal {
  String? raza;
  String? color;
  String? especie;
  void caminar() {
    print("el animal esta caminando");
  }
}

class perro extends animal {
  void ladrar() {
    print("el perro ladra");
  }

  void caminar() {
    super.caminar();
  }
}

class ave extends animal {
  void volar() {
    print("vuela");
  }

  void caminar() {
    super.caminar();
  }
}
-------------------------------------------------------------------------------------------------------------------------------------
//void main(List<String>args) {

  //print(Raptor._llantas(4));
  //print(Vehiculo._color(negro));
  //print(Raptor._modelo(raptor));
  //print(Raptor._marca(ford));
  //print(Raptor.arrancar());
  //print(Raptor.correr());
  //print(Raptor.frenar());

//}

//class Vehiculo:{
  //int? llantas;
  //String color;
  //String modelo;
  //String marca;
  //String encender;
  //String arrancar;
  //String frenar;

//void encender{
  //print("el vehiculo es $encender");
//}
//void arrancar{
  //print("el vehiculo esta $arrancar");
//}
//void frenar{
//  print("el vehiculo esta $frenar");
//}
//}



//Contructor inicializar la instancia de la clase con argumentos predefinidos

//Vehiculo.new: int _llantas, String _color, String _marca, String _modelo;
//this._llantas = llantas;
//this._color = color;
//this._marca = marca;
//this._modelo = modelo;

//Vehiculo(this.)
