# Java

## O que é a sintaxe Java?

*``A sintaxe Java`` refere-se à estrutura e às regras específicas que devem ser seguidas ao escrever programadas na linguagem de programação ``Java``.*

*Ela abrange a forma como as instruções e comandos são organizados, facilitando a compreensão pelo compilador e a execução correta pelo computador. A sintaxe é fundamental para garantir que o código seja preciso, legível e funcional.*

```diff
- Ao programar em Java, é necessário conhecer e aplicar corretamente as conveções e estruturas da sintaxe,
- que incluem a definição de variáveis, declaração de métodos, criação de classes e outros elementos essenciais
- para a construção de programas eficientes e sem erros.``*
```

*Em resumo, a sintaxe Java é gramática que orienta a escrita de código nesta linguagem, assegurando a coerência e a compreensibilidade do software desenvolvido.*

<br>

## Objeto em Java

*As entidades em ``Java`` encapsulam tanto estados quanto comportamentos. Por exemplo, consideremos um carro que tem estados como modelo, cor e proprietário, e comportamentos como acelerar, frear e virar. Cada entidade é uma instância de uma classe.*

<br>

## Classe em Java

*Uma classe em ``Java`` serve como um modelo, padrão ou esboço para uma entidade. Ela especifica os estados e comportamentos que uma instância da entidade pode ter. Por exemplo, a classe ``Car`` pode definir os estados modelo, cor e proprietário, e os comportamentos acelerar, frear e virar.*

<br>

## Operações em Java

*Operações, ou métodos em ``Java``, descrevem as lógicas, manipulam dados e realizam ações específicas. Cada método define um comportamento da entidade. Por exemplo, podemos ter um método ``ligar()`` na classe ``Car`` para representar a ação de ligar o carro.*

<br>

## Atributos de Instância em Java

*``Cada instância de uma entidade possui um conjunto único de atributos de instância.`` Esses atributos representam o estado da entidade e são fundamentais para suas características. Por exemplo, a instância de um carro pode ter atributos como modelo, cor e proprietário, os quais contribuem para o seu estado geral.*

<br>

## Programa Java simples: Olá, Java!

*Aqui está um programa ``Java`` simples:*
```Java
class Main {
   public static void main(String[] args) {
       System.out.println("Olá, mundo!");
   }
}
```
**_NOTE:_** Este programa imprime uma string "Olá, mundo!" no console. Recomendo instalar o JDK e o Intelliji IDEA e tentar escrever o código que você vê acima. Ou, na primeira tentativa, encontre um IDE online para fazer o mesmo.

#### Saída:
![image](https://github.com/Yuri-Silva2/Estudos/assets/128656475/4e937d8c-17d0-4f69-a709-e8bf44a646a5)

<br>

## Princípios fundamentais da sintaxe Java
**Ao desenvolver em Java, é crucial seguir algumas regras essenciais de sintaxe, tais como:**

> - O nome do arquivo deve coincidir exatamente com o nome da classe.
> - Geralmente, cada classe é armazenada em um arquivo individual com a extensão ``.java``. Esses arquivos de classe são comumente organizados em pastas conhecidas como pacotes.
> - ``Java`` faz distinção entre maiúsculas e minúsculas; portanto, ``"String" não é o mesmo que "string"``.
> - A execução de um programa ``Java`` sempre inicia no método principal: ``public static void main(String[] args)``. Este método é obrigatório em qualquer programa ``Java``.
> - Um método, que pode ser um procedimento ou uma função, é uma sequência de comandos que define o comportamento de um objeto.
> - A ordem dos métodos no arquivo do programa é irrelevante.
> - A primeira letra do nome de uma classe deve ser maiúscula. Se a classe tiver várias palavras, a primeira letra de cada palavra deve ser maiúscula ``("MyFirstJavaClass")``.
> - Os nomes de todos os métodos na sintaxe Java começam com uma letra minúsucla, com letras subsequentes em maiúscula ao usar várias palavras ``("public void myFirstMethodName()")``.
> - Os arquivos são salvos com o nome da classe e a extensão ``.java ("MyFirstJavaClass.java")``.
> - Em ``Java``, blocos de código são denotados por delimitadores ``"{...}"``, representando áreas distintas de código.
> - Cada instrução de código deve ser finalizada com um ponto e vírgula.




