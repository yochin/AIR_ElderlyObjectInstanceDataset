# AIR Project Elderly Object Instance Dataset
> 본 데이터셋은 물체의 인스턴스 인식 기술의 학습 및 평가를 위한 것으로 특히 고령자들이 자주 잃어버리고 찾는 물건들을 대상으로 함.
> [AIR과제](https://ai4robot.github.io/)의 일환으로 수집되었으며, 53명의 69세 이상 고령자들을 대상으로 자주 이용하고, 소지하고, 찾았던 물건들에 대해 관찰조사를 하고, 가장 빈번하게 등장한 15종의 소지품 물체들을 데이터셋의 대상으로 선정함.
> 추가적으로 가정에 공통적으로 존재하는 대형물체 5종을 추가 선정함.

## 내용
### 대상 물체
> 소지품: 안경, 핸드폰, 리모컨, 약봉지, 약통, 컵, 신문, 담배, 모자, 지팡이, 수건, 양말, 지갑, 필기구, 열쇠
> 대형가전: TV, 냉장고, 선풍기, 침구, 소파
![C](image/objects.png) 

(뭘 수집했느냐 보다 어떻게 수집했고, 뭘 공개하느냐에 촛점)

### 구성
> 소지품: 15종 + 대형가전 5종
> 수집 방식: 손에 들고, 테이블에 놓고, 집안에 배치
> 촬영 도구: Kinect v2, 1920x1080 RGB-D ~5fps, ~15초
> 데이터 형식: RGB, annotation정보 (depth는 추가 예정)
> 500장 학습, 100장 평가/물체당

> 총, 몇개물체, 뭐가 제공됨.
> 공개 규모: 손 학습용 10,000장(500장/물체), 평가용 2,000장(100장/물체)

### 디렉토리 구조
> PASCAL VOC 데이터셋의 구조를 따름
    .    
    ├── Annotations             # Image files
    ├── ImageSets
    ├── JpegImages
    ├── Utils
    ├── LICENSE
    └── README.md

### Script

## 다운로드 방법
> 

## Acknowledgements
>> This dataset is supported by the ICT R&D program of MSIP/IITP. [2017-0-00162, Development of Human-care Robot Technology for Aging Society]
