<h1>Curso Python</h1>

<h3>Comando Python</h3>
<ul>
	<li>python = entra no Python</li>
	<li>exit() = sai do Python</li>
	<li>print("texto a ser impresso")</li>
	<li>alt+p == volta instrução anterior no IDLE</li>
	<li>alt+n == avança instrução que foi executada no IDLE</li>
	<li>ctrl+f6 = reinicia o IDLE</li>
</ul>
<h4>Comentários</h4>
<p>Para comentar uma linha utilizamos o caracter #(sustenido)</p>
<p>Para comnetar várias linhas usamos 3 vezes o aspa dupla para abrir o comentário e repetimos para fechar o bloco de comentário</p>
<h3>Link para baixar os pacotes do Python</h3>
<a href='https://www.lfd.uci.edu/~gohlke/pythonlibs'>bibliotecas do Python</a>
<h2>Ambientes Virtuais</h2>
<h3>Anaconda</h3>
<p>Anaconda é uma ferramenta computacional gratuita que permite gerir distribuições Python.</p>
<hr>

Para verificar as variáveis de ambiente no console digitar:

echo %PATH%

comando vai listar tudo oque está na varável de ambiente path.

<h3>Criando Ambiente Virtual</h3>

<h4>Comandos Anaconda </h4>
<ul>
	<li>conda create --name k27 python=2.7(k27 é o nome do ambiente e python=2.7 versao do python)</li>
	<li>conda env list == lista os ambientes virtuais instalados</li>
	<li>activate k27(ativamos o ambiente virtual k27)</li>
	<li>deactivate(sai do ambiente virtual)</li>
</ul>

<h2>Biblioteca Kivy</h2>
<p>A biblioteca Kivy é um framework para desenvolvimento multiplataforma escrito em sua maioria em Python.</p>
<p>Qualquer aplicação desenvolvida com a biblioteca Kivy será executada em cima da biblioteca gráfica OpenGL.</p>
<h5>OpenGL</h5>
<p>É uma API de desenvolvimento de aplicações gráficas.</p>

<h2>PIP</h2>
<p>pip é um sistema de gerenciamento de pacotes usado para instalar e gerenciar pacotes de software np Python.</p>
<p><strong>Exemplo: pip install algum-nome-de-pacote</strong></p>
<h2>IDE PYCHARM</h2>
<p> </p>
<h3>IDLE</h3>
<p>Proporcionar uma maneira rápida e fácil aprender e utlizar o Python</p>

<h5>Variáveis Python</h5>
<ul>
	<li>Toda varável tem um NOME</li>
	<li>UM TIPO</li>
	<li>UM TAMANHO</li>
	<li>UM VALOR</li>
</ul>
<p> type( nomeDaVariavel) == retorna o tipo da varável</p>
<p>Python é uma linguagem de tipagem dinâmica</p>
<h6>Para concatenar nós usamos o caracter</h6>
<p>Alguns exemplos:<br></p>
print("O valor é: ", num_int)
print("O valor é: %i" %num_int)
print("O valor é: " + str(num_int))


