# Тестовый проект - детекция игральных карт с помощью нейросети YOLOv8  

В датасете 6 классов:  
0 : ace  
1 : king  
2 : queen  
3 : jack  
4 : ten  
5 : nine  


Датасет был [приведен в формат YOLO](https://github.com/Summit2/Yolo_detecting_cards/blob/main/make_dataset.ipynb)  

[Обучал](https://github.com/Summit2/Yolo_detecting_cards/blob/main/YOLOv8_cards_detection.ipynb) модель, предобученную на COCO dataset, на GPU T4 в Google Collab (100 эпох)  
В [папке с весами](https://github.com/Summit2/Yolo_detecting_cards/tree/main/best_weights) моделей лежат веса yolov8n (nano) и yolov8m (medium)  
