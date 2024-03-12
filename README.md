# Apollo

## O que é?
* Uma aplicação de Machine Learning feita com Gradio que permite que usuários a criarem Singles a partir de uma imagem que descreve a 'vibe' do Single e de uma descrição textual sobre o Single a ser criado.

## Como usar esse repositório para fazer melhorias localmente?
1. Baixar o arquivo ```CRIA_COMP_Apollo_Versao_Final.ipynb``` presente neste repositório.
2. Na sua conta do Google Drive, upar esse arquivo e abrir ele usando o Google Colab.
3. Configure o ambiente de execução para rodar com GPU (é mais rápido). Usar a opção ```T4```.
4. Configurar as APIs que você vai precisar usar no notebook do Google Colab. (Usamos duas APIs):
    * __API do Gemini:__ Basta seguir as informações dessa página: [Link para obtenção de chave para API e documentação da API do Gemini](https://ai.google.dev/)
    * __API da VertexAI da Google:__ Esse é um pouco mais complicadinho... Vamos lá.
         1. É preciso criar uma conta no Google Cloud para poder usar a API. É preciso colocar info de cartão de crédito (eles dizem que não haverá cobrança automática dps dos 90 dias de teste, mas eu não confiaria. Quando a cadeira acabar, recomendo tirar o método de pagamento). [Link para criar conta no Google Cloud Platform](https://accounts.google.com/v3/signin/)
         * Criar um projeto dentro do Google Cloud. Normalmente, quando vc cria a conta, o próprio site te guia na criação de um novo projeto. Vc vai precisar entrar no projeto e guardar o ID dele (use o recurso __Secrets__ do Google Colab pra guardar essa info).
         * No seu projeto, autorize a utilização da VertexAI API. Eu confesso que não me recordo como faz isso. Se vc rodar o notebook do Colab sem, ele vai dar um erro e te guiar como fazer isso. No processo, vai gerar uma outra API pra vc utilizar esse recurso.
5. Com as duas APIs, guarde elas usando a opção Secrets do Google Colab para guardar elas. Lembre-se de usar os mesmos nomes que tão no Google Colab Notebook.
6. Pode rodar e se divertir.
