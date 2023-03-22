## Respostas

1 - A Máquina Virtual Java é uma camada de abstração que executa código Java, ou seja, permite que o código seja executado em qualquer sistema operacional ou alguma outra arquitetura, sem a necessidade de converter o código fonte para um modelo específico. A JVM converte um bytecode em código de máquina.

2 - O JRE e JDK são distribuições do ambiente de execução Java e se diferem pelo fato que, enquanto o JRE é usado para executar aplicações Java, porém não têm incluso ferramentas para desenvolvimento, como compiladores  e depuradores. O JDK já um kit completo, pois possui tudo que o JRE possui, desse modo, possui o JRE incluso e ferramentas adicionais que o JDE já não possue, como compiladores, depuradores e recursos para criações de interface gráfica.


3 - 
public class Hello{
	public static void main(String[] args){
		System.out.println("Terminei a primeira aula com um programa Java!");
	}
}

4 - Não executa apenas com o "java Hello" mas com "java Hello.java" ele ja compila e executa direto.
5 - Compilou com o javac mas não executou porque não existe um método main na classe.
6 -
public class NameTeam{
	public static void main(String[] args){
		System.out.println("André Lucas");
		System.out.println("Karasuno");
	}
}


7 - Na tentativa de compilar o código anterior todo em maísculo a IDE indicou o seguinte erro: NameTeam.java:9: erro: classe, interface, enum ou registro esperado. O código não foi compilado, logo também não foi executado.

8 - Indica que classe do código deve ser indicada no próprio repositório. Dessa forma, o código não localizou a classe que o código fazia referência. Erro: The public type NameTeam must be defined in its own file