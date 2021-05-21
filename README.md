# detectormasks
<h3> People detector with and without masks with YoloV5 and FasterRCNN </h3>
<h3> Detector de pessoas com e sem mascaras com YoloV5 e FasterRCNN </h3>

![plot](./imgreadm.png)

<p> In this repository you will find the weights already trained to detect the masks wmaskscovid.pt with Yolov5 and also the weights of the model created with FasterRCNN. <p>

<p>Nesse repositorio você encontra os pesos já treinados para detectar as mascaras wmaskscovid.pt com Yolov5 e também os pesos do modelo criado com a FasterRCNN.<p>
    
<p> How does Yolov5 differ from a FasterRCNN?
While FasterR-CNN uses regions of the image to locate the object, Yolo looks at the image only once. In practice Yolo is faster but less accurate. <p>

<p>Qual a difereça do Yolov5 para uma FasterRCNN ?
Emquanto a FasterR-CNN usa regiões da imagem para localizar o objeto, o Yolo olha apenas uma vez para imagem. Na pratica Yolo e mais rapido porém menos preciso.<p>
    
    
<h1 align="center">
    <a href="https://towardsdatascience.com/r-cnn-fast-r-cnn-faster-r-cnn-yolo-object-detection-algorithms-36d53571365e">🔗 See more details in this article/ Veja mais detalhes nesse artigo</a>
</h1>

<h3> Using Yolo </h3>
<h3> Clone YoloV5. </h3>

<h3> Example usage for an image: </h3>

<p> python yolov5 / detect.py --source yolov5 / data / images / people.jpg --weights wmaskscovid.pt --conf 0.25 </p>

<h3> You can also use the webcam in real time: </h3>

python yolov5 / detect.py --source 0 --weights wmaskscovid.pt --conf 0.25

<h3>Usando o Yolo</h3>
<h3>Faça o clone do YoloV5.</h3>

<h3>Exemplo de uso para uma imagem: </h3>

<p> python yolov5/detect.py --source yolov5/data/images/pessoas.jpg --weights wmaskscovid.pt --conf 0.25 </p>

<h3> Você pode também usar a webcam em tempo real: </h3>

python yolov5/detect.py --source 0 --weights wmaskscovid.pt --conf 0.25

<h1 align="center">
    <a href="https://github.com/ultralytics/yolov5">🔗 YoloV5</a>
</h1>
<p align="center">🚀 See more details in the official YoloV5 documentation / Veja mais detalhes na documentação oficial do YoloV5</p>

<h3> Using FasterR-CNN </h3>
<p> Open the notebook in jupyter DetectionMaskRCNN.ipynb if you want to use the Webbcam use cap = cv2.VideoCapture (0) or cap = cv2.VideoCapture (1) and run all the cells. </p>
<p> The jupyter file of all FasterR-CNN training is also in this repository - Mask-Covid-Detection.ipynb </p>

<h3>Usando a FasterR-CNN</h3>
<p> Abra o notebook em jupyter DetectionMaskRCNN.ipynb caso deseje usar a Webbcam utilize cap = cv2.VideoCapture(0) ou cap = cv2.VideoCapture(1) e rode todas as celulas.</p>
<p>O arquivo em jupyter de todo o treinamento da FasterR-CNN também está nesse repositorio - Mask-Covid-Detection.ipynb</p>


<h1 align="center">
    <a href="https://www.packtpub.com/product/modern-computer-vision-with-pytorch/9781839213472">🔗 Sources/Fontes</a>
</h1>
<p align="center">🚀 Modern Computer Vision with PyTorch
</p>
