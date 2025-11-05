Programa Funcional en Haskell

Demostración de Funciones como Parámetros

Autora: Cynthia Isauro Trinidad Cynthia

Repositorio: https://github.com/tuusuario/programa-haskell-funcional

Probar codigo en: https://www.jdoodle.com/execute-haskell-online

¿Por qué solo funciona bien en Haskell?


En haskel funciona porque: 

Las funciones son valores normales, puedes pasar funcines como paramétros y tiene verificación de tipo automática.

En otros lenguajes es mas dificl ya que:
java necesita crear interfaces complicadas,  
python no verifica los tipos de las funciones 
c++ la sintaxis es compleja


Lenguaje Funcional:

Las funciones son ciudadanos de primera clase, se evitan los efectos secundarios y datos mutables
El código se escribe como composición de funciones y se usa evaluación de expresiones en lugar de ejecución de comandos


Ejemplo en codigo: 

"aplicarFuncion duplicar [1,2,3]"
Función como parámetro ↑
Resultado: [2,4,6]


Resultado esperado:

=== RESULTADOS ===
Números: [1,2,3,4,5,6,7,8,9,10]
Duplicados: [2,4,6,8,10,12,14,16,18,20]
Pares: [2,4,6,8,10]
