# detectormasks
Detector de Mascaras com YoloV5

![plot](./runs/detect/exp4/pessoas.jpg)

Nesse repositorio você encontra os pesos já treinados para detectar as mascaras wmaskscovid.pt

Faça o clone do YoloV5 em https://github.com/ultralytics/yolov5

Exemplo de uso para uma imagem:
python yolov5/detect.py --source yolov5/data/images/pessoas.jpg --weights wmaskscovid.pt --conf 0.25

Você pode também usar a webcam em tempo real:
python yolov5/detect.py --source 0 --weights wmaskscovid.pt --conf 0.25

Veja mais detalhes na documentação oficial do YoloV5.
