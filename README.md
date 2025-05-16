# Proc-Img-e-Visao-Comp

## Descrição do Projeto:
Este projeto usa um modelo treinado no [Teachable Machine](https://teachablemachine.withgoogle.com/) para classificar imagens em tempo real capturadas pela webcam.  
Ele utiliza Anaconda, Jupyter Notebook, VisualCode, OpenCV e Keras para realizar a previsão com base nas imagens.  
Aplicações incluem identificação de objetos, lixo reciclável, gestos, entre outros.

## Instruções de Instalação:
3. Treine e exporte seu modelo no Teachable Machine:
 - Vá para Teachable Machine: <https://teachablemachine.withgoogle.com/>;
 - Treine um modelo de imagem;
 - Clique em "Export Model" → Escolha "TensorFlow" → Selecione "Keras";
 - Baixe os arquivos: keras_model.h5 e labels.txt;
 - Coloque esses dois arquivos na mesma pasta do código Pynb;
 - depois crie uma pasta onde todos os arquivos estejam juntos.

## Instruções de Uso:

- Clicar em Run All, e selecionar o ambiente gerado em environments;
- Usar a câmera iriun;
- A webcam será iniciada e o modelo fará previsões em tempo real;
- Se a câmera não funcionar, troque o índice:
   1. camera = cv2.VideoCapture(0);
   2. Tente valores como 0, 1, 2, dependendo da câmera disponível.

## Créditos:
- Instituição: Universidade Federal do Oeste do Pará (UFOPA)
- Curso: Sistemas de Informação
- Disciplina: Processamento de Imagens
- Docente: Danilo Azevedo Figueiredo: <http://lattes.cnpq.br/9122429239132988>
- Ferramentas Utilizadas: Teachable Machine. TensorFlow. OpenCV. Anaconda e VScode. 


