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
Notebook с улучшением модели: model_improvement/feature_extracting.ipynb
График улучшения метрик: assets/metrics_improvement.png
run_id логирования: e87400ce4ceb4c0ea103efb6bb4c69fe
model_name: better_model_aleksandra
version_model: 1