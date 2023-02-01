# car-damage-segmentation

* **Damage_segmentation_with_Unet_final_results_only.ipynb** : 진행했던 코드 작업에 대한 단계적 설명. 

* 디렉토리 구조 및 파일별 역할


|— code

| &nbsp; &nbsp; &nbsp; |— src
> 

| &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; |— `Dataset.py` : Custom dataset 정의, dataset resize, transform
> 

| &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; |— `Evaluation.py` : 모델 성능 검증 코드
> 

| &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; |— `Models.py` : smp 라이브러리를 활용한 Unet 모델 class
> 

| &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; |— `Models_implementation.py` : 논문 기반으로 구현한 Unet 모델 class(w.batchnorm)
> 

| &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; |— `Train.py` : train loop, data loader, validation
> 

| &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; |— `Utils.py` : Annotation 형식 변환, loss & metric 계산 함수들
> 

| &nbsp; &nbsp; &nbsp; |— `main.py`
> 

| &nbsp; &nbsp; &nbsp; |— `damage_labeling.csv` : raw annotation 파일 → 추후 가공을 통해 `data/datainfo`의 json 파일들로 변경
>


|— dataa

| &nbsp; &nbsp; &nbsp; |— datainfo : 
> 
