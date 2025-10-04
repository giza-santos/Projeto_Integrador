```mermaid
    classDiagram
class Banco{



 - ID:int
 - nome:string
 - endereco:string
 - telefone:int
 - email:string
 + abrirConta(tipo string, saldo float):int
 + fecharConta(ID int):bool
 }
 ```