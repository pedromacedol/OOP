# Programação Orientada a Objetos

Paradigma de programação que organiza os dados(objetos) utilizando atributos(características) e métodos(ações) de um objeto.

- OBJETO ⇒ Um objeto é único
    - Atributos/Propriedades⇒ Descreve o objeto
    - Nouns
        
        → Coisas
        
        → Lugares
        
        → Ideais
        
        → Conceitos
    
___
### ➡️ **Classes**

<div align="center">
    <img src="https://user-images.githubusercontent.com/36522521/215089889-4a374613-f170-4122-8023-2755fbe5a1b0.png" />

</div>

#### **A classe é um molde utilizado para criar objetos ou métodos, os quais tem características e ações similares.**

- Type (**Nome) →** Qual a função dela?
- Properties, data (**Atributos)** → O que descreve?
- Operations (**Comportamento)** → O que faz?
- **Método** →Representa as ações de uma classe ou objeto.

<div align="left">

```cpp
    class Carro{
        private:
            string modelo;
            int ano_fabricacao;
            float valor, quilometragem;
        public:
            // Utilizamos set para definir o valor do atributo
            void setAnoFabricacao(int ano) {
                ano_fabricacao = ano; 
            }
            void setValor(float valor}
                this -> valor = valor;
            }
            void setQuilometragem(float km){
                quilometragem = km;
            }
            void setModelo(string modelo){
                this -> modelo = modelo;
            }
    
            // Utilizamos get para obter o valor do atributo
            int getAnoFabricacao(){
                return ano_fabricacao;
            }
            float getValor(){
                return this->valor;
            }
            float getQuilometragem(){
                return quilometragem;
            }
            string getModelo(){
                return this->modelo;
            }
    };
```

</div> 

___
### ➡️ **Pilares da POO**

- **Abstração**

    A abstração é utilizada para estabelecer os atributos e métodos essências para criação do objeto determinado. Portanto, existe uma dependência do objeto em relação aos atributos estabelecidos. 
    
    No exemplo abaixo é demonstrado que para existir uma pessoa é necessário ter um nome, altura e peso, enquanto nas classes "Pessoa 1" e "Pessoa 2" existem outros atributos que não estão presentes em ambos, desse modo não são essenciais.
    
     ![Classe abstrata](https://user-images.githubusercontent.com/36522521/215302022-78e00048-2543-4cb4-91ae-9fd2a5bfa3c6.png)
  
- **Encapsulamento** 
    
    No encapsulamento ocorre a proteção dos dados, visto que os atributos serão privados. Portanto, devemos utilizar para "esconder" informações do usuário, seja devido a informações sigilisas como fórmulas ou até mesmo processos realizadas pelo software.


- **Herança** 

    A Herança é essêncial para utilizarmos sub-classes, ou seja, quando temos um classe geral e desejamos criar um especificação dentro do nicho/área da classe principal. 
    
    Um exemplo é quando temos a classe "Loja" com os atributos nome, cnpj e endereço, portanto podemos criar uma sub-classe para definir a categoria da loja, "Supermercado" por exemplo. Então, iremos herdar os atributos de "Loja" utilizando herança(:) e adicionar os novos atributos relacionados a classe "Supermercado".

    
    
- **Polimorfismo** 

    No Polimorfismo utilizamos um conceito parecido com herança, porém ao invés de invocar os atributos, a classe derivada invoca o método da principal. Porém o comportamento das duas classes é diferente.

    - **Dinâmico:**
            O dinâmico mantém os métodos da classe principal, porém sobrescreve eles. Por exemplo, a classe principal tem um formula de área padrão em um dos métodos e desejo calcular outro tipo de área na classe dependente. Então, devo "repetir" o método da primeira classe e atribuir novos valores.

    - **Estático:**
            O estático ocorre quando a mesma operação é atribuida diversas vezes na mesma classe.

___
### ➡️ 3 Etapas do Software

Para elaboração de qualquer software, deve ser utilizado os três conceitos abaixo. Buscando solucionar as questões levantadas.

- **Análise**
    
    No processo de análise devemos investigar e entender os pontos que devem ser solucionados. Levantando a seguinte pergunta: 
    
    **Qual dor ou problema é preciso resolver?**

- **Designer**
    
    Após realizar o levantamento dos problemas a serem solucionados, devemos cirar um  planejamento para solucionar os problemas enfrentados. Portanto iniciando o designer, ou seja, o planejamento das soluções. Logo, utilizando a seguinte pergunta:
        
    **Como solucionar os problemas?**
    
- **Programação**

    Finalmente devemos iniciar a codar o nosso projeto, tendo um caminho a seguir para solucionar os problemas. Porém, devemos nos perguntar:
    
    **Como executar a solução?** 


### ➡️ Etapas para desevolvimento:

    1 Levantar os requisitos da aplicação

    2 Descrever a aplicação

    3 Indetificar os principais objetos 

    4 Descrever as interações 

    5 Criar um diagrama de classe - UML



