# Documento de Levantamento de Requisitos - Jogo da Forca Interativo

---

## Requisitos Funcionais (RFs)

<div align="center">

**Quadro 1 - Requisitos Funcionais**

| ID     | Descrição                                                                 | Pré-condição                  | Procedimento                              | Resultado Esperado                          | Pós-condição                     |
|--------|---------------------------------------------------------------------------|-------------------------------|-------------------------------------------|---------------------------------------------|----------------------------------|
| RF01   | O sistema deve ter modo cooperativo com múltiplos jogadores                                  | Sala multiplayer criada       | Jogadores inserem letras simultaneamente  | Progresso compartilhado em tempo real       | Colaboração ativa entre jogadores|
| RF02   | O sistema deve ter temas visuais customizáveis (claro/escuro/retrô)                          | Acesso às configurações       | Selecionar tema no menu                   | Interface atualiza esquema de cores         | Experiência visual personalizada |
| RF03   | O sistema deve ter banco de palavras categorizadas (Ex: Ciência, Cinema)                     | Jogo iniciado                 | Escolher categoria pré-jogo               | Sistema seleciona palavra temática          | Partidas temáticas               |
| RF04   | O sistema deve ter modo contra-relógio com bônus de tempo                                    | Partida individual iniciada   | Completar palavra antes do cronômetro     | Pontuação extra calculada                   | Ranking atualizado               |
| RF05   | O sistema deve ter criação de listas de palavras personalizadas                              | Perfil do usuário acessado    | Upload de arquivo .txt ou digitação       | Validação e armazenamento de lista          | Partidas com palavras customizadas |
| RF06   | O sistema deve ter sistema de dicas pagas com moedas virtuais                                 | Saldo suficiente disponível   | Acionar opção de dica durante o jogo      | Letra aleatória revelada                    | Dedução do saldo                 |
| RF07   | O sistema deve ter modo duelo 1v1 com mesma palavra                                          | Dois jogadores conectados     | Inserção alternada de letras              | Comparação de progresso em tempo real       | Definição de vencedor            |
| RF08   |O sistema deve ter  narração automática para acessibilidade                                   | Modo acessibilidade ativado   | Iniciar partida                           | Descrição auditiva dos elementos visuais    | Jogabilidade não visual          |

*Fonte: Autor do documento (2024)*
</div>

---

## Requisitos Não Funcionais (RNFs)

<div align="center">

**Quadro 2 - Requisitos Não Funcionais**

| ID     | Descrição                                                                 | Pré-condição                  | Procedimento                              | Resultado Esperado                          | Pós-condição                     |
|--------|---------------------------------------------------------------------------|-------------------------------|-------------------------------------------|---------------------------------------------|----------------------------------|
| RNF01  | O sistema deve ter reconhecimento de voz para input                                          | Microfone habilitado          | Ditado de letras                          | Conversão precisa (95%+)                    | Input processado como texto      |
| RNF02  | O sistema deve ter sincronização cross-platform                                              | Conta logada em >1 dispositivo| Alteração em um dispositivo               | Atualização instantânea (<1s)               | Dados unificados                 |
| RNF03  | O sistema deve ter geração procedural de palavras                                            | Banco com +10k palavras       | Início de nova partida                    | Balanceamento estatístico de dificuldade    | Experiência justa                |
| RNF04  | O sistema deve ter funcionalidade offline                                                    | Sem conexão de internet       | Acesso ao app                             | Disponibilidade de 3 últimos jogos locais   | Continuidade de progresso        |
| RNF05  | O sistema deve ter performance gráfica a 30fps                                               | Hardware compatível           | Execução de animações                     | Frame rate constante                        | Experiência fluida               |



*Fonte: Autor do documento (2024)*
</div>

---
