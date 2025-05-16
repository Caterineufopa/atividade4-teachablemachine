
# Proc-Img-e-Visao-Comp

## Descrição do Projeto:
Este projeto usa um modelo treinado no [Teachable Machine](https://teachablemachine.withgoogle.com/) para classificar imagens em tempo real capturadas pela webcam.  
Ele utiliza Python, OpenCV e Keras para realizar a previsão com base nas imagens.  
Aplicações incluem identificação de objetos, lixo reciclável, gestos, entre outros.

## Instruções de Instalação:
1. **Instale o Python 3.8 ou superior**
2. **Instale as bibliotecas necessárias** com o seguinte comando:
   ```bash
   pip install tensorflow opencv-python numpy
   ```
3. **Treine e exporte seu modelo no Teachable Machine**:
   - Vá para [Teachable Machine](https://teachablemachine.withgoogle.com/)
   - Treine um modelo de imagem
   - Clique em "Export Model" → Escolha "TensorFlow" → Selecione "Keras"
   - Baixe os arquivos: `keras_model.h5` e `labels.txt`
   - Coloque esses dois arquivos na mesma pasta do código Python

## Instruções de Uso:
1. Execute o script no terminal:
   ```bash
   python seu_script.py
   ```
2. A webcam será iniciada e o modelo fará previsões em tempo real
3. Pressione a tecla `ESC` para encerrar o programa
4. Se a câmera não funcionar, troque o índice:
   ```python
   camera = cv2.VideoCapture(0)
   ```
   Tente valores como `0`, `1`, `2` dependendo da câmera disponível

## Créditos:
- Projeto desenvolvido para a disciplina **Processamento de Imagens**
- Curso de **Sistemas de Informação** – UFOPA
- Ferramentas utilizadas: Python, OpenCV, TensorFlow/Keras, Teachable Machine





