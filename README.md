# 📚 Caderno Temático no NotebookLM: Da Arquitetura de Computadores à Nuvem Azure

> Desafio de Projeto desenvolvido para a plataforma [DIO](https://www.dio.me/).

---

## 🎯 Contexto e Objetivos

* **Tema Selecionado:** Arquitetura de Computadores, Organização de Hardware, Pensamento Computacional e Computação em Nuvem (Microsoft Azure / AZ-900).
* **Objetivo de Estudo:** Compreender a evolução do processamento de dados — desde a estrutura de chips, memórias, arquiteturas RISC/CISC e microcontroladores até a infraestrutura em nuvem moderna no Microsoft Azure. O material serve de apoio tanto para disciplinas de arquitetura e montagem de computadores quanto para a preparação para a certificação **AZ-900**.

---

## 📂 Curadoria de Fontes

Para alimentar o NotebookLM, foram selecionadas **16 fontes técnicas, acadêmicas e audiovisuais**:

1. **#SprintAZ900: Conceitos de Computação em Nuvem com Azure** (Série de vídeos)
2. **A PEÇA que ENCOLHEU o COMPUTADOR!** (#SagaDosComputadores Ep. 5)
3. **Colocamos um CHIP no MICROSCÓPIO** (#SagaDosComputadores Ep. 6)
4. **Por que CELULAR tem MEMÓRIA de 16, 32, 64, 128?** (Vídeo explicativo)
5. **Aprenda Arduino** (Fatec Jundiaí)
6. **RASPBERRY PI** (Editora do IFES)
7. **Arquitetura de Computadores - Livro/Gabarito** (Uniasselvi)
8. **Arquitetura de Computadores** (Grupo GEN)
9. **Ementa da Disciplina: Arquitetura e Montagem de Computadores** (IFCE)
10. **Ementa da Disciplina: Arquitetura e Organização de Computadores** (IFSul)
11. **Comparação entre as Arquiteturas RISC e CISC** (IFBA)
12. **Operador de Computador - Conceitos de Memória** (IFRN)
13. **Máquinas Hipotéticas da UFRGS** (Wikipédia)

---

## 🧪 Engenharia de Prompts e Cicatrizes (Troubleshooting)

### Prompts Testados & Resultados

* **Prompt 1 (Pensamento Computacional e Lógica):**
  * `Prompt:` *"Explique os quatro pilares do pensamento computacional e sua aplicação com exemplos do cotidiano e tecnologia."*
  * `Resultado:` A IA detalhou Decomposição, Reconhecimento de Padrões, Abstração e Algoritmos, ligando-os ao funcionamento de sistemas e aplicativos.

* **Prompt 2 (Evolução de Hardware e Arquitetura):**
  * `Prompt:` *"Com base nas fontes acadêmicas e vídeos, qual é a diferença entre as arquiteturas RISC e CISC e como o avanço dos chips viabilizou computadores menores e microcontroladores?"*
  * `Resultado:` A resposta explicou a redução no conjunto de instruções (RISC) vs. instruções complexas (CISC), destacando o papel do Arduino, Raspberry Pi e chips integrados.

* **Prompt 3 (Computação em Nuvem e Azure AZ-900):**
  * `Prompt:` *"Sintetize os conceitos da #SprintAZ900: vantagens da nuvem, CapEx vs OpEx, e modelos IaaS, PaaS e SaaS."*
  * `Resultado:` A IA construiu um resumo focado na certificação, destacando elasticidade, despesas operacionais e divisão de responsabilidade.

### 🛠️ "Cicatrizes" e Aprendizados (Troubleshooting)

* **Dificuldade Encontrada:** O acervo de 16 fontes misturava conteúdos de hardware físico baixo nível (chips, memórias, RISC/CISC) com alto nível (nuvem Azure). As primeiras buscas retornavam respostas divididas e desarticuladas.
* **Como foi resolvido:** Ajustei a engenharia de prompts criando uma abordagem de "linha do tempo", pedindo para a IA explicar a transição histórica: *como a evolução dos chips físicos e memórias permitiu a criação de servidores potentes e, posteriormente, a virtualização e a nuvem no Azure*.

---

## 📘 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado do Assunto

* **Pilares do Pensamento Computacional:** Decomposição, Reconhecimento de Padrões, Abstração e Algoritmos formam a base para resolver problemas via software.
* **Arquitetura de Hardware & Processadores:**
  * Diferença entre **RISC** (conjunto reduzido de instruções, mais eficiente) e **CISC** (instruções complexas).
  * Organização da memória (base binária / potências de 2: 16GB, 32GB, 64GB, 128GB).
  * Uso de placas como **Arduino** e **Raspberry Pi** para prototipagem e sistemas embarcados.
* **Nuvem Microsoft Azure (AZ-900):**
  * **CapEx vs. OpEx:** Redução de investimentos pesados em infraestrutura física (CapEx) para pagamento sob demanda por uso (OpEx).
  * **Modelos de Serviço:** IaaS (infraestrutura pura), PaaS (plataformas de dev), SaaS (softwares prontos).

### 2. Glossário de Principais Conceitos

* **RISC / CISC:** Tipos de arquitetura de conjunto de instruções de processadores.
* **Arduino / Raspberry Pi:** Microcontrolador e microcomputador de placa única, respetivamente, usados no estudo de arquitetura e embarcados.
* **CapEx (Capital Expenditure):** Gastos de capital inicial em hardware e infraestrutura física.
* **OpEx (Operational Expenditure):** Gastos operacionais sob demanda, característicos do modelo de cobrança em nuvem.
* **IaaS / PaaS / SaaS:** Três grandes pilares de oferta de serviços de computação em nuvem.

### 3. Prompts Reutilizáveis para Revisão

* 🔹 *"`Compare a arquitetura de um microcontrolador (Arduino) com a de um microcomputador (Raspberry Pi) usando tópicos simples.`"*
* 🔹 *"`Crie 5 perguntas de múltipla escolha focadas na prova AZ-900 cobrindo IaaS, PaaS, SaaS e CapEx/OpEx.`"*
* 🔹 *"`Explique por que as capacidades de memória em celulares e computadores progridem em potências de 2 (16, 32, 64, 128).`"*

---

## 💻 Tecnologias Utilizadas

* **NotebookLM** (Google) - Curadoria das 16 fontes, geração de resumos, podcasts (Deep Dive), flashcards e quizes.
* **GitHub** - Documentação do projeto e construção do portfólio.
