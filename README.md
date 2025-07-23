<h1>ListaFix</h1>
<P>ListaFix é um projeto web que permite organizar seus filmes e séries favoritos, além de oferecer um espaço para listar hobbies, seguir uma receita e enviar feedbacks. O site é responsivo, com navegação intuitiva e layout agradável.
</P>
<h2>Visão Geral</h2>
<p>O objetivo principal do ListaFix é facilitar o gerenciamento pessoal de entretenimento, oferecendo:

Uma galeria de filmes recentes;

Uma seção com missão e visão do projeto;

Um menu lateral navegável;

Página com hobbies e receita;

Formulário de feedback funcional.</p>

<h2>Estrutura do Projeto</h2>

<p> ListaFix
├── index.html         # Página principal com galeria de filmes e missão/visão
├── listas.html        # Página com hobbies, receita e links úteis
├── feedback.html      # Página de formulário de feedback
├── styles.css         # Estilização das páginas
└── script.js          # Controle do menu lateral</p>

  
<h2>Funcionalidades</h2>
<h3>index.html</h3>
<P>Exibe a missão e visão do site.

Apresenta uma galeria de filmes com pôsteres e nomes.

Contém um menu lateral funcional, acessível por ícone "hambúrguer" (em telas menores).</p>

<h3>listas.html</h3>
<p>Lista os hobbies pessoais.

Apresenta uma receita simples de omelete.

Inclui links úteis externos (YouTube, TudoGostoso).</p>

<h3>feedback.html</h3>
<p>Formulário com os campos:

Nome

E-mail

Endereço completo

Tipo de feedback (elogio, sugestão ou reclamação)

Mensagem

Botão para envio (a funcionalidade de envio ainda pode ser implementada via backend).</p>

<h2>styles.css</h2>
<p>Estiliza todas as páginas com foco em legibilidade e organização.

Utiliza Flexbox e Grid para responsividade.

Inclui media query para ativar o menu hambúrguer em telas pequenas.</p>

<h2>script.js</h2>
<p>Implementa o controle de abertura e fechamento do menu lateral via JavaScript.</p>

<h2>Responsividade</h2>
<p>O projeto foi pensado para funcionar bem em diferentes tamanhos de tela, com menu lateral ativado por botão nas versões mobile (max-width: 600px).</p>

<h2>Possíveis Melhorias</h2>
<p>Conectar o formulário a um backend (PHP, Node.js ou Firebase).

Armazenar os filmes em JSON ou banco de dados.

Permitir que o usuário adicione seus próprios filmes.

Adicionar favoritos ou status de "já assistido".</p>

👨‍💻 Autor
Cassio Passos
Projeto desenvolvido com fins educacionais e práticos para reforçar conceitos de HTML, CSS e JavaScript.
