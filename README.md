# mle-template-case-sprint2

Добро пожаловать в репозиторий-шаблон Практикума для проекта 2 спринта. Ваша цель — улучшить ключевые метрики модели для предсказания стоимости квартир Яндекс Недвижимости.

Полное описание проекта хранится в уроке «Проект. Улучшение baseline-модели» на учебной платформе.

Здесь укажите имя вашего бакета: 's3-student-mle-20241126-331bab00fa'

Этап 1:
sh скрипт для запуска MLflow server:
    mlflow_server/run_mlflow_server.sh
experiment_name: yandex_realty_aleksandra
run_id: b131c3f5a7f34ea89e8873c967465d08
model_name: base_model_aleksandra
vesrion_model: 1

Этап 2:
Notebook с исследованиями: EDA.ipynb
Папка с графиками: assets
run_id логирования: 4d9a87e125a14e798712d9df4429239f

Этап 3:
Notebook с улучшением модели: model_improvement/model_improvement.ipynb
График улучшения метрик: assets/metrics_improvement_extracting.png
run_id логирования: 4158aafbea7b470bb6e5c5ac3ba8427a
model_name: better_model_aleksandra
version_model: 5

Этап 4:
Notebook с  feature selection модели: model_improvement/model_improvement.ipynb
График улучшения метрик: assets/metrics_improvement_selection.png
run_id логирования: dc8df06f398d4429aae77fa49a80f5b0
model_name: selection_model_aleksandra'
version_model: 1

