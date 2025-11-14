

# Configurações Personalizadas do VS Code

Este repositório disponibiliza uma configuração otimizada do VS Code para aumentar produtividade, foco e legibilidade, principalmente para projetos em JavaScript/TypeScript, C e Svelte. A base foi pensada para desenvolvedores buscando uma interface mais limpa, recursos automatizados de formatação e integração nativa com principais extensões modernas.

#### Aparência e Interface

- Tema escuro padrão para melhor conforto visual.
- Barra de atividades movida para o topo e barra de status oculta, maximizando a área útil.
- Menu compacto, nomes curtos nas abas e destaque rápido para arquivos modificados.

#### Editor de Código

- Fonte monoespaçada com ligaduras, tamanho 18 e espaçamento ampliado.
- Linha atual destacada na gávea, highlight semântico, sticky scroll e animação suave no cursor.
- Minimapa desativado para eliminar distrações.
- Quebra automática de linhas, formatação ao salvar/colar e Prettier como formatador principal.
- Formatação inteligente para C e Svelte via plugins adequados.
- Ações automáticas ao salvar corrigem problemas, organizam imports e ordenam membros.

#### Navegação

- Breadcrumb habilitado para rápida localização no projeto.
- Pastas não compactadas e agrupamento inteligente via padrões de nesting definidos.

#### Terminal

- Terminal integrado ajustado: fonte, perfil-padrão para Linux e sempre usando terminal embutido.

#### Tailwind CSS

- Reconhecimento de atributos e funções customizadas para classes Tailwind direto nos arquivos.

#### Organização

- Oculta pastas como `.expo`, remove espaços ao fim das linhas, mantém projeto limpo.

#### Integrações

- Atualização automática de imports ao mover arquivos em TypeScript/JavaScript.
- GitLens configurado com Copilot GPT-4.1 para auxílio de IA.
- Notificações e comandos desnecessários de extensões como Postman e chat desativados.
- Plugin TS para Svelte ativo.

#### Debug

- Esconde o código fonte no modo assembly e ajusta delay do ErrorLens.
