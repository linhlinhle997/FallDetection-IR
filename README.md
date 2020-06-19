---
title: Fall Detection IR
created: '2020-06-18T06:26:26.707Z'
modified: '2020-06-18T08:23:21.137Z'
---

# Fall Detection IR

### Prerequisites
- Python >= 3.7
- Pytorch >= 1.5.0
- OpeCV >= 4.2.0

### Pre-Trained Models
- SPPE FastPose (AlphaPose) - [fast_res](https://drive.google.com/file/d/1GyVA7kPcHpaauDp6HUT1KyeeJFsn6cVd/view?usp=sharing)
- ST-GCN action regconition - [tsstg-model](https://drive.google.com/file/d/1NiN-2JuhngG1Q3RYZdZGPikJ31UlPvuY/view?usp=sharing)
- Tiny-YOLO oneclass - [yolo-tiny-onecls](https://drive.google.com/file/d/1QQ0pWakX6sIX71HkkMktQE8tVOMQn3mX/view?usp=sharing)

### Use
1. Install packages from `requirements.txt`
```markdown
pip install -r requirements.txt
```
2. Download all pre-trained models into `./Models` folder.
3. Run main.py
- Run with video
```markdown
python main.py -c ./video/input/test.avi -o ./video/output/test_out.avi
```
- Run with Camera
```markdown
python main.py -c 0 -o ./video/output/test_out.avi
```
### Reference
- AlphaPose: [https://github.com/Amanbhandula/AlphaPose](https://github.com/Amanbhandula/AlphaPose)
- ST-GCN: [https://github.com/yysijie/st-gcn](https://github.com/yysijie/st-gcn)
- Human-Falling-Detect-Tracks [https://github.com/GajuuzZ/Human-Falling-Detect-Tracks](https://github.com/GajuuzZ/Human-Falling-Detect-Tracks)

