# Tv Web IPTV Player

Tv Web IPTV Player é uma solução de transmissão ao vivo de IPTV baseada em navegador que suporta diversos protocolos de streaming e métodos de operação, além de oferecer uma interface de usuário simples e intuitiva, permitindo que você aproveite facilmente a experiência de TV ao vivo.


## Funções principais

- **Suporte a vários protocolos**: Suporta HLS, MPEG-DASH, RTMP e outros protocolos de streaming convencionais
- **Modo multioperação**: Adapta-se perfeitamente à operação com mouse, tela sensível ao toque e controle remoto de TV
- **Gerenciamento de canais**: Suporta o gerenciamento de múltiplas playlists M3U
- **Agrupamento inteligente**: Organiza automaticamente os canais por categoria
- **Detecção de canais**: Detecção em tempo real da disponibilidade e latência dos canais
- **Modo tela cheia**: Suporta reprodução em tela cheia e controle em tela cheia
- **Informações do canal por IA**: Integra a IA Gemini para fornecer informações do canal
- **Multiplataforma**: Compatível com todos os navegadores e dispositivos modernos

## Fonte de IPTV

Este player usa a fonte ao vivo de alta qualidade de [kilvn/iptv](https://github.com/kilvn/iptv) por padrão. Você também pode importar playlists M3U personalizadas.

## Guia do Usuário

### 1. Importar playlist

1. Clique no botão "Importar arquivo M3U" na barra de menu superior

2. Selecione um arquivo M3U local ou cole um URL M3U

3. A playlist será analisada automaticamente e exibida na área da lista de canais à direita

### 2. Controle de reprodução

- Selecione um canal na lista de canais à direita para iniciar a reprodução
- Use os botões de controle na parte inferior do player:
- Canal anterior
- Reproduzir/Pausar
- Próximo canal
- Controle de volume
- Alternar para tela cheia
- Clique no botão "✨ Informações do Canal" para obter detalhes do canal gerados por IA

### 3. Modo de tela cheia

- Clique duas vezes na área do player para entrar no modo de tela cheia
- Use a barra de controle para alternar os canais no modo de tela cheia
- Pressione a tecla ESC ou clique no botão "Sair da Tela Cheia" para retornar ao modo normal

### 4. Teclas de atalho

| Tecla | Função |
|---------------|--------------------|
| Barra de espaço | Reproduzir/Pausar |
| Teclas de seta para a esquerda e para a direita | Trocar de canal |
| Tecla F | Trocar para tela cheia |
| Teclas de seta ↑↓ | Controle de volume |
| Tecla I | Obter informações do canal |

### 5. Obtenha informações do canal

1. Selecione qualquer canal
2. Clique no botão "✨ Informações do Canal" no item do canal
3. O sistema usará o Gemini AI para gerar uma descrição detalhada do canal

## Estrutura do projeto

```
/iptv-player-web/
├── index.html # Página inicial do player
├── style.css # Folha de estilo da página
├── script.js # Script da função principal
├── iptv.m3u # [Exemplo] Arquivo da lista de canais
├── donate.jpg # Imagem do código QR para doação
├── iptv_logo.png # Logotipo do player
└── README.md # Descrição do projeto
```


### 📦 **Hospedagem do código-fonte do projeto**
Tv Web IPTV adota uma estratégia de hospedagem de código aberto de plataforma dupla e mantém os dois repositórios de código a seguir para se adaptar às diferentes necessidades dos desenvolvedores:

### ⚙️ **Métodos de aquisição e colaboração de código**
1. **Clonagem direta**
Baixe o repositório para o computador local por meio do comando `git clone` na tabela acima para auxiliar na revisão de código subsequente e no desenvolvimento secundário.

2. **Dicas de busca em repositórios**
- Digite `Tv Web Player` na barra de busca do GitHub/Gitee para localizar o projeto diretamente

3. **Sugestões de desenvolvimento colaborativo**
Se você precisar contribuir com código, é recomendado:
- **Fork do repositório** → Modificação local → Enviar Pull Request
- Usar o módulo **Issues** para relatar problemas ou propor novos recursos

Obrigado pelo seu apoio! ❤️
