# admin-i18n

Esse projeto é de caráter temporário e uma força tarefa para traduzir o atual Admin para a língua inglesa. 

A estrutura de pastas e arquivos aqui dispostas simulam o path da URL onde os textos se encontram para a tradução.

Ex.: "en" indica para qual língua o português deva ser traduzido.

Git:                     VTEX:
admin -> site -> Anexo = https://{{accountname}}.vtexcommercestable.com.br/admin/Site/Anexo.aspx

##Como traduzir uma página?

1 - Nomei placeholders para os textos que precisam ser traduzidos em uma estrutura JSON
2 - No valor destes placeholders coloque os próprios textos em português 
3 - Copie a mesma estrutura JSON
4 - Traduza os valores

Ex.:

Git:                          VTEX:
admin -> site -> Categories = https://{{accountname}}.vtexcommercestable.com.br/admin/Site/Categories.aspx

{
	"category-page":{
		"title": "Categoria - Administração de Categorias",
		"breadcrumb": {
			"inicial-page": "Página Inicial",
			"product-management": "Cadastro de produtos",
			"categories": "categorias"
		},
		"button":{
			"hide-all": "Recolher Todos",
			"show-all": "Expandir Todos"
		},
		"search-text": "Pesquisar categoria",
		"category-id-zero": "Categorias"
	}
}

{
	"category-page":{
		"title": "Category - Categories Management",
		"breadcrumb": {
			"inicial-page": "Inicial page",
			"breadcrumb-product-management": "Product management",
			"breadcrumb-categories": "Categories"
		},
		"button": {
			"hide-all": "Hide all",
			"show-all": "Show all"
		},
		"search-text": "Search category",
		"category-id-zero": "Categories"
	}
}
