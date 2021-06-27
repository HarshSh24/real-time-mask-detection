# real-time-mask-detection
This project is used to detect if a person is wearing mask or not. It can be used in a crowdy place too. The model is trained on yolo v5.
Steps to run:
1. Clone this repo.
2. Download "best.pt" trained model from " https://drive.google.com/file/d/12lAUKD3yi_wMR55vpQbyBV3r5CBMnfQw/view?usp=sharing" and paste it in cloned repo.
3. Open terminal and change directory to inside of the cloned repo.
4. Install requirements.txt (pip install -r requirements.txt).
5. Run command :   python detect.py --source 0 --weights best.pt
6. Or without changing directory, instead of detect.py, best.pt and requirements.txt, write complete path of detect.py, best.pt and requirements.txt.
7. Note: In place of 0 in source you may give path to an image or video if you want to detect in image or video.
8. Press qq to exit real time window when done.
9. Test results: ![mask](https://user-images.githubusercontent.com/67053037/123533859-7d942a00-d736-11eb-924b-b173ef92b36c.jpg)
10. ![mask](https://user-images.githubusercontent.com/67053037/123533891-a61c2400-d736-11eb-9b91-1db645f13239.jpg)
