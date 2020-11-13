Hand Detection
==============================


O que é?
-------------

Adaptação simples usando o modelo pré-treinado com o dataset grátis [CMU Hand DB](http://domedb.perception.cs.cmu.edu/handdb.html) do projeto open-source [yolo-hand-detection](https://github.com/cansik/yolo-hand-detection)

Como usar
---------------

1. Clone o repositório
2. Baixe o peso e configuração do modelo nos links abaixo
3. Coloque-as na pasta models presente no projeto
4. Tenha a versão 3.8+ do Python instalado
5. Execute `pip install -r requirements.txt` para instalar as dependencias
6. Execute `python webcam.py`

### Download

- YOLOv3 Cross-Dataset
	- [Configuration](https://github.com/cansik/yolo-hand-detection/releases/download/pretrained/cross-hands.cfg)
	- [Weights](https://github.com/cansik/yolo-hand-detection/releases/download/pretrained/cross-hands.weights)