# 🎵 타브 악보 변환 시스템

> 가천대학교 소프트웨어학과 졸업작품 (2024)  
> 지도교수 : 최재영 교수님

## 개요

우리의 프로젝트는 타브 악보 변환 시스템으로, YOLOv5를 사용한 악보 인식, basic-pitch를 통한 오디오 음정 감지, mido를 이용한 MIDI 파일 처리를 통해 시각적 및 음성 입력에서 정확하고 읽기 쉬운 타브 악보를 생성할 수 있는 애플리케이션입니다.

## 기능

- **악보 인식**: YOLOv5를 사용하여 이미지 악보를 인식하고 처리합니다.
- **음원 인식**: basic-pitch와 mido를 통해 음원 인식을 수행합니다.
- **악보 변환**: 인식된 결과를 토대로 Vextab을 통해 타브 악보 변환 후 이미지 출력을 수행합니다.

## Collaborators

| ID        | Name             | Email                | Role                |
|-----------|------------------|----------------------|----------------------|
| 201935070 | Shin-HyeonHo(신현호) | shin269@gachon.ac.kr | Data Classification  |
| 201935075 | Yang-JunHyoung(양준형) | yangkun053@gachon.ac.kr | Sheet Recognition  |
| 201935113 | Lee-HanSeul(이한슬) | hanseul37@gachon.ac.kr  | Music Source  |
| 201935125 | Jung-GyuWon(정규원) | kcc0520@gachon.ac.kr  | Sheet Recognition  |
| 202135563 | Lee-EunSeo(이은서) | silverl@gachon.ac.kr | Music Source  |
| 201935145 | Choi-Junbum(최준범) | gw06052@gachon.ac.kr | Data Classification |

## Technology stack

### Languages
<div>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white">
</div>

### Frameworks
<div>
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white">
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white">
</div>

### Deap Learning
<div>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/yolo-00FFFF?style=for-the-badge&logo=yolo&logoColor=black">
</div>

## Using Open Source

- Yolov5 (https://github.com/ultralytics/yolov5)
- mido (https://github.com/mido/mido)
- demucs (https://github.com/facebookresearch/demucs)
- basic-pitch (https://github.com/spotify/basic-pitch)
- vextab (https://github.com/0xfe/vextab)

## TABO Wiki
- tabo
- logic

## 설치

```bash
pip install -r requirements.txt


