# yolov4_detection
Yolov4 para detecção de armas, lâminas de barbear e shurikens

Experimento realizado utilizando o Google Colaboraty;

Siga os passos abaixo para reproduzir os resultados:

1 - Monte unidade do Google drive , vincule a pasta e navegue até a pasta yolov4
2 - Clone o repositório Darknet git
3 - Crie ou carregue os arquivos necessários para o treinamento (por exemplo, “ obj.zip ”, “ yolov4-custom.cfg ”, “ obj.data ”, “ obj.names ” e “ process.py ”) para sua unidade
4 - Faça alterações no Makefile para habilitar OPENCV e GPU
5 - Execute o comando make para criar darknet
6 - baixe o dataset ( https://drive.google.com/file/d/1X1pKbYDmi7o7hPWW97xiJB9mKgWiW5m4/view?usp=sharing )
7 - Copie os arquivos “ armas.zip ”, “ yolov4-custom.cfg ”, “ obj.data ”, “ obj.names ” e “ process.py ” da pasta yolov4 para o diretório darknet ( DISPONIVEL NA PASTA DO GIT )
8 - Execute o script python process.py para criar os arquivos train.txt e test.txt
9 - Baixe os pesos YOLOv4 pré-treinados
10 - Treine o detector
11 - Teste o detector

