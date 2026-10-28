# Evidencias: <Catalina Lombana Osorio>

## 1. Errores de sintaxis corregidos
| #    | Archivo                      | Línea   | Mensaje del compilador                     | Corrección                                                     |
|------|------------------------------|---------|--------------------------------------------|----------------------------------------------------------------|
| 1    | Acompanamiento.java          | 14      | error: ';' expected                        |agregué ';' después de la palabra precio                        |                                                     |
| 2    | Identificable.java           | 4       | error: ';' expected                        |agregué ';' después de los paréntesis de getCodigo()            |                                                   |
| 3    | Ingrediente.java             | 67      | error: unclosed string literal             |cerré comillas                                                  |
| 4    | Tuberculo.java               | 6       | invalid method declaration; return type req| renombré el constructor igual que la clase                     |                                                           |
| 5    | Tuberculo.java               | 22      | error: unclosed character literal          |  cambié las comillas simples por dobles                        |                                                                 |
| 6    | Verdura.java                 | 3       |error: '{' expected public class Verdura extend Ingrediente{  agregué una 's' a la palabra extend            |                                                                |
| 7    | Fonda.java                   |8        |cannot find symbol (class ArrayList)        |Agregué import java.util.ArrayList debajo de package            |                                                   |
| 8    | Costeable.java               | 5       | interface abstract methods cannot have body|quité el cuerpo del método calcularCosto() y lo terminé con ;   |                                                             |                                                                |
| 9    | Acompanamiento.java          | 4       |is not abstract and does not override ab..  |renombré el método calcularPrecio() a calcularCosto(), para implementar la interfaz |                                                                                                                     |
| 10   | Ingrediente.java             | 25      | incompatible types: possible lossy conversion from double to int|Cambié el tipo de retorno de getPrecioKilo() de int a double|                                                                                                              |
| 11   | Ingrediente.java             |  37     |  cannot find symbol (method IllegalArgumentException)|Agregué new antes de IllegalArgumentException         |                                                                                                            |
| 12   | Condimento.java              |  9      |cannot find symbol (variable alFinal)       |Cambié alFinal por seAgregaAlFinal, el nombre real del parámetro del constructor|                                                                                                      |
| 13   | Olla.java                    |64       | cannot find symbol (variable length)       |Cambié ingredientes.length por ingredientes.size(), porque es un ArrayList|                                                                                                           |
| 14   | Pedido.java                  |  33     |cannot find symbol (variable getPrecio)     |Agregué los paréntesis para llamar al método: a.getPrecio()     |                                                                                              |
| 15   | Sancocho.java                |34       | non-static method calcularTiempoCoccion() cannot be referenced from a static context|Cambié Olla.calcularTiempoCoccion() por olla.calcularTiempoCoccion(), llamándolo sobre el objeto|                                                                                

16. Condimento.java | 23 | variable minutos might not have been initialized | Cambié else if (!seAgregaAlFinal) por else, para que minutos siempre reciba un valor |
| 17 | Sancocho.java | 57 | incompatible types: unexpected return value | Cambié el tipo de retorno de servir() de void a boolean |
| 18 | Proteina.java | 8 | constructor Ingrediente cannot be applied to given types | Agregué el parámetro fresco en la llamada a super(...) |
| 19 | Proteina.java | 18 | incompatible types: String cannot be converted to int | Cambié return "60"; por return 60; |
| 20 | Verdura.java | 10 | method does not override or implement a method from a supertype | Renombré minutosDeCoccion() a minutosCoccion() |
| 21 | Olla.java | 38 | missing return statement | Agregué return null; al final de buscarPorCodigo() |
| 22 | Fonda.java | 45 | constructor Pedido cannot be applied to given types | Agregué el argumento cantidad en new Pedido(mesa, sancocho, cantidad) |
| 23 | Fonda.java | 65 | package system does not exist | Cambié system por System (mayúscula) |
| 24 | Main.java | 23 | Ingrediente is abstract; cannot be instantiated | Cambié new Ingrediente por new Tuberculo |
| 25 | Main.java | 108 | incompatible types: Ingrediente cannot be converted to Proteina | Agregué el cast (Proteina) |