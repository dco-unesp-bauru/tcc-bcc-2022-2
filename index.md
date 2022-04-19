# TCCs do BCC 2020 1º semestre

A publicação dos TCCs de BCC tem por objetivo inspirar e
apresentar aos alunos, professores, funcionários e a comunidade (em especial as
empresas e desenvolvedores de software locais) as invoações e realizações
acadamicas consquistas e contruidas pelos alunos graduandos desta universidade.

# Trabalhos

<ul>
	{% for post in site.posts %}
	<li>
	<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
	<p>Autor(a): {{ post.autor }} <br />
	Orientador(a): {{ post.orientador }}</p>
	</li>
	{% endfor %}
</ul>
