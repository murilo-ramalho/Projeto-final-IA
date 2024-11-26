# Projeto-final-IA

### Melhoria do chatbot apresentado em aula

Na aula 21 apresentada no dia 14/11/2024 foi apresentado um chatbot básico desenvolvido em  linguagem python. **A tarefa consiste em fazer melhorias nesse chatbot básico.** No dia a dia de um desenvolvedor é comum ter que melhorar códigos antigos desenvolvidos por outras pessoas, e esse trabalho une essa tarefa ao tema da disciplina. O código para esse chatbot básico pode ser encontrado nos materiais de aula. Pode-se utilizar outros pacotes python no projeto para fazer as melhorias.

### Principais problemas a serem resolvidos:

**1. Melhoria na lematização do chatbot:** Atualmente o chatbot tem problemas em distinguir palavras no masculino e no feminino. Por exemplo ele não reconhece a palavras "obrigado" mas reconhece "obrigada". 

**2. Fim dos erros de codificação de caracteres na resposta:** Palavras acentuadas são exibidas com caracteres incomuns atualmente. Aparentemente o erro vem do não uso do UTF-8 em todas as partes do projeto. Investiguem se é realmente isso e corrijam.

**3. A interface gráfica GUI não envia o texto ao pressionar Enter na caixa de texto.**

### Melhoria do dicionário de intents:
**1. Escolha um tema para que seu chatbot converse.** Pode-se simular um negócio (empresa) fictício ou algum outro assunto de seu interesse.

**2. Procure não repetir o mesmo tema utilizado por outro grupo** para evitar problemas de trabalhos iguais já que o código base é o mesmo.

### Outras melhorias necessárias:

- **Adição de um botão para limpar a conversa na interface gráfica.**

### Grupo  
O trabalho será desenvolvido em grupos de 2 até 4 alunos. Respeitem os tamanhos dos grupos.  

### Entrega do trabalho  
Cada integrante do grupo deverá entregar o **link do GitHub** contendo todo o código do projeto.
O **nome dos integrantes deve constar no readme** do projeto no GitHub.
O **readme também deverá ter uma explicação** sobre o tema que o chatbot conversa.
O **readme deverá conter um tutorial** mencionando a instalação dos pacotes e 
dependências necessárias do projeto.

### Avaliação
Será levado em consideração o quanto o chatbot básico foi **melhorado em 
relação ao original** e aos outros projetos da sala. A **qualidade da conversação** com o chatbot será outro item avaliado.

### FAQ  
Trabalhos iguais em grupos diferentes: Zero para ambos os grupos. 
Cuidado com o que vocês compartilham entre si.  
Usei uma IA para fazer os códigos pra mim, por isso ficou igual ao do outro grupo: 
Zero para ambos os grupos. Usem as IA (GPT e afins) com responsabilidade. 
Não sai copiando e colando qualquer coisa que eles respondem... Usem a cabeça...

---

## Chatbot de Lanchonete

Este projeto é um chatbot desenvolvido para responder perguntas e auxiliar clientes em uma lanchonete, oferecendo informações sobre o cardápio, preços, status de pedidos e muito mais. O chatbot utiliza técnicas de processamento de linguagem natural (PNL) para compreender as interações dos usuários e fornecer respostas apropriadas.

## Grupo
- Murilo Ramalho da Mata
- Camila Gomes da Silva Casa
- Yasmim Christhina Lopes

## Funcionalidades (ficticio)

O chatbot é capaz de:
- Responder perguntas sobre o cardápio da lanchonete.
- Fornecer informações sobre tipos de hambúrgueres, preços e outros itens.
- Confirmar pedidos realizados pelos usuários.
- Informar sobre o status do pedido (tempo estimado de entrega, etc).
- Oferecer respostas amigáveis para interações como agradecimentos e despedidas.

## Tecnologias Utilizadas

- **Python:** Linguagem de programação utilizada para desenvolvimento do backend.
- **TensorFlow e NLTK:** Bibliotecas utilizadas para treinamento e processamento de linguagem natural.
- **Tkinter:** Interface gráfica utilizada para a interação com o usuário.
- **JSON:** Formato de dados usado para armazenar os intents e respostas do chatbot.

## Instalação e utilização

### Requisitos

Antes de rodar o chatbot, certifique-se de que você possui o Python 3.9 instalado em seu sistema. Você também precisará instalar algumas bibliotecas Python.

1. **Clone o repositório do projeto:**

   ```bash
   git clone https://link-para-o-repositorio.git

2. **Instalar o [Python 3.9](https://www.python.org/downloads/release/python-390/)**

3. **instalar as dependencias**
    ```bash
    python -m pip install --upgrade pip
    pip install tensorflow numpy nltk