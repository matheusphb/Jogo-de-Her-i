// Definindo a classe Heroi
class Heroi {
  // Construtor para inicializar as propriedades do herói
  constructor(nome, idade, tipo) {
    this.nome = nome;
    this.idade = idade;
    this.tipo = tipo;
  }

  // Método atacar que exibe a mensagem de ataque conforme o tipo
  atacar() {
    let ataque = '';

    // Verificando o tipo de herói e definindo a mensagem de ataque
    if (this.tipo === 'mago') {
      ataque = 'magia';
    } else if (this.tipo === 'guerreiro') {
      ataque = 'espada';
    } else if (this.tipo === 'monge') {
      ataque = 'artes marciais';
    } else if (this.tipo === 'ninja') {
      ataque = 'shuriken';
    }

    // Exibe a mensagem final
    console.log(`o ${this.tipo} atacou usando ${ataque}`);
  }
}

// Criação de objetos Heroi e chamadas ao método atacar
const heroi1 = new Heroi('Gandalf', 100, 'mago');
heroi1.atacar(); // Exibe: o mago atacou usando magia

const heroi2 = new Heroi('Arthur', 30, 'guerreiro');
heroi2.atacar(); // Exibe: o guerreiro atacou usando espada

const heroi3 = new Heroi('Lian', 25, 'monge');
heroi3.atacar(); // Exibe: o monge atacou usando artes marciais

const heroi4 = new Heroi('Ryu', 20, 'ninja');
heroi4.atacar(); // Exibe: o ninja atacou usando shuriken
