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
    
#### **A classe é um molde utilizado para criar objetos ou métodos, os quais tem características e ações similares.**

</div>


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
    
    No exemplo abaixo é demonstrado que para existir uma pessoa é necessário ter um nome, altura e peso, enquanto nas classes "Pessoa 1" e "Pessoa 2" existem outros atributos que não estão presentes em ambos, desse modo não sendo essenciais.
    
     ![Classe abstrata](https://user-images.githubusercontent.com/36522521/215302022-78e00048-2543-4cb4-91ae-9fd2a5bfa3c6.png)
  

Encapsulamento -> Proteger os dados e torna privados

Herança ->

Polimorfismo -> 
Dinamico: 
Estático





