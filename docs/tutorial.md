# Configuração Simplificada do `mkdocs.yml`

Este é um guia básico e simplificado para configurar o arquivo `mkdocs.yml` no MkDocs.

```yaml
# Nome do site (exibido no cabeçalho e título da página)
site_name: "Meu Projeto"

# URL do site (útil para SEO e links)
site_url: "https://meusite.com"

# Descrição do site (aparece nos metadados, bom para SEO)
site_description: "Documentação do Meu Projeto"

# Nome do autor (opcional, usado em metadados)
site_author: "Seu Nome"

# URL do repositório (opcional, aparece no cabeçalho com um link)
repo_url: "https://github.com/usuario/projeto"
repo_name: "GitHub"

# Tema do site (pode ser 'material' ou outro tema que preferir)
theme:
  name: "material"
  palette:
    primary: "indigo"
    accent: "deep orange"

# Navegação (define a ordem das páginas no menu)
nav:
  - Home: index.md
  - Instalação: instalacao.md
  - Uso:
      - Básico: uso_basico.md
      - Avançado: uso_avancado.md

# Plugins (adiciona funcionalidades extras)
plugins:
  - search  # Pesquisa interna do site
  - minify:  # Otimiza HTML, CSS e JS para menor tamanho
      minify_html: true

# Extensões Markdown (adiciona funcionalidades extras ao Markdown)
markdown_extensions:
  - toc         # Gera automaticamente uma tabela de conteúdos
  - admonition  # Blocos de alerta (informação, aviso, etc)

# Arquivos CSS e JS extras (personalize a aparência e comportamento)
extra_css:
  - "css/estilos_custom.css"

extra_javascript:
  - "js/scripts_custom.js"
 ```

# Exemplos de Como Adicionar Itens

### 1. Adicionando uma Página Simples

Para adicionar uma nova página simples à navegação:

```yaml
nav:
  - Home: index.md
  - Sobre: sobre.md  # Adicionando a página "Sobre"
```

### 2. Adicionando Subpáginas
Para organizar suas páginas em uma hierarquia, você pode adicionar subpáginas. Aqui está como fazer isso:
```yaml
nav:
  - Home: index.md
  - Tutoriais:
      - Introdução: tutoriais/introducao.md
      - Avançado: tutoriais/avancado.md  # Adicionando uma subpágina
```

### 3. Modificando um Item Existente
Se você deseja alterar o título ou o arquivo de uma página existente, basta modificar o item correspondente. Por exemplo, para mudar "Sobre" para "Quem Somos":

```yaml
nav:
  - Home: index.md
  - Quem Somos: sobre.md  # Alterando o título de "Sobre" para "Quem Somos"
```

### 4. Removendo um Item
Para remover um item, basta excluí-lo da seção `nav`. Por exemplo, se você quiser remover a página "Sobre":

```yaml
nav:
  - Home: index.md
  # - Sobre: sobre.md  # Comentado ou removido
```

### 5. Agrupando Itens
Você pode agrupar várias páginas em um único item para manter a navegação organizada. Aqui está um exemplo:

```yaml
nav:
  - Home: index.md
  - Tutoriais:
      - Introdução: tutoriais/introducao.md
      - Avançado: tutoriais/avancado.md
  - Referência:
      - API: referencia/api.md
      - FAQ: referencia/faq.md
```

### Dicas Importantes
- Caminhos Relativos: Os caminhos dos arquivos devem ser relativos à pasta docs. Se o seu arquivo estiver em uma subpasta, inclua o caminho completo.
- Ordenação: A ordem dos itens na seção nav reflete a ordem em que eles aparecerão no menu de navegação. Basta reorganizar os itens para mudar a ordem.
- Consistência: Certifique-se de que os nomes dos arquivos Markdown estejam corretos e correspondam aos que você criou na pasta docs.