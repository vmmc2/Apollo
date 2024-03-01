# Apollo

## O que é?
* Uma aplicação de Machine Learning feita com Gradio que permite que usuários a criarem Singles a partir de uma imagem que descreve a 'vibe' do Single e de uma descrição textual sobre o Single a ser criado.

## Lista de Melhorias (Sugestões de Calegario)
- [X] Tempo de geração do Single muito longo. Já foi reduzido de 6-10 minutos para 1 minuto __Responsável: Victor Miguel.__
- [ ] As vezes a API da VertexAI da Google não retorna a imagem em certos casos (Erro 400). Testar geração de imagens com outras ferramentas, de preferência Chat-GPT4 com DALL-E 2 ou 3. Falar com Calegario para pegar uma chave de API (por Email ou Discord). Usar com parcimônia por causa do limite de créditos. __Responsável: .__
- [ ] Realizar experimentos de Prompt Engineering com __TODOS__ os prompts feitos. Verificar se é possível melhorar o resultado dos artefatos gerados (Imagem do Single, Single). __Responsável: .__
- [ ] Tentar mexer no prompt que gera o Single em si para verificar a possibilidade de gerar um Single com letras e voz. __Responsável: .__
- [ ] Mexer com a biblioteca 'ffmpeg' para gerar um 'card' de Single: Capa do Single, Single, Nome do Artista ou Banda, Nome do Single. __Responsável: .__

## Como usar esse repositório para fazer melhorias localmente?
1. Baixar o arquivo ```(Vivi Version) - Projeto Final Criatividade Computacional.ipynb``` presente neste repositório.
2. Na sua conta do Google Drive, upar esse arquivo e abrir ele usando o Google Colab.
3. Configure o ambiente de execução para rodar com GPU (é mais rápido). Usar a opção ````T4```.
4. Configurar as APIs que você vai precisar usar no notebook do Google Colab. (Usamos duas APIs):
    * __API do Gemini:__
    * __API da VertexAI da Google:__
