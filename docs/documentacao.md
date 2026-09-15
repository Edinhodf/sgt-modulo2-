# Documentação do Projeto Final — HTML5 e CSS3

## 1. Identificação do projeto

**Projeto:** Sistema de Gerenciamento de Tarefas  
**Módulo:** HTML5 e CSS3  
**Ano:** 2026  
**Autor:** Edson Mendes

## 2. Objetivo

Desenvolver uma interface web responsiva para um sistema de gerenciamento de tarefas, utilizando HTML5 semântico e CSS3, com telas de login, cadastro, dashboard e detalhes da tarefa.

## 3. Tecnologias utilizadas

- HTML5
- CSS3
- Flexbox
- CSS Grid
- Media Queries
- Variáveis CSS
- `clamp()` para tipografia responsiva
- Recursos de acessibilidade e navegação por teclado

## 4. Estrutura de diretórios

```text
/
|-- index.html
|-- pages/
|   |-- cadastro.html
|   |-- dashboard.html
|   |-- detalhes.html
|-- css/
|   |-- estilos.css
|-- images/
|-- docs/
|   |-- documentacao.md
```

## 5. Mapa do site

- [x] Home / Login (`index.html`)
- [x] Página 2: Cadastro (`pages/cadastro.html`)
- [x] Página 3: Dashboard (`pages/dashboard.html`)
- [x] Página 4: Detalhes da Tarefa (`pages/detalhes.html`)

## 6. Descrição das páginas

### Login
Tela inicial do sistema com campos de e-mail e senha e acesso ao cadastro.

### Cadastro
Tela para criação de uma nova conta com nome, e-mail e senha.

### Dashboard
Apresenta as tarefas cadastradas em cards, com ações para editar e concluir.

### Detalhes da Tarefa
Exibe informações completas da tarefa selecionada, status, data, descrição e ações.

## 7. Semântica HTML5

Foram utilizados elementos semânticos como `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `form`, `label`, `input`, `button`, `dl`, `dt` e `dd`.

## 8. Acessibilidade — WCAG 2.2 AA

Checklist aplicado:

- [x] `lang="pt-BR"` definido.
- [x] Um título principal por página.
- [x] Headings em ordem lógica.
- [x] Landmarks semânticos.
- [x] Link “Pular para o conteúdo”.
- [x] Labels associados aos campos.
- [x] Foco visível com `:focus-visible`.
- [x] Navegação por teclado.
- [x] Contraste adequado para textos e controles principais.
- [x] Mensagens/nomes acessíveis para ícones.
- [x] Preferência `prefers-reduced-motion`.

## 9. Responsividade

A estratégia utilizada é mobile-first, com reorganização do layout para telas menores.

Telas consideradas:
- Celulares: aproximadamente 360×640 até 414×896.
- Tablets: aproximadamente 768×1024.
- Desktop: 1024px ou mais.

No dashboard, os seis cards passam de três colunas no desktop para uma coluna no celular.

## 10. Conceitos de CSS aplicados

- Cascata
- Especificidade
- Herança
- Box Model
- Unidades relativas
- Variáveis CSS
- Flexbox
- CSS Grid
- Media Queries
- Tipografia responsiva com `clamp()`
- `prefers-reduced-motion`

## 11. Plano de testes

| Caso | Passos | Resultado esperado | Status |
|---|---|---|---|
| Login | Abrir `index.html` e preencher campos | Formulário permite avançar ao dashboard | OK |
| Cadastro | Abrir cadastro e preencher os três campos | Formulário permite avançar ao dashboard | OK |
| Dashboard | Abrir dashboard | Seis tarefas aparecem em cards | OK |
| Detalhes | Clicar no ícone/Editar | Página de detalhes é aberta | OK |
| Responsividade | Reduzir a largura da janela | Elementos se reorganizam sem scroll horizontal | OK |
| Teclado | Usar Tab | Elementos interativos recebem foco visível | OK |

## 12. Changelog

| Data | Autor | Alteração |
|---|---|---|
| 14/09/2026 | Edson Mendes | Criação e organização das páginas HTML5 e CSS3 |
| 14/09/2026 | Edson Mendes | Implementação da responsividade desktop/mobile |
| 14/09/2026 | Edson Mendes | Inclusão de recursos de acessibilidade |

## 13. Declaração do estudante

Declaro que este trabalho foi realizado pela equipe acima identificada e que todas as fontes de terceiros utilizadas foram devidamente citadas.

**Assinatura:** EDSON MENDES DE SÁ  
**Data:** 14/09/2026
