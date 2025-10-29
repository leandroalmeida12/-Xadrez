 Movimentação de Peças de Xadrez

📋 Descrição do Projeto
Sistema desenvolvido em linguagem C que simula o movimento de peças específicas de xadrez utilizando estruturas de repetição (for, while, do-while), loops aninados e recursividade. O projeto é dividido em três módulos de complexidade crescente.

🎯 Cenário
A MateCheck , desenvolvedora de jogos, criou um jogo eletrônico inovador para o ensino de programação e incentivo ao xadrez. No jogo, o jogador não move as peças manualmente, mas cria procedimentos e rotinas em código para executar as ações, respeitando as regras do xadrez e a sintaxe da linguagem C.

📁 Estrutura do Projeto
graduacao-estacio-xadrez/
├── src/
│   ├── modulo_novato/
│   ├── modulo_aventureiro/
│   └── modulo_mestre/
├── include/
├── tests/
├── docs/
├── Makefile
├── README.md
└── .gitignore
⚙️ Requisitos Funcionais
🏰 RF001 - Movimentação Linear da Torre
Descrição : Implementar movimento linear (horizontal e vertical) da Torre
Critério : Utilização de estruturas de reprodução para, while ou do-while
Entrada : Posição inicial e final da Torre
Saída : Validação do movimento e caminho percorrido
⛪ RF002 - Movimentação Diagonal do Bispo
Descrição : Implementar movimento diagonal do Bispo
Critério : Utilização de estruturas de reprodução para, while ou do-while
Entrada : Posição inicial e final do Bispo
Saída : Validação do movimento e caminho percorrido
👑 RF003 - Movimentação Combinada da Rainha
Descrição : Implementar movimento combinado (linear e diagonal) da Rainha
Critério : Utilização de estruturas de reprodução para, while ou do-while
Entrada : Posição inicial e final da Rainha
Saída : Validação do movimento e caminho percorrido
🐎 RF004 - Movimentação em "L" do Cavalo
Descrição : Implementar movimento em "L" do Cavalo
Critério : Utilização de loops aninados para simular o movimento complexo
Entrada : Posição inicial e final do Cavalo
Saída : Validação do movimento em "L"
🔄 RF005 - Otimização com Recursividade
Descrição : Implementar recursividade para otimizar movimentos das peças
Critério : Aplicar recursividade e loops complexos com múltiplas condições
Entrada : Posição inicial, final e peça selecionada
Saída : Caminho otimizado e validação do movimento
✅ RF006 - Validação do Tabuleiro
Descrição : Validar se as posições estão dentro dos limites do tabuleiro (8x8)
Critério : Verificação de coordenadas entre A1-H8
Entrada : Coordenadas da posição
Saída : Confirmação de posição válida
💻 RF007 - Interface de Linha de Comando
Descrição : fornecer interface simples para entrada de comandos
Critério : Menu interativo para seleção de peças e movimentos
Entrada : Comandos do usuário
Saída : Feedback das operações
🔧 Requisitos Não Funcionais
💻 RNF001 - Linguagem de Programação
Descrição : O sistema deve ser desenvolvido exclusivamente em linguagem C
Critério : Código compatível com padrão C99 ou superior
🔄 RNF002 - Estruturas de Repetição Obrigatórias
Descrição : Uso obrigatório de estruturas para, while e do-while
Critério : Cada tipo de estrutura deve ser utilizado pelo menos uma vez
⚡ RNF003 - Desempenho
Descrição : O sistema deve responder em tempo real às operações
Critério : Tempo de resposta inferior a 1 segundo para qualquer movimento
🌐 RNF004 - Portabilidade
Descrição : O código deve ser compilável em diferentes sistemas operacionais
Critério : Compatibilidade com GCC em Linux, macOS e Windows
🧩 RNF005 - Modularidade
Descrição : O código deve ser organizado em módulos bem definidos
Critério : Separação clara entre lógica de negócio, interface e validações
📚 RNF006 - Documentação
Descrição : Todo o código deve ser detalhado documentado
Critério : Comentários explicativos em funções complexas e cabeçalhos
⚠️RNF007 - Tratamento de gado
Descrição : O sistema deve tratar entradas inválidas
Critério : Mensagens de erro claro e recuperação de estados inválidos
💾 RNF008 - Uso de Memória
Descrição : O sistema deve usar memória de forma eficiente
Critério : Liberação adequada de memória alocada dinamicamente
 Módulos do Projeto
 Módulo Novato
Implementação de movimentos básicos (Torre, Bispo, Rainha)
Uso de estruturas de reprodução simples
Validação básica de movimentos
 Módulo Aventureiro
Implementação do movimento do Cavalo
Uso de loops aninhados
Validação de movimentos complexos
Módulo Mestre
Otimização com recursividade
Loops complexos com múltiplas condições
Refinamento e otimização de código
 Como Compilar e Executar
 Pré-requisitos
Compilador GCC instalado
Sistema operacional: Linux, macOS ou Windows
Make (opcional, para usar Makefile)
 Compilação
# Compilação manual
gcc -o xadrez src/*.c -I include/

# Usando Makefile
make all
▶Execução
./xadrez
Estrutura de Arquivos
src/: Código fonte do projeto
include/: Arquivos de cabeçalho (.h)
tests/: Testes unitários
docs/Documentação adicional
Makefile: Arquivo de automação de construção
