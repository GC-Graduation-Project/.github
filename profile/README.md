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
| 201935075 | Yang-JunHyoung(양준형) | yangkun053@gachon.ac.kr | Sheet Recognition  |
| 201935113 | Lee-HanSeul(이한슬) | parks4754@gmail.com  | Music Recognition  |
| 201935125 | Jung-GyuWon(정규원) | kcc0520@gachon.ac.kr  | Sheet Recognition  |
| 202135563 | Lee-EunSeo(이은서) | silverl@gachon.ac.kr | Music Recognition  |

## Technology stack

- Node.js
- Python
- Pytorch
- OpenCV
- Basic Pitch
- Mido
- YOLOv5
- Flutter

## Using Open Source

- Yolov5 ([https://github.com/ultralytics/yolov5](https://github.com/ultralytics/yolov5))
- mido ([https://github.com/mido/mido](https://github.com/mido/mido))
- basic-pitch ([https://github.com/spotify/basic-pitch](https://github.com/spotify/basic-pitch))
- vextab ([https://github.com/0xfe/vextab] (https://github.com/0xfe/vextab))

## TABO Wiki
- tabo
- logic

## 설치

```bash
pip install -r requirements.txt


