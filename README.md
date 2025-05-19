# processamento-de-imagem


Descrição do Projeto

Este projeto utiliza um modelo de aprendizado de máquina treinado com o Teachable Machine do Google para reconhecer imagens em tempo real a partir da webcam do computador. O modelo pode ser treinado para reconhecer diferentes categorias, como gestos, objetos ou sinais visuais. Suas aplicações incluem:

Reconhecimento de gestos para controle sem toque

Identificação de objetos para automação

Projetos educacionais de aprendizado de máquina

Prototipagem de sistemas inteligentes interativos


Instruções de Instalação

Pré-requisitos:

Python 3 instalado

Instalar as seguintes bibliotecas (via terminal ou prompt de comando):


pip install tensorflow keras opencv-python numpy

Arquivos Necessários:

1. keras_Model.h5 – o modelo treinado exportado do Teachable Machine.


2. labels.txt – arquivo contendo os nomes das classes, também exportado do Teachable Machine.



Como obter os arquivos:

Acesse o Teachable Machine.

Treine seu modelo de imagem.

Clique em “Export Model” > “TensorFlow” > “Download my model”.

Extraia os arquivos .zip baixados e copie keras_Model.h5 e labels.txt para a mesma pasta do script Python.

Instruções de Uso

1. Conecte sua webcam ao computador.


2. Execute o script main.py (ou outro nome de arquivo que contenha o código).


3. O programa abrirá uma janela com a imagem da webcam e exibirá a classe prevista e a confiança da predição no terminal.


4. Para parar o programa, pressione a tecla ESC.

Créditos

Desenvolvido por [Luiz Cauã OLIVEIRA,Ana Paula BELÉM,Ida RAMOS,Gabrielly PINHEIRO,Cleyson VIANA].

Projeto realizado no Laboratório de Sistemas de Informação da UFOPA.

Baseado em modelo treinado com o Teachable Machine – Google.

Bibliotecas utilizadas: TensorFlow, Keras, OpenCV, NumPy.
