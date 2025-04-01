a)nome, espécie e idade
b)usa a estrutura extends para herdar a classe animal e adiciona o atributo habitat e o método exibirHabitat
c)significa que a classe animalSelvagem herda a classe animal
d)o comando super importa a inicialização dos atributos da classe mãe, o que diminui a quantidade de atributos a serem declarados na classe filha
e)Cria um objeto da classe animal selvagem e passa os parâmetros para os atributos da classe.
f)Eles são de classes diferentes.
g)Porque é um método da classe mãe e pode ser usado por ambas, já que animalselvagem herda os métodos de animal
h)Não, pois esse é um método exclusivo da classe filha e não pode ser chamada pela classe mãe, apenas por animalselvagem e classes que a herdem.
i)Com a herança, um código que seria escrito várias vezes pode ser reciclado e usado em diferentes situações, como por exemplo a inicialização dos atributos das classes animal e animalselvagem. Ao invés de declarar tudo de novo, ele usa o que já foi feito na classe mãe(Código modular)
j)Como o método seria adicionado a todos os animais, ele deveria ser adcionado na classe animal e a classe animalselvagem e outras herdaria esse método.
k)Nome: Tico, Especie: Macaco, Idade: 4
Nome: Nala, Especie: Leoa, Idade: 5
Habitat natural: Savana Africana
L)Ele não receberia os valores de nome, espécie e idade, só seria passado o habitat, gerando um erro.
m)
class AnimalDomestico extends Animal{
constructor(nome, espécie, idade, nomeDono){
super(nome, espécie, idade);
this.nomeDono=nomeDono;
}
exibirDono(){
return `Nome do dono:${this.nomeDono}`;
}
}
