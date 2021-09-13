
var nome = "Richard", data = "17/09/2021", dataAtual = "13/09/2021"
var idade = 18
const participante = ['Cleber','Jose','Aline','Vagner','Alex','Eliane']
var quantidade = 6
console.log("")
console.log("Cadastro de Evento")
console.log("Data Atual : "+dataAtual)
console.log("")
console.log("A data do Evento é : "+ data)
if (data == dataAtual) {
console.log("Não é possivel realizar o cadastro") 
console.log("Consulte a data do envento e tente novamente !!")
}else{
    console.log("Cadastro em Andamento !")
}
console.log("Nome do Participante: "+nome+", e sua idade é: "+idade+" anos")
if (idade >= 18) {
    console.log("Idade permitida") 
    console.log("Cadastro em Andamento !")   
}else{
    console.log("Menor de 18 anos, cadastro não permitido !")
}
console.log("")
console.log("Lista de Participantes:")
console.log(" " +participante)
console.log("Quantidade de participantes "+ quantidade)
console.log("")
if (quantidade >100) {
    console.log("Cadastro não realizado")
    console.log("Quantidade execedeu o limite de 100 Pessoas")
}else{
    console.log("Cadastro em Concluido")

}



