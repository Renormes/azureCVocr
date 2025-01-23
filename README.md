# azureCVocr
train for Computer Vision OCR

# Projeto de Reconhecimento de Texto

## Introdução
Este projeto tem como objetivo realizar o reconhecimento de texto em imagens de documentos, utilizando o Azure Vision Studio. A seguir, descrevo o passo a passo desde o login na Azure até a criação dos diretórios `inputs` e `outputs` no GitHub.

## Passo a Passo

### 1. Login na Azure
1. Acesse o Azure Portal.
2. Faça login com sua conta da Microsoft.

### 2. Configuração do Vision Studio
1. No portal do Azure, procure por **Vision Studio** na barra de pesquisa.
2. Selecione **Vision Studio** e clique em **Create**.
3. Siga as instruções para configurar seu recurso de Vision Studio.

### 3. Upload das Imagens
1. No Vision Studio, navegue até a seção de **Image Analysis - Extract Text From Images**.
2. Faça o upload das seguintes imagens:
   - `image1.jpg` e `image2.jpg` (documentos de identificação)
   - `image5.jpg` e `image6.jpg` (comprovantes de residência)

![printPlataform](https://github.com/user-attachments/assets/ea8c6aaf-afe5-45fa-8506-e6f48bb5e104)

### 4. Reconhecimento de Texto
1. Acesse a seção de **Read Text** no Vision Studio.
2. Selecione as imagens `image1.jpg`, `image2.jpg`, `image5.jpg` e `image6.jpg`.
3. Execute o reconhecimento de texto e salve os resultados.

### 5. Criação dos Diretórios de Input e Output no GitHub
1. No repositório de escolha, criar as pastas `inputs` e `outputs`.
2. Faça o upload das imagens originais na pasta `inputs`.
3. Salve os resultados de reconhecimento de texto na pasta `outputs`.


## Insights
- A qualidade das imagens influencia diretamente na precisão do reconhecimento de texto.
- Organizar os arquivos em pastas específicas facilita a gestão e análise dos dados.

## Possibilidades
- Explorar diferentes algoritmos de OCR para melhorar a precisão do reconhecimento de texto.
- Aplicar técnicas de pré-processamento de imagem para melhorar a qualidade das imagens antes do reconhecimento.
- Utilizar o OCR para aplicações de segurança, autenticação e usabilidade de clientes.
