# real-time-mask-detection
This project is used to detect if a person is wearing mask or not. It can be used in a crowdy place too. The model is trained on yolo v5.
Steps to run:
1. Clone this repo.
2. Download "best.pt" trained model from here and paste it in cloned repo. 
3. Open terminal and change directory to inside of the cloned repo.
4. install requirements.txt (pip install requirements.txt).
5. run command :   python detect.py --source 0 --weights best.pt
6. note: In place of 0 in source you may give path to an image or video if you want to detect in image or video.
7. Test results: ![mask](https://user-images.githubusercontent.com/67053037/123533859-7d942a00-d736-11eb-924b-b173ef92b36c.jpg)
8. ![mask](https://user-images.githubusercontent.com/67053037/123533891-a61c2400-d736-11eb-9b91-1db645f13239.jpg)

