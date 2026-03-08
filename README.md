🌏 CesiumJS 기반 볼류메트릭 모델 가시화   

CesiumJS(WebGIS) 환경에서 볼류메트릭 비디오(Volumetric Video/Animated GLB) 기술 적용 검토   

1. 프로젝트 개요
  - 목적: 3D 가우시안 스플래팅 및 볼류메트릭 기술의 디지털 트윈 서비스 적용 가능성 검토
  - 기술: CesiumJS, Volumetric Video(glTF/GLB Animation)

2. 기술적 시사점
  - 데이터 최적화: 볼류메트릭 데이터는 일반적인 glTF보다 용량이 크므로, 원활한 서비스를 위해 Draco 압축 기술 적용 및 비동기(async/await) 로딩 처리가 필수적임
  - 향후 동적인 시뮬레이션이나 리플레이 기능을 디지털 트윈에 적용하는 기초 모델로 활용 가능
