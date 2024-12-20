# Симулятор экосистемы

Это консольное приложение на языке Java моделирует виртуальную экосистему, где можно управлять видами растений и животных, отслеживать пищевые цепи и ресурсы. Симулятор включает предсказания изменений популяций и полную автоматическую симуляцию.

## Особенности
- CRUD-операции для управления объектами экосистемы
- Поддержка нескольких симуляций
- Прогнозирование изменений популяций в зависимости от климата и ресурсов
- Полная автоматическая симуляция с логированием изменений
## Запуск
1. Убедитесь, что у вас установлена Java 8 или выше.
2. Для запуска выполните команду:
   - **Linux/Mac**: `./run.sh`
   - **Windows**: `run.bat`

## Меню управления экосистемой

Приложение предоставляет интерактивное меню, где вы можете выбрать, какое действие выполнить с экосистемой. Введите номер действия, чтобы выбрать его.

### Доступные действия:

1. **Добавить растения или животных**  
   Позволяет добавить новый вид растений или животных в экосистему. После добавления данные будут сохранены в файл.

2. **Обновить информацию о растениях или животных**  
   Позволяет изменить характеристики существующего вида, например, здоровье, численность и др. После обновления данные также сохраняются.

3. **Удалить растения или животных**  
   Удаляет выбранный вид из экосистемы и обновляет файл.

4. **Показать всех живых существ**  
   Выводит текущий список всех видов растений и животных с их характеристиками.

5. **Запуск симуляции экосистемы**  
   Запускает полную симуляцию с логированием всех изменений. Результаты симуляции записываются в файл `simulation_log.txt`.

6. **Прогноз популяций**  
   Генерирует прогноз изменений популяции в зависимости от текущих условий. Прогнозируемые данные показывают, какие виды могут увеличиться, уменьшиться или остаться стабильными.

7. **Назад**  
   Возврат в предыдущее меню.

### Пример использования меню
При запуске приложения введите номер действия и нажмите `Enter`. Например:
- Введите `1` для добавления нового вида в экосистему.
- Введите `5`, чтобы запустить симуляцию и записать изменения в `simulation_log.txt`.

## Автор
Гражина Ульянова
