# Atlas da Guitarra

Livro pessoal e interativo de estudos de guitarra, em português. Site estático em HTML, CSS e JavaScript, sem framework, dependências de execução ou etapa de build.

## Conteúdo

- Oito capítulos: escalas naturais, pentatônicas, harmônicas, CAGED, modos gregos, tríades e arpejos, blues e técnica.
- Diagramas do braço, tablaturas, exercícios e frases com áudio sintetizado.
- Metrônomo, acompanhamento harmônico e treino auditivo.
- Modos claro e escuro, rotina, anotações e progresso.

## Executar localmente

Abra o arquivo `index.html` no navegador. Para usar um endereço local consistente, com Python instalado, execute na pasta do projeto:

```sh
python -m http.server 4173
```

Acesse http://localhost:4173. O terminal precisa permanecer aberto enquanto você usa esse endereço.

## Arquivos

- `index.html`: estrutura inicial da página.
- `style.css`: estilos, temas e layout responsivo.
- `app.js`: conteúdo dos capítulos, diagramas e funcionalidades.

Edite esses três arquivos diretamente. Não é necessário instalar pacotes.

## Publicar no GitHub Pages

1. Envie os arquivos desta pasta para seu repositório.
2. Em **Settings → Pages**, escolha **Deploy from a branch**.
3. Selecione sua branch (normalmente `main`) e a pasta `/ (root)`.
4. Aguarde o GitHub informar o endereço do site.

Os caminhos dos arquivos são relativos, permitindo publicar em um subdiretório do GitHub Pages.

## Dados pessoais e áudio

Anotações, favoritos, progresso e preferência de tema ficam no armazenamento local do navegador. Eles não são enviados ao GitHub e não são sincronizados entre dispositivos ou endereços. Use a exportação do caderno na página de rotina para guardar uma cópia dos registros.

A reprodução usa a Web Audio API e começa após uma interação com a página. As fontes são carregadas do Google Fonts; se não houver conexão, o navegador usa as fontes alternativas definidas no CSS.
