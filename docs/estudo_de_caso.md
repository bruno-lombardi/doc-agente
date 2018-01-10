---


---

<h1 id="estudo-de-caso">ESTUDO DE CASO</h1>
<h2 id="introdução">Introdução</h2>
<p>Este é o documento que serve de base para todos os outros documentos, já que é a base do projeto, onde deve ser descrito de maneira narrativa a funcionalidade do sistema. O objetivo é descrever as ações que o usuário pode realizar, os resultados esperados de suas ações e suas restrições.</p>
<p>Para facilitar a leitura, vamos classificar nossos atores (usuários, administradores, visitantes) como sendo uma <strong>entidade</strong>. No entanto, entidades não se restringem a isso. Para mais detalhes veja a página sobre <a href="entidade/">entidades</a>. Cada <strong>entidade</strong> pode realizar determinadas <em>ações</em>. As <em>ações</em> possuem restrições e consequências. Entendido essa parte, dividimos esse documento de acordo com os atores, a começar pelos usuários.</p>
<h2 id="usuários">Usuários</h2>
<h3 id="visitante">Visitante</h3>
<p>Ao acessar o site pela primeira vez, o visitante abre a página <a href="#">Início</a>.</p>
<h4 id="ações">Ações</h4>
<ul>
<li><a href="#">Cadastrar-se</a></li>
<li>Fazer login</li>
<li>Ver a <a href="#">linha do tempo</a> com as últimas postagens de atletas já cadastrados</li>
<li>Ver o <a href="#">perfil</a> de atletas cadastrados</li>
</ul>
<h4 id="restrições">Restrições</h4>
<ul>
<li>Comentar ou curtir publicações de atletas</li>
<li>Pesquisar e ver o perfil de <a href="#">olheiros</a></li>
<li>Criar <a href="#">publicações</a></li>
<li>Acessar a página de <a href="">notícias</a></li>
<li>Conversar com outros atletas</li>
</ul>
<p>Ao retornar ao site, o visitante é sugerido a criar uma conta.</p>
<h3 id="atleta">Atleta</h3>
<p>Ao fazer login, o atleta é redirecionado à página inicial. Ele é uma extensão do que o visitante pode fazer, o que significa que ele pode fazer tudo que o visitante faz, sem as restrições que o visitante possui.</p>
<h4 id="ações-1">Ações</h4>
<ul>
<li>Seguir olheiros</li>
<li>Criar uma carreira, onde adicionam prêmios, conquistas e realizações</li>
<li>Adicionar 5 fotos de destaque no perfil</li>
<li>Adicionar sua modalidade de esporte e categoria</li>
</ul>
<h4 id="restrições-1">Restrições</h4>
<ul>
<li>Mudar seu tipo de conta para olheiro</li>
<li>Ver o email ou número de telefone de outros atletas</li>
</ul>
<h3 id="olheiro">Olheiro</h3>
<p>Ao fazer login, é redirecionado para página inicial. O olheiro é um caso especial de usuário. Ele pode observar não apenas o perfil de atletas, mas também as estatísticas das várias modalidades de esporte existentes no site, como saber quantos atletas existem em determinada modalidade.</p>
<h3 id="administrador">Administrador</h3>
<p>Ao fazer login, é redirecionado para seu painel administrativo. Tem acesso a funções privilegiadas para gerenciar o sistema.</p>
<h4 id="ações-2">Ações</h4>
<ul>
<li>Criar, remover e atualizar usuários</li>
<li>Criar, remover e atualizar publicações de usuários</li>
<li>Enviar mensagens para todos os usuários</li>
</ul>
<h4 id="restrições-2">Restrições</h4>
<ul>
<li>Criar, atualizar e remover administradores</li>
</ul>
<h2 id="cadastro-e-autenticação">Cadastro e autenticação</h2>
<p>O cadastro não é obrigatório para os visitantes acessaram o conteúdo do site. Ao realizar o cadastro, o usuário preenche informações obrigatórias, como nome completo, data de nascimento, etc.</p>
<p>O cadastro possui duas etapas, sendo que a segunda etapa distingue o usuário de atleta ou olheiro. Mais detalhes sobre as informações que cada um deve preencher são encontrados na página da entidade <a href="entidades/usuario">Usuário</a>.</p>
<h2 id="linha-do-tempo">Linha do tempo</h2>
<p>A linha do tempo faz parte da página inicial do site. Lá podemos encontrar as últimas atividades ou publicações realizadas pelos atletas e olheiro. Apresentando as atividades mais recentes primeiro, a linha do tempo tem o objetivo de manter os atletas atualizados sobre a comunidade.</p>
<p>A linha do tempo é composta de <a href="#">publicações</a>, e para cada atleta, ela é personalizada. Isso quer dizer que as publicações que aparecem para um usuário, não são as mesmas que aparecem para outro. A personalização é baseada nos interesses do usuário. Portanto, se o atleta tem interesse em futebol, ele vai ver publicações relacionadas a futebol. Os atletas podem alterar seus interesses a qualquer momento.</p>
<p>A linha do tempo não será paginada, será dinâmica, e carregará as publicações enquanto o usuário navega pela página, similar ao que acontece no facebook.</p>
<h2 id="perfil-dos-atletas">Perfil dos atletas</h2>
<p>O perfil dos atletas irá mostrar seus dados para as pessoas. As fotos em destaque que eles escolheram, e seus vídeos. Além disso, as publicações feitas pelo atleta apareceram em sua página de perfil, que terá uma linha do tempo própria.</p>
<h2 id="perfil-dos-olheiros">Perfil dos olheiros</h2>
<p>O perfil dos olheiros não mostra muitos dados sobre eles. No entanto, tem uma linha do tempo também com as publicações feitas pelos olheiros.</p>
<h2 id="publicações">Publicações</h2>
<p>Publicações são formas de os usuários se promoverem, mostrarem suas conquistas em suas carreiras ou socializar.</p>
<h2 id="painel-do-usuário">Painel do usuário</h2>
<p>Ao acessar sua própria página de perfil, o usuário abre uma página personalizada onde pode alterar suas informações, criar novas publicações e ver como estão suas mensagens.</p>
<h2 id="painel-do-administrador">Painel do administrador</h2>
<p>O administrador possui um painel distinto, que ele pode usar para gerenciar vários aspectos do site.</p>
<h2 id="pesquisa-de-usuários">Pesquisa de usuários</h2>
<p>O site possui uma página de pesquisa personalizada. Nessa página, é possível pesquisar atletas por nome, idade, sexo, cidade, UF, modalidade de esporte, categoria, altura ou peso. A pesquisa de olheiros pode não incluir todas essas opções.</p>

