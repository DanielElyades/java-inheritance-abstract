# java-inheritance-abstract

São classes que não podem ser instânciadas.
É uma forma de garantir herança total: somente subclasses não abstratas podem ser instânciadas, mas nunca a superclasse abstrata.

Se a classe Account não pode ser instânciada, por que simplesmente não criar somente as classes SavingsAccount e BusinessAccount?
Por reuso e polimorfismo. A superclasse genérica nos permite tratar de forma fácil e uniforme todos os tipos de conta, inclusive com polimorfismo se for o caso. Por exemplo, você pode colocar todos tpos de contas em uma mesma coleção.

Suponha que você queira:
Toralizar o saldo de todas as contas.
Depositar 10.00 em todas as contas.
