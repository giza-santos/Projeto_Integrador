class ageendamento{
- ID:int
- nome:string
- email:string
- telefone:int
- data:string
- hora:strings
+ editar(data string, hora string):void
+ cancelar():bool
+ reagendar(data string, hora string):bool
+confirmar():bool
+ notificar():bool
+listarAgendamentos():string
+criarAgendamento(nome string, email string, telefone int, data string, 
hora 
string):int
+buscarAgendamento(ID int):string
+removerAgendamento(ID int):bool
+atualizarAgendamento(ID int, data string, hora string):bool
+filtrarAgendamentos(data string):string

}