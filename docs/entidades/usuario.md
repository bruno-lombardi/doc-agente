---


---

<h1 id="usuário">Usuário</h1>
<p>Pode ser visitante, atleta, olheiro ou administrador. Clique nos tipos de usuário para saber mais sobre eles.</p>
<h2 id="visitante"><a href="https://bruno-lombardi.github.io/doc-agente/docs/estudo_de_caso#visitante">Visitante</a></h2>
<p>Qualquer um que acessa o site pelo navegador de internet. Pode ser um robô. Se um visitante acessa o site pela primeira vez, mas não se cadastra, podemos rastreá-lo e quando ele voltar podemos sugerir que ele se cadastre.</p>
<h3 id="atributos">Atributos</h3>
<ul>
<li>Endereço IP</li>
<li>Código único de rastreio no navegador</li>
<li>Data e hora da visita</li>
</ul>
<h2 id="atleta"><a href="https://bruno-lombardi.github.io/doc-agente/docs/estudo_de_caso#atleta">Atleta</a></h2>
<p>Qualquer um que possui um cadastro ativo no site como atleta.</p>
<h3 id="atributos-obrigatórios">Atributos obrigatórios</h3>
<ul>
<li>Tipo de usuário -&gt; <code>Atleta</code></li>
<li>Nome completo -&gt; <code>String</code></li>
<li>Data de nascimento -&gt; <code>Date</code></li>
<li>Sexo -&gt; <code>Char</code></li>
<li>Cidade -&gt; <code>Cidade</code></li>
<li>UF -&gt; <code>UF</code></li>
<li>Email -&gt; <code>String</code></li>
<li>Senha para login -&gt; <code>String</code></li>
<li>Foto de perfil -&gt; <code>Imagem</code></li>
<li>Modalidade de esporte -&gt; <code>Modalidade</code></li>
<li>Categoria do atleta -&gt; <code>Categoria</code></li>
<li>Tempo de experiência -&gt; <code>Integer</code></li>
<li>Altura (cm) -&gt; <code>Float</code></li>
<li>Peso (kg) -&gt; <code>Float</code></li>
</ul>
<h3 id="atributos-opcionais">Atributos opcionais</h3>
<ul>
<li>Biografia -&gt; <code>Text</code></li>
<li>5 imagens de destaque -&gt; <code>Imagem</code></li>
<li>Telefone -&gt; <code>String</code></li>
</ul>
<h2 id="olheiro"><a href="https://bruno-lombardi.github.io/doc-agente/docs/estudo_de_caso#olheiro">Olheiro</a></h2>
<p>Qualquer um que possui um cadastro ativo no site como olheiro.</p>
<h3 id="atributos-obrigatórios-1">Atributos obrigatórios</h3>
<ul>
<li>Tipo de usuário -&gt; <code>Olheiro</code></li>
<li>Nome completo -&gt; <code>String</code></li>
<li>Data de nascimento -&gt; <code>Date</code></li>
<li>Sexo -&gt; <code>Char</code></li>
<li>Cidade -&gt; <code>Cidade</code></li>
<li>UF -&gt; <code>UF</code></li>
<li>Email -&gt; <code>String</code></li>
<li>Senha para login -&gt; <code>String</code></li>
<li>Foto de perfil -&gt; <code>Imagem</code></li>
<li>Modalidade de esporte -&gt; <code>Modalidade</code></li>
</ul>
<h3 id="atributos-opcionais-1">Atributos opcionais</h3>
<ul>
<li>Biografia -&gt; <code>Text</code></li>
<li>Telefone -&gt; <code>String</code></li>
</ul>
<h2 id="administrador"><a href="https://bruno-lombardi.github.io/doc-agente/docs/estudo_de_caso#administrador">Administrador</a></h2>
<p>Não pode se cadastrar pela página de cadastros. É cadastrado apenas pelos webmasters.</p>
<h3 id="atributos-obrigatórios-2">Atributos obrigatórios</h3>
<ul>
<li>Tipo de usuário -&gt; <code>Administrador</code></li>
<li>Nome completo -&gt; <code>String</code></li>
<li>Data de nascimento -&gt; <code>Date</code></li>
<li>Sexo -&gt; <code>Char</code></li>
<li>Email -&gt; <code>String</code></li>
<li>Senha para login -&gt; <code>String</code></li>
</ul>

