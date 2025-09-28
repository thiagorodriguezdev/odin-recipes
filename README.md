Odin Recipes
📋 Descrição
O Odin Recipes é um projeto web simples desenvolvido como parte do currículo da The Odin Project (TOP), focado em aprendizado de HTML e CSS básicos. O site serve como um repositório pessoal de receitas favoritas, permitindo que os usuários visualizem uma lista de pratos e acessem detalhes completos de cada receita, incluindo ingredientes e instruções passo a passo.
O objetivo principal é praticar a estruturação de páginas web estáticas, links internos, formatação de texto e organização de conteúdo, sem o uso de JavaScript ou frameworks avançados. 

O site está hospedado no Vercel e acessível em: https://odin-recipes-nine-delta.vercel.app/.

🚀 Funcionalidades

Página Inicial: Uma landing page com uma introdução ao site e links para receitas selecionadas.
Lista de Receitas: Exibe cards ou links para receitas como Lasanha, Panquecas e Salada de Frango, com imagens e descrições breves.
Páginas de Receita Individual: Cada receita inclui:

Imagem principal do prato.
Lista de ingredientes.
Instruções de preparo passo a passo.

Navegação: Menu simples com link de volta para a home.

Sem dependências externas: Tudo é vanilla (puro), sem bibliotecas ou frameworks como Bootstrap ou React.
Imagens: Assets locais ou gratuitos (ex: Unsplash para fotos de comida).

📁 Estrutura de Pastas
odin-recipes/
├── index.html          # Página inicial
├── recipes/            # Pasta com páginas de receitas
│   ├── lasagna.html    # Exemplo: Receita de Lasanha
│   ├── pancakes.html   # Exemplo: Receita de Panquecas
│   └── chicken-salad.html # Exemplo: Receita de Salada de Frango
├── css/
│   └── style.css       # Estilos globais
├── images/             # Assets de imagens
│   ├── lasagna.jpg
│   ├── pancakes.jpg
│   └── chicken-salad.jpg
└── README.md           # Este arquivo

🏗️ Como Executar o Projeto
Pré-requisitos

Um editor de código (ex: VS Code, Sublime Text).
Navegador web moderno (Chrome, Firefox, etc.).

Passos para Rodar Localmente

Clone o Repositório:
git clone https://vercel.app/odin-recipes-nine-delta  # Ou baixe o ZIP do deploy

(Nota: Como é um deploy estático no Vercel, você pode baixar o código fonte diretamente do GitHub se vinculado, ou recriar com base nos arquivos HTML/CSS.)
Abra a Pasta:

Navegue até a raiz do projeto: cd odin-recipes.


Abra no Navegador:

Abra o arquivo index.html no seu navegador preferido.
Ou use um servidor local simples: python -m http.server 8000 (Python 3) e acesse http://localhost:8000.

Teste as Receitas:

Clique nos links para navegar entre as páginas.

Deploy no Vercel
Crie uma conta gratuita no Vercel.
Conecte seu repositório GitHub/GitLab.
Importe o projeto e deploy automático.

📝 Exemplos de Conteúdo
Receita de Exemplo: Lasanha Clássica

Ingredientes:

1 pacote de massa de lasanha.
500g de carne moída.
Queijo muçarela ralado.
Molho de tomate.


Instruções:

Cozinhe a carne em uma panela.
Monte as camadas em uma assadeira.
Asse por 30 minutos a 180°C.



(Conteúdo real pode variar; verifique o site para detalhes exatos.)
🤝 Contribuições
Este projeto é um exercício educacional, mas contribuições são bem-vindas! Siga estes passos:

Fork o repositório.
Crie uma branch: git checkout -b minha-feature.
Commit suas mudanças: git commit -m 'Adiciona nova receita'.
Push para a branch: git push origin minha-feature.
Abra um Pull Request.

📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
🙏 Agradecimentos

The Odin Project: Por fornecer o currículo e inspiração.
Vercel: Por hospedar o site gratuitamente.

Se você tiver sugestões ou encontrar bugs, abra uma issue no repositório! 😊