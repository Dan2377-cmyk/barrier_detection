Состав архива:
- dataset_yolo — подготовленный датасет;
- runs — веса, метрики и графики обучения;
- user_results и web_results — результаты детекции;
- report_materials — материалы для отчёта;
- detection_history.json — история запросов;
- history_barrier_detection.xlsx — история в Excel.

Для продолжения работы повторное обучение не требуется. Нужно загрузить best.pt через YOLO и использовать порог 0.0210.