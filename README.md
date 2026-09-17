# CDN 1CRI

Repositório de conteúdo estático (imagens, JS, CSS, fontes) do Cartório do
1º Ofício de Registro de Imóveis de Camaçari.

Este repositório serve como CDN para os sistemas e aplicações do Cartório:
basta subir o arquivo e usá-lo pelo link.

## Como usar

1. Adicione o arquivo na pasta correta:

   | Pasta       | Conteúdo                          |
   |-------------|-----------------------------------|
   | `images/`   | PNG, JPG, SVG, ícones, logos      |
   | `js/`       | Scripts JavaScript                |
   | `css/`      | Folhas de estilo                  |
   | `fonts/`    | Tipografias (WOFF, TTF, etc.)     |

2. Faça commit e push (via GitHub Desktop ou git).
3. Use o link da tabela abaixo.

## Padrões de URL

| Tipo             | URL                                                                                                |
|------------------|----------------------------------------------------------------------------------------------------|
| **Produção (CDN)** | `https://cdn.jsdelivr.net/gh/Desenvolvimento1CRI/cdn@main/<caminho>`                              |
| **Preview imediato** | `https://raw.githubusercontent.com/Desenvolvimento1CRI/cdn/main/<caminho>`                       |
| Pages (se habilitado) | `https://desenvolvimento1cri.github.io/cdn/<caminho>`                                           |

### Exemplos

- `images/logo.png`
  - Produção: `https://cdn.jsdelivr.net/gh/Desenvolvimento1CRI/cdn@main/images/logo.png`
  - Preview: `https://raw.githubusercontent.com/Desenvolvimento1CRI/cdn/main/images/logo.png`

> **Produção**: link do jsDelivr — servido por CDN global com cache e
> compressão. Ao fazer push, o cache é invalidado automaticamente em minutos.
>
> **Preview**: link "raw" do GitHub — sempre reflete o conteúdo atual, sem
> cache. Use durante o desenvolvimento; prefira o link de produção nos
> sistemas.

## Convenções de nome

- Nomes em minúsculas, sem espaços nem acentos.
- Use hífen (`-`) para separar palavras: `logo-cri-branco.png`.
- Evite caracteres especiais (`#`, `%`, `&`, `?`, `=`, `@`) no nome do arquivo.

## Licença

Todo o conteúdo deste repositório é **propriedade exclusiva** do Cartório do
1º Ofício de Registro de Imóveis de Camaçari. O uso fora dos sistemas do
Cartório, sem autorização por escrito, é proibido. Consulte o arquivo
[LICENSE](LICENSE) para os termos completos.