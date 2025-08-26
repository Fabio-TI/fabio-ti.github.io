---
layout: default
---

<h1 class="page-heading">Diário de um Engenheiro Cristão</h1>
<p><strong>Um espaço onde fé, família e código se encontram.</strong></p>

<p>Meu nome é Fábio de Lima. Sou engenheiro de software, marido da Marcela, pai da Manuela e Testemunha de Jeová desde 1989.</p>

<p>Aqui, escrevo sobre:</p>
<ul>
  <li>Como a disciplina técnica fortalece minha fé</li>
  <li>Como automação me dá tempo com minha família</li>
  <li>Por que excelência não é orgulho — é adoração</li>
</ul>

<hr>

<h2>Perfil Profissional</h2>
<p>
  <a href="https://linkedin.com/in/fabio-delima">LinkedIn</a> | 
  <a href="https://github.com/fabio-ti">GitHub</a>
</p>
<ul>
  <li>Engenheiro de Software | Engenheiro de Dados, Azure, AWS, GCP, Databricks | SAP 4Hana | Python | FullStack</li>
  <li>Metodologias Ágeis, Gestão de Dados, Arquitetura de Sistemas</li>
</ul>

<h2>Últimos Posts</h2>
<ul>
  {% for post in site.posts limit:15 %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <br><small>{{ post.date | date: "%d/%m/%Y" }}</small>
  </li>
  {% endfor %}
</ul>
<ul>
  <li>
    <a href="https://github.com/fabio-ti/automacao-para-o-bem" target="_blank">Automação para o Bem</a><br>
    <small>Scripts em Python para ajudar pessoas comuns a ganharem tempo.</small>
  </li>
</ul>

<p>
  • <a href="/about">Sobre mim →</a><br>  
  • <a href="/feedback">Deixe uma mensagem →</a>
</p>
