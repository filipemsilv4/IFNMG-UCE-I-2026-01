# Wiki e Documentação

Este documento registra como a wiki publicada do projeto funciona e como ela deve ser mantida.

## Princípio central

O repositório continua sendo a fonte de verdade.

Isso significa:
- o conteúdo nasce e evolui dentro de `docs/`;
- o site gerado com `MkDocs` é uma camada de navegação e publicação;
- a wiki nativa do GitHub, se vier a ser usada, deve apenas apontar para o site publicado.

## Stack adotada

- `MkDocs`
- `mkdocs-shadcn`
- `GitHub Pages`
- GitHub Actions para build e deploy

## Arquivos principais

- [`mkdocs.yml`](https://github.com/filipemsilv4/IFNMG-UCE-I-2026-01/blob/main/mkdocs.yml): configuração da wiki, tema e navegação.
- [`requirements-docs.txt`](https://github.com/filipemsilv4/IFNMG-UCE-I-2026-01/blob/main/requirements-docs.txt): dependências para build local e CI.
- [`.github/workflows/docs.yml`](https://github.com/filipemsilv4/IFNMG-UCE-I-2026-01/blob/main/.github/workflows/docs.yml): validação e deploy no GitHub Pages.
- [`docs/index.md`](../index.md): página inicial da wiki.

## Fluxo de manutenção

1. Edite os arquivos dentro de `docs/`.
2. Se a estrutura da wiki mudar, atualize também `mkdocs.yml`.
3. Rode um build local antes de abrir PR quando mexer em navegação ou links.
4. O deploy acontece automaticamente via GitHub Actions ao fazer merge para `main`.

## Build local

Com `uv`:

```bash
uv venv
source .venv/bin/activate
uv pip install -r requirements-docs.txt
mkdocs serve
```

Ou com `pip`:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements-docs.txt
mkdocs serve
```

Para validar sem subir servidor:

```bash
mkdocs build --strict
```

## Convenções

- priorizar links relativos entre documentos do próprio repositório;
- nunca usar caminhos absolutos do filesystem local;
- evitar duplicar texto entre múltiplos arquivos quando um link resolve o problema;
- manter nomes e seções coerentes entre repo e wiki;
- preferir atualizações no conteúdo original em vez de criar páginas-resumo redundantes.

> Arquivos fora de `docs/` (como `mkdocs.yml` e `requirements-docs.txt`) não são navegáveis pela wiki, então os links para eles apontam diretamente para o GitHub.

## Quando atualizar a navegação

Atualize `mkdocs.yml` quando:
- surgir uma nova etapa do projeto;
- uma seção deixar de refletir a organização real do trabalho;
- um documento passar a ser ponto de entrada importante;
- a ordem de leitura precisar mudar.

## Critério de qualidade

A wiki deve facilitar descoberta e leitura sem esconder a estrutura real do repositório.

Se uma mudança deixar o site mais bonito, mas tornar o conteúdo mais difícil de manter, a mudança não vale a pena.
