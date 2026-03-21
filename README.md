Creative Bible Apps - Explorador da Digital Bible Platform

O Creative Bible Apps é uma aplicação web de página única (SPA) concebida para explorar de forma visual e intuitiva os recursos da API da Digital Bible Platform (Bible Brain v4).

Esta ferramenta permite a programadores, investigadores e curiosos navegar através de milhares de idiomas, traduções da Bíblia, estruturas de livros e até ler ou ouvir capítulos específicos, tudo isto através de uma interface limpa e moderna.

✨ Funcionalidades Principais

Modo de Demonstração Integrado: O projeto inclui um modo mock (dados simulados) ativado por predefinição. Se não tiver uma chave de API, a aplicação irá funcionar e demonstrar o fluxo de utilização com dados de exemplo.

Visualização Inteligente (Smart View): A aplicação deteta automaticamente o tipo de dados devolvido pela API (lista de idiomas, metadados de uma tradução, texto de um capítulo, áudio, etc.) e renderiza uma interface gráfica amigável e interativa.

Explorador JSON: Para além da visualização rica, os utilizadores podem alternar para a aba "Resposta JSON" para inspecionar os dados em bruto recebidos da API, ideal para programadores.

Navegação Heurística: Clique num idioma para ver as suas Bíblias, clique numa Bíblia para ver os seus livros, e clique num livro para começar a ler ou ouvir. A aplicação constrói as rotas automaticamente.

Exemplos Prontos a Usar: Um menu lateral com presets de rotas comuns para facilitar os primeiros passos.

Histórico de Requisições: Regista as últimas rotas acedidas na sessão para facilitar a navegação.

🛠️ Tecnologias Utilizadas

Este projeto foi construído para ser o mais simples e portátil possível, não requerendo ferramentas de compilação complexas para ser executado:

HTML5 & CSS3: Estrutura base da aplicação.

React 18: Interface de utilizador e gestão de estado (carregado via CDN).

Babel (Standalone): Compilação de código JSX diretamente no navegador.

Tailwind CSS: Estilização utilitária e design responsivo (carregado via script).

🚀 Como Executar o Projeto

Como a aplicação é totalmente baseada no cliente e utiliza CDNs para as dependências, a execução é extremamente simples:

Transfira o ficheiro index.html.

Dê um duplo clique no ficheiro para o abrir em qualquer navegador web moderno (Chrome, Firefox, Safari, Edge).

A aplicação irá iniciar imediatamente no Modo de Demonstração.

🔑 Configurar a API Key (Modo Real)

Para aceder ao catálogo completo e real da Digital Bible Platform, precisará de uma chave de API oficial.

Registe-se e solicite a sua chave em: Faith Comes By Hearing - API Key Request.

Abra o ficheiro index.html num editor de texto ou de código.

Procure a seguinte linha na função principal App (dentro da tag <script type="text/babel">):

const publicApiKey = 'SUA_CHAVE_API_AQUI'; 


Substitua 'SUA_CHAVE_API_AQUI' pela sua chave real (entre aspas).

Guarde o ficheiro e recarregue a página no navegador. O aviso laranja do Modo de Demonstração irá desaparecer e a aplicação passará a consultar os dados reais da internet.

🤝 Contribuições

Este é um projeto de exploração inicial. Sinta-se à vontade para fazer um fork, melhorar a interface, adicionar novos visualizadores de dados (como visualização de vídeos do Evangelho de Lucas) ou implementar traduções na interface.

Criado para a exploração de dados abertos e partilha de conhecimento.
