<h1 align="center"> 💻Efficiency_X </h1>

![image](https://user-images.githubusercontent.com/55964635/172654704-462d38c9-37f4-4b7f-9729-803ec1324e72.png)



<div align="center">
<img src="Img/2.png"/>
 </div>

<h1 align="center"> Diagrama </h1>

<div align="center">
<img src="Img/1.png"/>
 </div>


## Pruebas.
```Pascal
var
	caracter:char;
	numero: integer;
	numero : INTEGER;
	r:real;
	bool:boolean;
	puntero: ^integer;
	puntero2:^char;
	puntero:^real;
	puntero:^boolean;
begin
end.
```
![image](https://user-images.githubusercontent.com/55964635/129513229-2f79a29e-efc9-4172-9af1-8f1ca8f145e8.png)

## Codigo de prueba.

```Pas
program Problema;
type
  cadena35 = string[35];
  empleado = record
    dirCorreo: cadena35;
    edad: integer;
    sueldo:real;
  end:
  
  punt = empleado^;
  vector = array [1..500] of punt;
  
  lista = ^nodo;
  nodo = record
    dato: empleado;
    sig: lista;
  end;
  
var
	caracter:char;
	numero: integer;
	numero : INTEGER;
	r:real;
	bool:boolean;
	puntero: ^integer;
	puntero2:^char;
	puntero:^real;
	puntero:^boolean;
begin

  l:=nil;
  for i:=1 to 10 to 
  begin
    read(emp.dirCorreo, emp.edad, emp.sueldo);
    if (emp.edad < 40) and (emp.sueldo < 40000) then
      exp.sueldo:= exp.sueldo + 7000;
    new(aux); 
    aux^.dato := emp;
    aux^.sig: := l;
    l := aux;    
  end;
end.

```

![image](https://user-images.githubusercontent.com/55964635/129676115-ea422097-595c-4da9-82bf-172e33360657.png)

## Agregando strings.

```Pascal
program Problema;
type
  cadena35 = string[35];
  empleado = record
    dirCorreo: cadena35;
    edad: integer;
    sueldo:real;
  end:
  
  punt = empleado^;
  vector = array [1..500] of punt;
  
  lista = ^nodo;
  nodo = record
    dato: empleado;
    sig: lista;
  end;
  
var
	caracter:char;
	numero: integer;
	numero : INTEGER;
	r:real;
	bool:boolean;
	puntero: ^integer;
	puntero2:^char;
	puntero:^real;
	puntero:^boolean;
        nombre:cadena35;
begin

 
end.
  
```



![image](https://user-images.githubusercontent.com/55964635/130160452-cdcb94b5-15f2-4e5f-a1cf-7ad2d31a9757.png)

## Type terminado.

```Pas
program Problema;
type
  cadena35 = string[35];
  empleado = record
    dirCorreo: cadena35;
    edad: integer;
    sueldo:real;
  end;
  
  punt = ^empleado;
  vector = array [1..500] of punt;
  
  lista = ^nodo;
  nodo = record
    dato: empleado;
    sig: lista;
  end;
  
var
  v:vector;
  aux:lista;
  emp:empleado;
  i:integer;
begin
  l:=nil;
  for i:=1 to 10 to 
  begin
    read(emp.dirCorreo, emp.edad, emp.sueldo);
    if (emp.edad < 40) and (emp.sueldo < 40000) then
      exp.sueldo:= exp.sueldo + 7000;
    new(aux); 
    aux^.dato := emp;
    aux^.sig: := l;
    l := aux;    
  end;
end.
  

```

![image](https://user-images.githubusercontent.com/55964635/130385848-30fa0f2a-5882-4fc2-952c-7a2e68cdfb2c.png)

![image](https://user-images.githubusercontent.com/55964635/130385863-a6361ab6-02de-44b8-9eae-4c57c9b6652d.png)


## Empezamos memoria dinamica

```Pas
program Problema;
type
  cadena35 = string[35];
  empleado = record
    dirCorreo: cadena35;
    edad: integer;
    sueldo:real;
  end;
  
  punt = ^empleado;
  vector = array [1..500] of punt;
  
  lista = ^nodo;
  nodo = record
    dato: empleado;
    sig: lista;
  end;
  
var
  v:vector;
  aux:lista;
  emp:empleado;
  i:integer;
begin
   new(aux); 
end.
  
```


### Eliminamos todos los espacios para trabajar de forma mas facil

[Website](https://fabian-martinez1.github.io/Efficiency_X/)

### Fuentes.
[Eliminar saltos de linea](https://www.it-swarm-es.com/es/javascript/como-eliminar-todos-los-saltos-de-linea-de-una-cadena/1066967721/).

[Expresiones regulares basicas](https://www.youtube.com/watch?v=KELZuuVPPT4).

[Operaciones con expresiones regulares](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Regular_Expressions).

[Pasar un array a string](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/toString).

[Web de pruebas](https://regexr.com/).
