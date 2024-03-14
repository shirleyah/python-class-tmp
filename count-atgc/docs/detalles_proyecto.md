# [Nombre del proyecto]

Fecha: dd/mm/202X  

**Participantes**:

- [Nombre] <email:username@ccg/lcg.unam.mx>  

## descripci??n del roblema


[Especificar la problem??tica que se presenta y la solluci??n que se espera obtener.]  


## Especificaci??n de Requisitos

Requisitos funcionales

- Requisito 1: [descripci??n]  
- Requisito 2: [descripci??n]  
- Requisito 3: [descripci??n]  
- Requisito 4: [descripci??n]  
- Requisito 5: [descripci??n]  

Requisitos no funcionales

- Requisito no funcional 1: [descripci??n]  
- Requisito no funcional 2: [descripci??n]  
- Requisito no funcional 3: [descripci??n]  



## An??lisis y Dise??o

[Especificar c??mo se llegar?? a la soluci??n del problema. Se pueden incluir diagramas de casos de uso, pseudoc??digos, y cualquien otro gr??fico que describa la soluci??n. Si se reciben datos de entrada se debe especificar el formato en el que se requieren , el tipo de archivo esperado, formato de resultados  ]  


```
Funci??n principal (Suma_Numero):
    Intentar:
        datos_archivo = Obtener_Datos_Archivo(ruta_archivo)
        numeros = Validar_Datos(datos_archivo)
        resultado = Calcular_Suma(numeros)
        Imprimir_Resultado(numeros, resultado)
    Atrapar cualquier excepci??n como error:
        Imprimir el error

Funci??n Obtener_Datos_Archivo(ruta_archivo):
    Si la ruta del archivo no existe:
        Levantar un error de "archivo no encontrado"
    Leer y retornar las l??neas del archivo

Funci??n Validar_Datos(data):
    Intentar:
        Convertir todos los datos a formato flotante y retornar como una lista
    Atrapar ValorError:
        Levanta un error de "??Introducir solamente n??meros de base 10!"

Funci??n Calcular_Suma(numeros):
    Retornar la suma de los n??meros

Funci??n Imprimir_Resultado(numeros, resultado):
    Imprimir los n??meros y su suma total en el formato especificado
```



#### Caso de uso: [Nombre del caso de uso]

```
         +---------------+
         |   [Actor]     |
         +-------+-------+
                 |
                 | 
                 v
         +-------+-------+
         |    [Caso      |
         |     de        |
         |     uso       |
         |   (actor)]    |
         +---------------+
```

- **Actor**: [Nombre del actor]
- **Descripci??n**: [Descripci??n del caso de uso]
- **Flujo principal**:

	1. [Paso 1]  
	2. [Paso 2]  
	3. [Paso 3]  
	4. [Paso X]  
	
- **Flujos alternativos**:
	- [Condicional 1]
	1. [Paso 1]  
	- [Condicional X]
	1. [Paso 1]  
                

