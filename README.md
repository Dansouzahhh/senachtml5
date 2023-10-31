# senachtml5

17/10/2023 Este Repositorio faz do Aprendizado no curso de Web Designer do Senac Itapira
# Diario de Borbo
pag:68

26/10/2023
pag:69

links absolutos e relativos 
Elemento: <!-- Elemento<a> -->
O endereço relativo é a informação para a localização da pagina desejada a partir da localização da pagina atual , eles estão na mesma pagina

pag:76 
Criação de um link Externo 
<!-- <a href="https://pt.wikipedia.org/wiki/Lhasa_apso" target="_blank">Tenha mais informações</a> -->
Utilizar links para visitar outro site com uma maior descrição sobre o cachorro referido.

pag:81 
Inserindo link de E-mail 
<!-- <a href="emailto:atendimento@meuamigocaopetshop.com">atendimento@meuamigocaopetshop.com</a>- (0xx) 88888-8888 -->
permite por meio do uso de link o acesso ao progama padrão de correio eletrônico trazendo o campo destinatario preenchido possibilita ao usuário enviar uma mensagem para um E-email apenas clicando em um link na página 

pag:85
Criando um Formulario Básico 
<!-- <form>

<p><label for="Nome:">Nome</label> <input type="text" name="nome"></p>

</form> -->

type Esse atributo Especifica o tipo de elemento

,label, é um elemento de entrada que define um rótulo para um elemento que será digitado.

A tag ,input, é um elemento de entrada onde o usuário pode inserir dados. deve ser utilizado junto a uma tag ,label

id:Serve para indentificar o elemento e possibilitar o uso da tag ,Label,;

PlaceHolder: Especifica uma dica que descreve o valor esperado de um campo de entrada, uma orientação do que deve ser digitado;

id="nome" placeholder="Digite seu Nome"

pag:86
<!-- <input type="submit" value="Enviar"> -->

o atributo type com o valor descrito com o valor descrito como submit Criara um botão
                                                 
                                                ///CaP:03///
pag:121 

 Antes do Elemento <!-- </head> -->
Digite ^link "href=Estilos/principail.css"  Rel="stylesheet" type="Text/css"^

Esse procedimento cria um vínculo entre o arquivo contendo o estilo e a página na qual Está o conteúdo.

pag:122 
Font size: 1.75em / 28/16=1.75 /

font size Modifica o tamanho da fonte Dentro de Um H.1 ou 2 muda Apenas o local Desejado 

Distância entre linhas e alinhamento: Para Controla o comportamento dessas linhas deve utilizar Duas propriedades de estilo: line-Height (altura da linha) e Align (Alinhamento).

p' 
 font-size: 1.1em;
 line-height: 1.3;
 text-align: justify;
 '

 pag:123

há uma serie de possibilidades para se manipular os textos dentro de uma página.
Variação, peso e estilo são as mais comuns.

 Variação, peso e estilo: 
 p::first-line {
    font-size: 1.17em;
    font-variant: small-caps;
    font-weight: bolder;
    font-style: italic;
}

O Seletor Utilizado é chamado pseudoelemento first-line. Ele seleciona a primeira linha do elemento indicado que nesse caso é o parágrafo Existem Vários tipos de seletores diferentes.

Cor da Régua 
hr"
border-color: #c0262c "

Famíia de fontes

body=Font-family : Adiciona Diferentes fontes depende do Computador Vire padrão 
