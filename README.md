# Sistema Musical

Projeto didático de interface para um sistema de gerenciamento de artistas e músicas. O protótipo reúne telas de login, menu, cadastro e listagem, usando HTML e CSS.

> **Estado atual:** esta versão é somente front-end. Os formulários não enviam dados para um servidor nem salvam informações; as tabelas exibem exemplos fixos definidos no HTML.

## Funcionalidades da interface

- **Login:** formulário de entrada com credenciais de demonstração visíveis na própria tela (`admin` / `123`). Não há autenticação real.
- **Menu principal:** atalhos para as telas de artistas e músicas.
- **Cadastro de artistas:** campos para nome, gênero, país e foto, além de uma tabela com artistas de exemplo.
- **Cadastro de músicas:** campos para artista, título, álbum, gênero, link do YouTube, capa e letra, além de uma tabela de exemplo.
- **Biblioteca musical:** tabela de músicas de exemplo e controles visuais para busca e filtros por artista e gênero. Os filtros ainda não são aplicados.
- **Estilos responsivos:** folha de estilos compartilhada, com ajustes para telas menores.

## Arquivos

| Arquivo | Descrição |
| --- | --- |
| `login.html` | Tela de login de demonstração |
| `index.html` | Menu principal |
| `cadastro_artista.html` | Formulário e listagem de artistas |
| `cadastro_musica.html` | Formulário e listagem de músicas |
| `listagem_musicas.html` | Biblioteca musical com filtros visuais |
| `styles.css` | Estilos compartilhados por todas as páginas |

## Como executar

Não é necessário instalar dependências nem configurar um processo de build. Abra `login.html` em um navegador para começar, ou abra diretamente qualquer outra página HTML.

Para navegar pela demonstração, use os links e botões das páginas. Alguns formulários e ações, como editar, excluir e assistir, são apenas visuais ou usam links de exemplo.

## Tecnologias

- HTML5
- CSS3

## Próximos passos possíveis

Para transformar o protótipo em um sistema funcional, será necessário implementar um backend e integrar as telas a ele. Entre as evoluções possíveis estão:

- autenticação e controle de sessão;
- persistência de artistas e músicas em um banco de dados;
- processamento e validação de uploads de imagens;
- operações reais de cadastro, edição e exclusão;
- aplicação dos filtros da biblioteca;
- armazenamento e validação dos links de vídeo.
