# Painel Ticket Manager — Edição Executiva · Azul Atlântico

Versão de apresentação derivada do Painel Ticket Manager V45.3. A edição mantém o arquivo principal autocontido e aplica uma paleta autoral de azul-marinho, azul oceano e ciano suave, pensada para uma apresentação de gestão.

## Direção visual

- Azul-marinho `#0B263D`: navegação e hierarquia.
- Azul institucional autoral `#247FA5`: ações e foco.
- Ciano suave `#73C5D8`: realces, sem competir com o conteúdo.
- Fundo claro `#F4F8FB`: leitura e projeção.
- Cores de significado operacional — crítico, atenção, saudável, vencido e pendente — são preservadas para não alterar a interpretação dos indicadores.

A referência é uma linguagem visual corporativa azul; esta não é a identidade visual oficial da IOS Informática, não utiliza o logotipo oficial da empresa e não implica aprovação institucional.

## Publicar no GitHub Pages

1. Crie um repositório separado para esta edição, por exemplo `painel-ticket-manager-edicao-executiva`.
2. Extraia o ZIP e envie `index.html`, `README.md` e `SECURITY.md` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main` e pasta `/(root)`; salve.
5. Aguarde a publicação e use a URL que o GitHub Pages informar.

## Validação desta edição

- Os 23 testes internos de navegação semântica passaram após a correção de escopo da função de classificação; as regras de classificação não foram alteradas.
- Testes de renderização feitos em 1440 px e 760 px não mostraram overflow horizontal. Em telas estreitas, o painel impede que o drawer fechado crie rolagem horizontal global.

## Observações

- O painel é uma aplicação estática; não inclui serviço de autenticação, API ou backend multiusuário.
- O seletor de visão por perfil altera a experiência visual, mas não é controle de acesso real.
- Antes de uma apresentação em repositório/site público, confira a tela inicial e utilize somente dados fictícios ou anonimizados.
