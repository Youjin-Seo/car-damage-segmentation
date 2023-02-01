# car-damage-segmentation

* **Damage_segmentation_with_Unet_final_results_only.ipynb** : 진행했던 코드 작업에 대한 단계적 설명. 

* 디렉토리 구조 및 파일별 역할


|— code

> |— src
> 

> |    |— `Dataset.py` : Custom dataset 정의, dataset resize, transform
> 

> |    |— `Evaluation.py` : 모델 성능 검증 코드
> 

> |    |— `Models.py` : smp 라이브러리를 활용한 Unet 모델 class
> 

> |    |— `Models_implementation.py` : 논문 기반으로 구현한 Unet 모델 class(w.batchnorm)
> 

> |    |— `Train.py` : train loop, data loader, validation
> 

> |    |— `Utils.py` : Annotation 형식 변환, loss & metric 계산 함수들
> 

> |— `main.py`
> 

> |— `damage_labeling.csv` : raw annotation 파일 → 추후 가공을 통해 `data/datainfo`의 json 파일들로 변경
>
