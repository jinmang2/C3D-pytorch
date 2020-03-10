# Study for implementation
- 구현을 위한 공부 목록 작성

## 논문 구현 과정
### First, Video 파일 읽기
- `cv2`
    - OpenCV로 간단하게 video 읽기
- `torchvision`
    - Pytorch에서 구현되있는 video 관련 모듈을 학습하고 video frame, audio frame에 대한 이해도를 높인다.
    
### Second, Input Data Module 만들기
- `torch.utils.data`의 `dataset.py`와 `dataloader.py`로 CustomDataset 구축
- `torchvision`에서 다루는 video 데이터셋 처리를 참고
- generator로 만들어서 메모리를 효율적으로 사용하고 속도 최적화를 추구

### Third, model 실험 및 학습
- C3D 모델 구현

### Fourth, Inference 코드 작성

### Fifth, 전체 모듈화 및 `argparser`로 python 명령어로 가동시킬 수 있게 만들기

### Sixth, 코드 리뷰 받기
