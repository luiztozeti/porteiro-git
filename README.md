# Porteiro Git

Miniaplicação web de login simulada, criada para a atividade avaliativa de **Gestão de Projetos de Software** (4º ADS - IFSP Câmpus Bragança Paulista).

## Integrantes
- Luiz Tozeti
- Pedro Vicente
- Pedro Alcântara
- Henrique Martinelli

## Propósito
Praticar controle de versão com Git/GitHub: branches, commits, pull requests com revisão de código, tags, releases e changelog, simulando o planejamento e a execução de releases de um software.

## Plano de releases

| Release | Tag | Branch | Conteúdo |
|---|---|---|---|
| 1 | `v0.1.0` | `release1` | Tela de login (`index.html`); ao clicar em ENTRAR exibe “em construção” (`working.html`) |
| 2 | `v0.2.0` | `release2` | Login chama a página do administrador (`pg001.html`) sem validar os campos |
| 3 | `v1.0.0` | `release3` | Funcionamento completo: usuário em branco → `msg.html`; `admin` → `pg001.html`; qualquer outro → `pg002.html` |

## Estratégia de branches
- `main`: versão estável.
- `develop`: integração.
- `release1`, `release2`, `release3`: branches de desenvolvimento de cada release.
- `ajustev1`: branch de correção.

## Como executar
Abra `index.html` no navegador. Não há dependências externas.