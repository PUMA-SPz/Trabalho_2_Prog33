# Trabalho_2_Prog33
Trabalho_2_Prog33
LEIA-ME (README)

1. OBJETIVO GERAL
Este projeto tem como finalidade o desenvolvimento de um programa em linguagem C para processamento de localizações e rotas, utilizando estruturas ligadas e memória dinâmica. O trabalho inclui a leitura de localidades a partir de um ficheiro (localidades.txt) e a leitura de rotas de outro ficheiro (rotas.txt), de modo a executar comandos específicos passados pela linha de comando e gerar resultados em ficheiros de saída.

2. ESTRUTURA GLOBAL DO PROJETO
- Diretório "src": Contém o código-fonte C do projeto, incluindo:
  - main.c: Função principal responsável pelo processamento dos argumentos de linha de comando e pela execução das funcionalidades.
  - localidades.c e localidades.h: Módulo responsável pela gestão de localidades (leitura, inserção, remoção, armazenamento e ordenação alfabética).
  - rotas.c e rotas.h: Módulo responsável pela leitura do ficheiro rotas, armazenamento e cálculo de distâncias.
- Diretório "data": Pode conter os ficheiros de dados, como localidades.txt e rotas.txt.
- Diretório "docs": Reservado para documentações adicionais.
- Diretório "bin": Opcional para armazenar eventuais ficheiros binários gerados.

3. DIVISÃO DO TRABALHO
Para permitir uma distribuição equilibrada, sugere-se a seguinte divisão de tarefas entre duas pessoas.

Membro 1:
- Leitura e validação das localidades a partir de localidades.txt, incluindo:
  - Criação de funções para ler, validar e armazenar os dados numa estrutura dinâmica.
  - Ordenação das localidades alfabeticamente.
- Funcionalidade "-TL" (Teste de Leitura):
  - Processamento da leitura de localidades e escrita do relatório num ficheiro de saída, incluindo a quantidade de memória dinâmica utilizada.
- Funcionalidade "-ADI" (Adicionar Localidade):
  - Inserção de novas localidades na estrutura em memória, mantendo a ordenação e evitando duplicados.
- Testes e Documentação:
  - Elaboração de testes unitários para as funcionalidades de localidades.
  - Criação de secções de documentação relativas a estes módulos.

Membro 2:
- Funcionalidade "-REM" (Remover Localidade):
  - Implementação de rotinas para remoção de localidades da estrutura dinâmica, mantendo a ordenação.
- Funcionalidade "-ROTAS":
  - Leitura do ficheiro rotas.txt e armazenamento das rotas numa estrutura dinâmica.
  - Cálculo das distâncias usando a metodologia indicada (aproximação através de Dx e Dy).
  - Escrita do resultado das rotas num ficheiro de saída, por ordem crescente de distância total.
- Algoritmos de Ordenação de Rotas:
  - Ordenação das rotas, de forma crescente, pela distância calculada.
- Testes e Documentação:
  - Testes para garantir o correto funcionamento das rotas e da remoção de localidades.
  - Criação de secções de documentação específicas para estes módulos.

4. FLUXO DE TRABALHO E INTEGRAÇÃO
- Utilização de um sistema de controlo de versões para permitir revisões, solução de conflitos e histórico de alterações.
- Respeito pelas mesmas convenções de codificação e documentação em todas as partes do código.
- Integração e validação cruzada das partes desenvolvidas por cada membro antes da conclusão final.

5. OBSERVAÇÕES FINAIS
- Para o processamento correto, cada um dos ficheiros de dados (localidades.txt e rotas.txt) deve ser aberto e validado (por exemplo, verificar formatação e intervalos válidos de latitude e longitude).
- A apresentação e escrita dos dados em ficheiros de saída devem cumprir as especificações fornecidas no enunciado (por exemplo, respetivas linhas de resultados, mensagens de erro e ordenações pedidas).
- A entrega deve consistir num ficheiro zip contendo todos os ficheiros de código fonte, de acordo com as instruções fornecidas pela coordenação da disciplina.
