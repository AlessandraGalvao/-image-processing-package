# Dio-image-processing-package
Criação de Pacote de Processamento de Imagem Python


Descrição
O pacote "image_processing-test" é usado para:

Módulo "Processing":

Correspondência de histograma;
Similaridade estrutural;
Redimensionar imagem;
Módulo "Utils":

Ler imagem;
Salvar imagem;
Plotar imagem;
Resultado do gráfico;
Plotar histograma;

Instalação local, após hospedagem no Test Pypi
 Instalação de dependências
pip install -r requirements.txt
 Instalção do Pacote
Use o gerenciador de pacotes pip install -i https://test.pypi.org/simple/ image-processing-test para instalar image_processing-test

pip install image-processing-test
Como usar em qualquer projeto
from image-processing-test.processing import combination
combination.find_difference(image1, image2)

![image](https://user-images.githubusercontent.com/33034037/195414939-d32faac3-c1e7-437e-bd45-5acb14e1e876.png)

Autor (quem hospedou o projeto no Test Pypi)
Alessandra Galvão da Silva
Licença
MIT
