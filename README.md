# IA Descentralizada (DeAI)

Site estático sobre IA Descentralizada, com foco em UX, acessibilidade e conteúdo introdutório. O projeto é leve (HTML, CSS e JavaScript puros) e pode ser publicado facilmente no GitHub Pages.

## Demonstração
- Publicação recomendada: GitHub Pages do repositório `nioac/Decentralized_AI`.
- Após habilitar o Pages (ver instruções abaixo), o site ficará disponível em:
  - https://nioac.github.io/Decentralized_AI/

## Estrutura do Projeto
```
.
├── 02/
│   └── Index.html          # Variante de página (exemplo/rascunho)
├── 2411.17461v3.pdf        # Material/PDF de referência
├── Beneficios.txt          # Notas de conteúdo
├── index.html              # Página principal
├── script.js               # Interações e animações
└── styles.css              # Estilos globais
```

## Tecnologias Utilizadas
- HTML5 sem frameworks
- CSS3 com variáveis e responsividade
- JavaScript (vanilla) com IntersectionObserver, rolagem suave e otimizações leves

## Como Rodar Localmente
Pré-requisitos: Python 3 instalado (para um servidor HTTP simples).

1. Abra um terminal na pasta do projeto.
2. Execute:
   ```bash
   python -m http.server 8001
   ```
3. Acesse no navegador: http://localhost:8001/

Dica: você pode usar qualquer servidor estático (p. ex., `npx serve`), se preferir Node.js.

## Publicação no GitHub Pages
1. No GitHub, vá em: Settings → Pages.
2. Em “Build and deployment”, escolha “Deploy from a branch”.
3. Branch: `main` e pasta: `/ (root)`.
4. Salve. Aguarde alguns minutos até o deploy concluir.
5. O site ficará disponível em: https://nioac.github.io/Decentralized_AI/

## Personalização Rápida
- Título e metadados: edite em `index.html` (head e hero).
- Paleta de cores e tipografia: variáveis e estilos em `styles.css`.
- Conteúdo das seções (Pilares, Exemplos, Desafios, Futuro): diretamente no `index.html`.
- Botão final (MIT Media Lab): já configurado para abrir em nova aba com `target="_blank"` e `rel="noopener noreferrer"`.

## Recursos de UX e Acessibilidade
- Rolagem suave com gerenciamento de foco para âncoras internas.
- Animações de entrada com IntersectionObserver (respeitando `prefers-reduced-motion`).
- Botão “voltar ao topo” e barra de progresso de leitura.
- Navegação responsiva e contraste adequado.

## Boas Práticas
- Evite inserir segredos/keys no repositório.
- Otimize imagens (prefira SVG quando possível).
- Mantenha o HTML semântico (melhora SEO e acessibilidade).

## Contribuição
Sinta-se à vontade para abrir issues e PRs com melhorias de conteúdo, design ou acessibilidade.

## Licença
Defina a licença de sua preferência para o projeto (por exemplo, MIT). Até que seja definida, considere o conteúdo como “Todos os direitos reservados”.