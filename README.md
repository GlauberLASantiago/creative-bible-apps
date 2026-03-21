Creative Bible Apps - Bible Brain v4 Showcase

O Creative Bible Apps é uma suíte interativa e multimédia concebida para demonstrar o poder e a flexibilidade da Digital Bible Platform (Bible Brain v4).

Mais do que uma simples API de texto, a DBP4 introduz um ecossistema completo de conteúdos ricos, e esta aplicação serve como um laboratório visual para programadores, designers e ministérios explorarem estas novas capacidades de forma criativa.

🚀 O que há de novo na DBP4? (Recursos Explorados)

A versão 4 da plataforma substitui o antigo DAMID pelo FilesetId como identificador principal, expandindo drasticamente os tipos e formatos de conteúdo disponíveis. O Creative Bible Apps demonstra estas funcionalidades:

Textos Bíblicos Formatados (HTML/CSS): Apresentação de textos que vão além do "plain-text", mantendo a formatação original, parágrafos, poesia e estilos.

Áudio Sincronizado (Audio Timing): Funcionalidade estilo karaoke! A DBP4 fornece o tempo exato de início de cada versículo. A nossa app demonstra como o texto pode ser realçado em tempo real enquanto o áudio é reproduzido.

Gospel Films (Vídeo): Integração de gravações de áudio (incluindo Traduções Bíblicas Orais - OBT) com filmes evangélicos, criando representações visuais com precisão palavra por palavra.

Streaming Adaptativo e Baixo Bitrate: Demonstração de como a API serve conteúdos em HLS, Opus e AAC, otimizando a entrega para regiões com baixa conectividade, superando a antiga limitação de mp3 a 64kbps.

✨ Funcionalidades da Aplicação

Modo Showcase Integrado: O projeto funciona com dados simulados (mock data) altamente interativos para ilustrar a experiência do utilizador final, sem necessitar de chave de API imediata.

Leitor Imersivo: Uma interface que combina as chamadas de texto formatado com os dados de Audio Timing, oferecendo uma experiência de leitura e audição em simultâneo.

Modo Cinema: Um ambiente escuro e focado para a visualização dos Gospel Films sincronizados com os dados da Bible Brain.

Painel de Formatos: Um explorador que evidencia as opções de bitrate e formatos de streaming adaptativo.

🛠️ Tecnologias Utilizadas

Este projeto foi construído como uma Single Page Application moderna, focada em renderização de multimédia:

HTML5 & CSS3: Estrutura base da aplicação com suporte a tags de áudio e vídeo nativas.

React 18: Interface de utilizador modular e gestão de estado complexo (sincronização de áudio/texto) via CDN.

Tailwind CSS: Estilização avançada, design responsivo e "Dark Mode" dinâmico.

🚀 Como Executar o Projeto

Transfira o ficheiro index.html.

Dê um duplo clique no ficheiro para o abrir em qualquer navegador web moderno.

A aplicação irá iniciar no Modo de Demonstração Interativo, permitindo navegar pelas diferentes capacidades (Filmes, Áudio Sincronizado, etc.).

📖 Conceitos Essenciais da DBP4

Para criar as suas próprias apps criativas, familiarize-se com:

FilesetId: O coração da DBP4, agrupando conteúdos do mesmo tipo e formato.

Tipos de Fileset: Textos (text_plain, text_format), Áudio (audio, audio_drama), Vídeo (video_stream).

Endpoints de Timing: /timestamps para sincronização perfeita entre os arrays de texto e os ficheiros multimédia.

Criado para a exploração criativa da Palavra através da tecnologia.
