# admin-i18n

Esse projeto é de caráter temporário e uma força tarefa para traduzir o atual Admin para a língua inglesa. 

A estrutura de pastas e arquivos aqui dispostas simulam o path da URL onde as pages com seus textos se encontram na plataforma para a tradução.

Ex.: "en" indica para qual língua o português deva ser traduzido.
~~~~
Git:                     VTEX:
admin -> site -> Anexo = https://{{accountname}}.vtexcommercestable.com.br/admin/Site/Anexo.aspx
~~~~

### Quero ajudar. Como eu faço?

1. Escolha uma página para traduzir no project [Roadmap](https://github.com/vtex/admin-i18n/projects/1), os primeiros cards da coluna Backlog são de maior prioridade
2. Assign para você e dig in

### Como traduzir uma página?

1. Nomeie placeholders para os textos que precisam ser traduzidos em uma estrutura JSON
2. No valor destes placeholders coloque os próprios textos em português 
3. Copie a mesma estrutura JSON abaixo no próprio arquivo
4. Traduza os valores

### Observações importantes

1. Copie o texto em português exatamente como está atualmente na plataforma
2. Evite identação no JSON

Ex.:

~~~~
Git:                          VTEX:
admin -> site -> Categories = https://{{accountname}}.vtexcommercestable.com.br/admin/Site/Categories.aspx
~~~~
~~~~
{
	"category-page":{
		"title": "Categoria - Administração de Categorias",
		"breadcrumb-initial-page": "Página Inicial",
		"breadcrumb-product-management": "Cadastro de produtos",
		"breadcrumb-categories": "categorias",
		"button-hide-all": "Recolher Todos",
		"button-show-all": "Expandir Todos",
		"search-text": "Pesquisar categoria",
		"category-id-zero": "Categorias"
	}
}
~~~~
~~~~
{
	"category-page":{
		"title": "Category - Categories Management",
		"breadcrumb-initial-page": "Initial page",
		"breadcrumb-product-management": "Product management",
		"breadcrumb-categories": "Categories",
		"button-hide-all": "Hide all",
		"button-show-all": "Show all",
		"search-text": "Search category",
		"category-id-zero": "Categories"
	}
}
~~~~
