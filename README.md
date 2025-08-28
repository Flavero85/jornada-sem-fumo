Jornada Sem Fumo 🚭
Descrição
Jornada Sem Fumo é um Progressive Web App (PWA) interativo e motivacional, desenhado para ajudar utilizadores a parar de fumar através do acompanhamento de progresso, ferramentas de apoio e gamificação.

O seu diferencial é o Sistema de Recaída Inteligente, que preserva o progresso total do utilizador após um deslize, reforçando a resiliência na jornada.

✨ Funcionalidades Principais
Painel Personalizado: Saudação com nome e avatar de desenho.

Acompanhamento em Tempo Real: Contador de tempo sem fumar, cigarros evitados e dinheiro economizado.

Metas e Saúde: Acompanhe metas financeiras e a recuperação da sua saúde com barras de progresso.

Gamificação: Desbloqueie conquistas por marcos importantes, comemoradas com uma chuva de confetes.

Botão de Pânico: Oferece dicas e mini-jogos de distração para momentos de vontade intensa.

Diário de Bordo: Registe os seus sentimentos e vitórias.

Sistema de Recaída Inteligente: Regista recaídas no diário e reinicia o contador de tempo, mas preserva o progresso e as conquistas totais.

PWA Completo: Instale a aplicação no seu dispositivo, use-a offline e receba notificações push sobre as suas conquistas.

🚀 Como Publicar no GitHub Pages
Siga estes passos para colocar o seu projeto online e torná-lo instalável.

Passo 1: Preparar os Ficheiros
Crie a seguinte estrutura de pastas e ficheiros no seu computador:

/jornada-sem-fumo/
├── index.html
├── service-worker.js
├── manifest.json
└── /icons/
    ├── icon-192x192.png
    └── icon-512x512.png

Adicione os códigos fornecidos aos respetivos ficheiros (index.html, service-worker.js, manifest.json).

Coloque os ícones da aplicação na pasta /icons.

Passo 2: Subir para o GitHub e Ativar o Pages
Crie um novo repositório no GitHub e faça o upload dos seus ficheiros.

No repositório, vá a Settings > Pages.

Na secção "Branch", selecione o ramo main e clique em Save.

O GitHub irá gerar um link para a sua aplicação (ex: https://seunome.github.io/jornada-sem-fumo/).

Passo 3: Testar e Instalar
Aceda ao link gerado no seu telemóvel ou computador.

Um botão para instalar a aplicação deverá aparecer no ecrã ou na barra de endereço do navegador.

Clique para instalar e a "Jornada Sem Fumo" será adicionada ao seu dispositivo!

📄 Ficheiro manifest.json
Crie este ficheiro na pasta principal do projeto. Ele é essencial para as funcionalidades de PWA.

{
  "name": "Jornada Sem Fumo",
  "short_name": "Sem Fumo",
  "description": "Uma aplicação para o ajudar a parar de fumar, acompanhando o seu progresso e mantendo a motivação.",
  "start_url": ".",
  "display": "standalone",
  "background_color": "#d7f0d8",
  "theme_color": "#256e49",
  "icons": [
    {
      "src": "icons/icon-192x192.png",
      "sizes": "192x192",
      "type": "image/png"
    },
    {
      "src": "icons/icon-512x512.png",
      "sizes": "512x512",
      "type": "image/png"
    }
  ]
}

🛠️ Tecnologias Utilizadas
HTML5

CSS3 (com Variáveis CSS para fácil customização)

JavaScript (ES6+) (sem frameworks, puro e leve)
