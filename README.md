# Estudos GitFind
## Descrição
`GitFind` é uma aplicação web desenvolvida com React que permite ao usuário pesquisar informações de perfil e repositórios públicos de qualquer usuário do GitHub. A interface recebe o nome de usuário do GitHub e, ao clicar em "Buscar", exibe as informações do perfil e lista os repositórios públicos do usuário.

### Tecnologias
- **React**: Biblioteca para criação de interfaces de usuário.
- **Fetch API**: Para chamadas HTTP à API pública do GitHub.
- **React Hooks**: useState para gerenciamento de estados no componente.

### Estrutura do Projeto

```
src
├───assets                    - Contém imagens e outros arquivos de mídia.
├───components                - Componentes reutilizáveis.
│   ├───Header                - Componente de cabeçalho.
│   │   ├───Header.js         - Arquivo do componente Header.
│   │   └───styles.css        - Estilos específicos do Header.
│   └───ItemList              - Componente para exibir os repositórios.
│       ├───ItemList.js       - Arquivo do componente ItemList.
│       └───styles.css        - Estilos específicos do ItemList.
└───pages                     - Páginas da aplicação.
    └───Home                  - Página principal da aplicação.
        ├───Home.js           - Arquivo da página Home.
        └───styles.css        - Estilos específicos da Home.
```

### Descrição dos Arquivos
- `assets`/: Diretório para armazenar a imagem.
- `components`/: Diretório para os componentes reutilizáveis da aplicação, Header e ItemList.
- `Header`: Contém o componente de cabeçalho com seu arquivo de estilo.
- `ItemList`: Contém o componente para exibição dos repositórios e seus estilos.
- `pages`/: Diretório para as páginas principais da aplicação.
- `Home`: Página inicial que contém a lógica de busca e exibição de dados do GitHub.

### Funcionalidades
**Busca de Usuário**: Permite buscar um usuário GitHub pelo nome de usuário.

**Exibição de Perfil**: Mostra a imagem, nome e biografia do usuário.

**Lista de Repositórios**: Exibe uma lista de repositórios públicos do usuário, com o título e descrição.
