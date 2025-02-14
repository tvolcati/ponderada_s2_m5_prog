# Documento de Levantamento de Requisitos - Jogo da Forca Interativo

---

## Requisitos Funcionais (RFs)

<div align="center">

**Quadro 1 - Requisitos Funcionais**

| ID     | Descrição                                                                 | Pré-condição                  | Procedimento                              | Resultado Esperado                          | Pós-condição                     |
|--------|---------------------------------------------------------------------------|-------------------------------|-------------------------------------------|---------------------------------------------|----------------------------------|
| RF01   | O sistema deve ter Modo cooperativo com múltiplos jogadores                                  | Sala multiplayer criada       | Jogadores inserem letras simultaneamente  | Progresso compartilhado em tempo real       | Colaboração ativa entre jogadores|
| RF02   | O sistema deve ter Temas visuais customizáveis (claro/escuro/retrô)                          | Acesso às configurações       | Selecionar tema no menu                   | Interface atualiza esquema de cores         | Experiência visual personalizada |
| RF03   | O sistema deve ter Banco de palavras categorizadas (Ex: Ciência, Cinema)                     | Jogo iniciado                 | Escolher categoria pré-jogo               | Sistema seleciona palavra temática          | Partidas temáticas               |
| RF04   | O sistema deve ter Modo contra-relógio com bônus de tempo                                    | Partida individual iniciada   | Completar palavra antes do cronômetro     | Pontuação extra calculada                   | Ranking atualizado               |
| RF05   | O sistema deve ter Criação de listas de palavras personalizadas                              | Perfil do usuário acessado    | Upload de arquivo .txt ou digitação       | Validação e armazenamento de lista          | Partidas com palavras customizadas |
| RF06   | O sistema deve ter Sistema de dias pagas com moedas virtuais                                 | Saldo suficiente disponível   | Acionar opção de dica durante o jogo      | Letra aleatória revelada                    | Dedução do saldo                 |
| RF07   | O sistema deve ter Modo duelo 1v1 com mesma palavra                                          | Dois jogadores conectados     | Inserção alternada de letras              | Comparação de progresso em tempo real       | Definição de vencedor            |
| RF08   |O sistema deve ter  Narração automática para acessibilidade                                   | Modo acessibilidade ativado   | Iniciar partida                           | Descrição auditiva dos elementos visuais    | Jogabilidade não visual          |

*Fonte: Autor do documento (2024)*
</div>

---

## Requisitos Não Funcionais (RNFs)

<div align="center">

**Quadro 2 - Requisitos Não Funcionais**

| ID     | Descrição                                                                 | Pré-condição                  | Procedimento                              | Resultado Esperado                          | Pós-condição                     |
|--------|---------------------------------------------------------------------------|-------------------------------|-------------------------------------------|---------------------------------------------|----------------------------------|
| RNF01  | Reconhecimento de voz para input                                          | Microfone habilitado          | Ditado de letras                          | Conversão precisa (95%+)                    | Input processado como texto      |
| RNF02  | Sincronização cross-platform                                              | Conta logada em >1 dispositivo| Alteração em um dispositivo               | Atualização instantânea (<1s)               | Dados unificados                 |
| RNF03  | Geração procedural de palavras                                            | Banco com +10k palavras       | Início de nova partida                    | Balanceamento estatístico de dificuldade    | Experiência justa                |
| RNF04  | Funcionalidade offline                                                    | Sem conexão de internet       | Acesso ao app                             | Disponibilidade de 3 últimos jogos locais   | Continuidade de progresso        |
| RNF05  | Performance gráfica a 60fps                                               | Hardware compatível           | Execução de animações                     | Frame rate constante                        | Experiência fluida               |
| RNF06  | Criptografia AES-256 para dados                                           | Partida ativa                 | Tentativa de acesso ao código-fonte       | Dados ilegíveis                             | Segurança reforçada              |
| RNF07  | Notificações push para turnos                                             | Permissões concedidas         | Vez do jogador em multiplayer             | Alerta imediato em qualquer tela            | Retorno rápido ao jogo           |

*Fonte: Autor do documento (2024)*
</div>

---
