# 🌐 Web Scraping e Tradução de Patch Notes do League of Legends por meio do Azure AI Service Open AI🎮

## 📒 Descrição
Este projeto tem como objetivo extrair e traduzir informações sobre atualizações do jogo League of Legends. Utilizando técnicas de web scraping, o projeto captura os patch notes diretamente do site oficial do jogo e traduz o conteúdo para o português, proporcionando acesso às novidades e mudanças no jogo para a comunidade de língua portuguesa.
Sendo, igualmente possível a tradução para qualquer outro idioma.

## 🧐 Processo de Criação
O projeto foi desenvolvido em um ambiente Python, utilizando as bibliotecas `requests` e `BeautifulSoup` para realizar o scraping do conteúdo da web, além da biblioteca `langchain` e `openai` para gerenciar a tradução por meio da API do Azure.

### Etapas:
1. **Extração de Dados**: Implementação de uma função para fazer scraping da página de patch notes, capturando o texto relevante.
2. **Limpeza de Dados**: Remoção de elementos desnecessários como scripts e estilos, além de limpar o texto extraído.
3. **Configuração do Serviço de Tradução**: Preparação do cliente para utilizar a API do Azure para tradução.
4. **Tradução do Conteúdo**: Implementação de uma função que envia o texto extraído para ser traduzido e recebe a resposta traduzida.
5. **Exibição dos Resultados**: Impressão do texto extraído e traduzido, formatado em Markdown.

## 🚀 Resultados
Os resultados do projeto incluem a extração e tradução bem-sucedida dos patch notes do League of Legends. O conteúdo traduzido é apresentado de forma clara e organizada, permitindo que jogadores que falam português acessem informações importantes sobre o jogo.

### Exemplos de Tradução
Através da função de tradução, o texto capturado da página web é enviado para a API do Azure, e a resposta traduzida é apresentada de forma a manter a clareza e a estrutura original.

### Benefícios da Ferramenta
Este projeto não só facilita a compreensão das atualizações do jogo, mas também demonstra como combinar web scraping e inteligência artificial para criar ferramentas úteis para comunidades específicas.

## 💭 Reflexão
Este projeto enfatiza a importância do acesso à informação e como a tecnologia pode ser utilizada para superar barreiras linguísticas. A combinação de técnicas de scraping e tradução proporciona uma maneira eficiente de disseminar informações relevantes para os jogadores.

## Outros pontos
Importante considerar que com o serviço de tradução é possível traduzir até 2M de caracteres Free, e acima disso o próximo 1M é ~R$54. Já o serviço OpenAi no Azure, é possível traduzir igualmente seus arquivos, com valor 10x menor ~R$5 a cada 1M tokens usando o GPT 4o-mini.
Então, utilização do Azure Ai Service OpenAI é uma saída muito válida para tradução.
