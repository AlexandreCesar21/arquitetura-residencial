# arquitetura-residencial


#Estrutura HTML

Explicação
• <!DOCTYPE html>: Declara o documento como HTML5.
• <html lang="en">: Define o idioma como inglês, útil para motores de busca e leitores de tela.
• <head>: Contém metadados como charset (codificação de caracteres), viewport (responsividade) e o título da página, além de um link para o arquivo CSS externo (style.css).

#Cabeçalho da Página

Explicação
• <header>: Seção principal do cabeçalho da página.
• <div class="titulo">: Bloco que contém o título principal e o subtítulo da página.
• <h1> e <h4>: Usados para exibir o título principal ("Tradição em projetos de arquitetura") e o subtítulo.

#Estilo CSS do Cabeçalho

Explicação
• background-color: Define um fundo escuro para o cabeçalho.
• display: flex e align-items / justify-content: Usados para centralizar o texto verticalmente e alinhá-lo à esquerda.



#Seção de Informações (#colunas)

Explicação
• <div id="colunas">: Contém três blocos com informações principais sobre o portfólio da empresa.
• .informacao: Cada bloco contém um número (<h2>) e uma descrição (<p>).

#Estilo CSS da Seção de Informações

Explicação
• display: grid e grid-auto-flow: column: Organiza os blocos em colunas.
• font-size e margin-top: Define o tamanho do texto e espaçamento superior.


#Seção de Depoimento (#teste)

Explicação
• <div id="teste">: Contém dois blocos, um para o depoimento (.container .depoimento) e outro para a imagem (.container-img).
• <h1> e <p>: Apresentam o título e a descrição do depoimento, com informações sobre a experiência da empresa.


#Estilo CSS da Seção de Depoimento

• display: grid e grid-auto-flow: column: Distribui o depoimento e a imagem em colunas.
• position: relative em .container e .container-img: Posiciona o texto e a imagem.



#Rodapé com Formulário

Explicação
• <footer>: Define o rodapé com um formulário para que os visitantes entrem em contato.
• <form>: Envia os dados inseridos para uma API externa usando o método POST.
• input e button: Campos para o nome, email, e um botão de envio.



#Estilo CSS do Rodapé e Formulário

Explicação
• footer: Define um fundo escuro e centraliza o conteúdo.
• .button-form: Estiliza o botão com uma cor de fundo, bordas arredondadas, e efeito de sombra.
• :hover: Aplica uma animação ao botão ao passar o mouse, para uma experiência interativa.













