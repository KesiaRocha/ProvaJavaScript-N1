# JavaScript



# EXEMPLO DE ARRAY STRING (com push/pop & shift/unshift)
let nomes = ["José","Maria","João"]

nomes.push("Bea")

console.log(nomes[nomes.length-1])



let nomes = ["José","Maria","João"]

console.log("====ADICIONA NOVO ELEMENTO NO FIM=====")

nomes.push("Bea")

console.log(nomes[nomes.length-1])


console.log("\n====RETIRA ÚLTIMO ELEMENTO=====")

nomes.pop()

console.log(nomes)


console.log("\n====ORDEM QUASE ALFABÉTICA=====")

nomes.sort()

console.log(nomes)



console.log("====\nAPAGA ELEMENTO=====")

delete nomes[1]

console.log(nomes)


console.log("====\nREMOVE 1º ELEMENTO=====")


nomes.shift()


console.log(nomes)



console.log("====\nADICIONA 1º ELEMENTO=====")

nomes.unshift()

console.log(nomes)


# REMOÇÃO NA ARRAY

let nome = ["José","Maria","João", "Bia"]

let removidos=nome.splice(2,1,"Teo")

console.log(nome)


# ==============================================
#       	-> EXEMPLOS USANDO SPLICE
# ==============================================

let nomes = ["josé","João","Maria","Bia"]


nomes.splice(1,1,"Teo")


console.log(nomes)


nomes.splice(4,0,"Ana")


console.log(nomes)


nomes.push("Ana2") 


console.log(nomes)


nomes.sort()


console.log(nomes)

