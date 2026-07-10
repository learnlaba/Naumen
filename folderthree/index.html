<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Чек-лист для самопроверки — Практикум №5: База знаний</title>
<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    background: linear-gradient(135deg, #f5f7fa 0%, #e8ecf1 100%);
    color: #2c3e50;
    line-height: 1.6;
    padding: 20px;
    min-height: 100vh;
  }

  .container {
    max-width: 1200px;
    margin: 0 auto;
    background: #ffffff;
    border-radius: 12px;
    box-shadow: 0 10px 40px rgba(0, 0, 0, 0.08);
    overflow: hidden;
  }

  .header {
    background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
    color: #ffffff;
    padding: 40px 30px;
    position: relative;
  }

  .header::before {
    content: '';
    position: absolute;
    top: 0;
    right: 0;
    width: 200px;
    height: 200px;
    background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, transparent 70%);
    border-radius: 50%;
  }

  .header h1 {
    font-size: 28px;
    font-weight: 700;
    margin-bottom: 10px;
    position: relative;
  }

  .header .subtitle {
    font-size: 15px;
    opacity: 0.9;
    position: relative;
  }

  .header .badge {
    display: inline-block;
    background: rgba(255, 255, 255, 0.2);
    padding: 4px 12px;
    border-radius: 20px;
    font-size: 12px;
    font-weight: 600;
    margin-bottom: 12px;
    position: relative;
  }

  .content {
    padding: 30px;
  }

  .intro {
    background: #f8fafc;
    border-left: 4px solid #3b82f6;
    padding: 16px 20px;
    border-radius: 6px;
    margin-bottom: 30px;
    font-size: 14px;
  }

  .intro strong {
    color: #1e3a8a;
  }

  .block {
    margin-bottom: 20px;
    border: 1px solid #e5e7eb;
    border-radius: 10px;
    overflow: hidden;
    transition: all 0.3s ease;
  }

  .block-header {
    background: linear-gradient(135deg, #f1f5f9 0%, #e2e8f0 100%);
    padding: 18px 20px;
    border-bottom: 1px solid #e5e7eb;
    display: flex;
    align-items: center;
    gap: 12px;
    cursor: pointer;
    user-select: none;
    transition: all 0.2s ease;
    position: relative;
  }

  .block-header:hover {
    background: linear-gradient(135deg, #e2e8f0 0%, #cbd5e1 100%);
  }

  .block-header::after {
    content: '';
    position: absolute;
    right: 20px;
    top: 50%;
    transform: translateY(-50%) rotate(0deg);
    width: 0;
    height: 0;
    border-left: 8px solid transparent;
    border-right: 8px solid transparent;
    border-top: 10px solid #3b82f6;
    transition: transform 0.3s ease;
  }

  .block.collapsed .block-header::after {
    transform: translateY(-50%) rotate(-180deg);
  }

  .block-number {
    background: #3b82f6;
    color: #ffffff;
    width: 36px;
    height: 36px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 700;
    font-size: 16px;
    flex-shrink: 0;
    box-shadow: 0 2px 8px rgba(59, 130, 246, 0.3);
  }

  .block-title {
    font-size: 18px;
    font-weight: 700;
    color: #1e3a8a;
    flex-grow: 1;
  }

  .block-count {
    font-size: 14px;
    color: #64748b;
    font-weight: 600;
    background: #ffffff;
    padding: 4px 12px;
    border-radius: 20px;
    border: 1px solid #e5e7eb;
  }

  .block-content {
    overflow: hidden;
    transition: max-height 0.4s ease, padding 0.4s ease;
    max-height: 2000px;
  }

  .block.collapsed .block-content {
    max-height: 0;
    padding: 0;
  }

  .block-content table {
    width: 100%;
    border-collapse: collapse;
    table-layout: fixed;
  }

  thead {
    background: #f8fafc;
  }

  th {
    padding: 14px 16px;
    text-align: left;
    font-size: 12px;
    font-weight: 600;
    color: #64748b;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    border-bottom: 2px solid #e5e7eb;
  }

  th:nth-child(1) { width: 60px; }
  th:nth-child(2) { width: auto; }
  th:nth-child(3) { width: 100px; text-align: center; }
  th:nth-child(4) { width: 250px; }

  td {
    padding: 16px;
    border-bottom: 1px solid #f1f5f9;
    font-size: 14px;
    vertical-align: middle;
  }

  tr:last-child td {
    border-bottom: none;
  }

  tr:hover {
    background: #fafbfc;
  }

  .row-number {
    font-weight: 600;
    color: #3b82f6;
  }

  .row-criterion {
    color: #1e293b;
    word-wrap: break-word;
  }

  .row-criterion code {
    background: #f1f5f9;
    padding: 3px 8px;
    border-radius: 4px;
    font-family: 'Courier New', monospace;
    font-size: 13px;
    color: #0f172a;
    border: 1px solid #e2e8f0;
  }

  .row-checkbox {
    text-align: center;
  }

  .checkbox-wrapper {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 32px;
    height: 32px;
    border: 2px solid #cbd5e1;
    border-radius: 8px;
    cursor: pointer;
    transition: all 0.2s ease;
    background: #ffffff;
  }

  .checkbox-wrapper:hover {
    border-color: #3b82f6;
    transform: scale(1.1);
    box-shadow: 0 2px 8px rgba(59, 130, 246, 0.2);
  }

  .checkbox-wrapper.checked {
    background: #10b981;
    border-color: #10b981;
  }

  .checkbox-wrapper.checked::after {
    content: '✓';
    color: #ffffff;
    font-weight: 700;
    font-size: 18px;
  }

  .checkbox-wrapper input {
    display: none;
  }

  .row-hint {
    font-size: 13px;
    color: #64748b;
    font-style: italic;
    background: #f8fafc;
    padding: 8px 12px;
    border-radius: 6px;
    border-left: 3px solid #3b82f6;
    line-height: 1.4;
  }

  .row-hint::before {
    content: '💡 ';
  }

  .results-section {
    background: linear-gradient(135deg, #f8fafc 0%, #f1f5f9 100%);
    border-radius: 10px;
    padding: 24px;
    margin-top: 30px;
    border: 1px solid #e5e7eb;
  }

  .results-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
    flex-wrap: wrap;
    gap: 12px;
  }

  .results-title {
    font-size: 18px;
    font-weight: 700;
    color: #1e3a8a;
  }

  .results-counter {
    font-size: 14px;
    color: #475569;
  }

  .results-counter strong {
    color: #1e3a8a;
    font-size: 20px;
  }

  .progress-bar {
    width: 100%;
    height: 12px;
    background: #e2e8f0;
    border-radius: 6px;
    overflow: hidden;
    margin-bottom: 20px;
    box-shadow: inset 0 2px 4px rgba(0,0,0,0.1);
  }

  .progress-fill {
    height: 100%;
    background: linear-gradient(90deg, #3b82f6 0%, #10b981 100%);
    transition: width 0.4s ease;
    border-radius: 6px;
  }

  .criteria-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 12px;
  }

  .criteria-item {
    padding: 16px 18px;
    border-radius: 8px;
    border-left: 4px solid;
    background: #ffffff;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);
  }

  .criteria-item.excellent {
    border-color: #10b981;
  }

  .criteria-item.good {
    border-color: #f59e0b;
  }

  .criteria-item.needs-work {
    border-color: #ef4444;
  }

  .criteria-item .label {
    font-size: 12px;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    margin-bottom: 6px;
  }

  .criteria-item.excellent .label { color: #10b981; }
  .criteria-item.good .label { color: #f59e0b; }
  .criteria-item.needs-work .label { color: #ef4444; }

  .criteria-item .range {
    font-size: 14px;
    color: #475569;
    font-weight: 600;
    margin-bottom: 4px;
  }

  .criteria-item .desc {
    font-size: 13px;
    color: #64748b;
  }

  .status-message {
    margin-top: 20px;
    padding: 18px 20px;
    border-radius: 8px;
    font-size: 15px;
    font-weight: 600;
    text-align: center;
    transition: all 0.3s ease;
  }

  .status-message.pending {
    background: #f1f5f9;
    color: #64748b;
  }

  .status-message.success {
    background: #d1fae5;
    color: #065f46;
    border: 1px solid #10b981;
  }

  .status-message.warning {
    background: #fef3c7;
    color: #92400e;
    border: 1px solid #f59e0b;
  }

  .status-message.danger {
    background: #fee2e2;
    color: #991b1b;
    border: 1px solid #ef4444;
  }

  .actions {
    display: flex;
    gap: 12px;
    margin-top: 24px;
    flex-wrap: wrap;
  }

  .btn {
    padding: 12px 24px;
    border: none;
    border-radius: 8px;
    font-size: 14px;
    font-weight: 600;
    cursor: pointer;
    transition: all 0.2s ease;
    display: inline-flex;
    align-items: center;
    gap: 8px;
  }

  .btn-primary {
    background: #3b82f6;
    color: #ffffff;
  }

  .btn-primary:hover {
    background: #2563eb;
    transform: translateY(-1px);
    box-shadow: 0 4px 12px rgba(59, 130, 246, 0.3);
  }

  .btn-secondary {
    background: #ffffff;
    color: #475569;
    border: 1px solid #e5e7eb;
  }

  .btn-secondary:hover {
    background: #f8fafc;
    border-color: #cbd5e1;
  }

  .btn-success {
    background: #10b981;
    color: #ffffff;
  }

  .btn-success:hover {
    background: #059669;
    transform: translateY(-1px);
    box-shadow: 0 4px 12px rgba(16, 185, 129, 0.3);
  }

  .btn:disabled {
    opacity: 0.5;
    cursor: not-allowed;
    transform: none !important;
  }

  .save-indicator {
    position: fixed;
    top: 20px;
    right: 20px;
    background: #10b981;
    color: white;
    padding: 10px 20px;
    border-radius: 8px;
    font-size: 14px;
    font-weight: 600;
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
    opacity: 0;
    transform: translateY(-20px);
    transition: all 0.3s ease;
    z-index: 1000;
  }

  .save-indicator.show {
    opacity: 1;
    transform: translateY(0);
  }

  @media (max-width: 768px) {
    body { padding: 10px; }
    .header { padding: 24px 20px; }
    .header h1 { font-size: 22px; }
    .content { padding: 20px; }
    
    th, td { padding: 12px; font-size: 13px; }
    .row-hint { display: none; }
    
    .criteria-list { grid-template-columns: 1fr; }
    
    .block-header {
      padding: 16px;
    }
    
    .block-title {
      font-size: 16px;
    }
  }

  @media print {
    body { background: #ffffff; padding: 0; }
    .container { box-shadow: none; }
    .actions { display: none; }
    .save-indicator { display: none; }
    .checkbox-wrapper { border: 2px solid #333; }
    .block-content { max-height: none !important; }
    .block-header::after { display: none; }
  }
</style>
</head>
<body>

<div class="save-indicator" id="save-indicator">💾 Изменения сохранены</div>

<div class="container">
  <div class="header">
    <div class="badge">ПРАКТИКУМ №5</div>
    <h1>Чек-лист для самопроверки</h1>
    <div class="subtitle">Создание и наполнение базы знаний (KMS) в Naumen Contact Center</div>
  </div>

  <div class="content">
    <div class="intro">
      <strong>Инструкция:</strong> Отметьте каждый выполненный критерий, поставив галочку в соответствующей строке. 
      Система автоматически подсчитает результат и покажет итоговую оценку.
      <br><br>
      <strong>💡 Подсказка:</strong> Нажмите на заголовок блока, чтобы свернуть/развернуть его содержимое. 
      <strong>Все изменения сохраняются автоматически!</strong>
    </div>

    <!-- БЛОК 1 -->
    <div class="block" id="block1">
      <div class="block-header" onclick="toggleBlock('block1')">
        <div class="block-number">1</div>
        <div class="block-title">Создание структуры (разделы)</div>
        <div class="block-count" id="block1-count">0 / 5</div>
      </div>
      <div class="block-content">
        <table>
          <thead>
            <tr>
              <th>№</th>
              <th>Критерий проверки</th>
              <th style="text-align: center;">Да / Нет</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="row-number">1.1</td>
              <td class="row-criterion">Создан раздел <strong>«Программа лояльности»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="1" data-id="1.1">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">1.2</td>
              <td class="row-criterion">Создан раздел <strong>«Доставка»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="1" data-id="1.2">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">1.3</td>
              <td class="row-criterion">У каждого раздела указано понятное название (не «Раздел 1», а смысловое)</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="1" data-id="1.3">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">1.4</td>
              <td class="row-criterion">Для каждого раздела добавлены метки (теги) через запятую (например: «лояльность, баллы, скидки» и «доставка, зона, время»)</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="1" data-id="1.4">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">1.5</td>
              <td class="row-criterion">Разделы сохранены без ошибок</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="1" data-id="1.5">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>

    <!-- БЛОК 2 -->
    <div class="block" id="block2">
      <div class="block-header" onclick="toggleBlock('block2')">
        <div class="block-number">2</div>
        <div class="block-title">Создание статей — раздел «Программа лояльности»</div>
        <div class="block-count" id="block2-count">0 / 4</div>
      </div>
      <div class="block-content">
        <table>
          <thead>
            <tr>
              <th>№</th>
              <th>Критерий проверки</th>
              <th style="text-align: center;">Да / Нет</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="row-number">2.1</td>
              <td class="row-criterion">Создана статья <strong>«Условия накопительной карты»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="2" data-id="2.1">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">2.2</td>
              <td class="row-criterion">Создана статья <strong>«Скидки по категориям»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="2" data-id="2.2">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">2.3</td>
              <td class="row-criterion">Создана статья <strong>«Как восстановить утерянную карту»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="2" data-id="2.3">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">2.4</td>
              <td class="row-criterion">Все 3 статьи привязаны к разделу <strong>«Программа лояльности»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="2" data-id="2.4">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>

    <!-- БЛОК 3 -->
    <div class="block" id="block3">
      <div class="block-header" onclick="toggleBlock('block3')">
        <div class="block-number">3</div>
        <div class="block-title">Создание статей — раздел «Доставка»</div>
        <div class="block-count" id="block3-count">0 / 4</div>
      </div>
      <div class="block-content">
        <table>
          <thead>
            <tr>
              <th>№</th>
              <th>Критерий проверки</th>
              <th style="text-align: center;">Да / Нет</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="row-number">3.1</td>
              <td class="row-criterion">Создана статья <strong>«Условия бесплатной доставки»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="3" data-id="3.1">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">3.2</td>
              <td class="row-criterion">Создана статья <strong>«Зоны покрытия»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="3" data-id="3.2">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">3.3</td>
              <td class="row-criterion">Создана статья <strong>«Время доставки по районам»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="3" data-id="3.3">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">3.4</td>
              <td class="row-criterion">Все 3 статьи привязаны к разделу <strong>«Доставка»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="3" data-id="3.4">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>

    <!-- БЛОК 4 -->
    <div class="block" id="block4">
      <div class="block-header" onclick="toggleBlock('block4')">
        <div class="block-number">4</div>
        <div class="block-title">Наполнение статей (содержание)</div>
        <div class="block-count" id="block4-count">0 / 8</div>
      </div>
      <div class="block-content">
        <table>
          <thead>
            <tr>
              <th>№</th>
              <th>Критерий проверки</th>
              <th style="text-align: center;">Да / Нет</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="row-number">4.1</td>
              <td class="row-criterion">В каждой статье заполнено поле <strong>«Название»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="4" data-id="4.1">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">4.2</td>
              <td class="row-criterion">В каждой статье заполнено поле <strong>«Метки»</strong> (ключевые слова через запятую)</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="4" data-id="4.2">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">4.3</td>
              <td class="row-criterion">В каждой статье заполнено поле <strong>«Текст»</strong> с использованием WYSIWYG-редактора</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="4" data-id="4.3">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">4.4</td>
              <td class="row-criterion">В статьях использовано форматирование: жирный шрифт для акцентов, маркированные/нумерованные списки</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="4" data-id="4.4">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">4.5</td>
              <td class="row-criterion">В статьях <strong>«Скидки по категориям»</strong> и <strong>«Время доставки по районам»</strong> добавлены таблицы</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="4" data-id="4.5">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">4.6</td>
              <td class="row-criterion">В статьях присутствует блок <strong>«Речевой модуль для оператора»</strong> (выделенный визуально)</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="4" data-id="4.6">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">4.7</td>
              <td class="row-criterion">В статьях присутствует блок <strong>«Важно для оператора»</strong> с предупреждениями</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="4" data-id="4.7">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">4.8</td>
              <td class="row-criterion">Все 6 статей сохранены без ошибок</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="4" data-id="4.8">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>

    <!-- БЛОК 5 -->
    <div class="block" id="block5">
      <div class="block-header" onclick="toggleBlock('block5')">
        <div class="block-number">5</div>
        <div class="block-title">Тестирование поиска в KMS</div>
        <div class="block-count" id="block5-count">0 / 8</div>
      </div>
      <div class="block-content">
        <table>
          <thead>
            <tr>
              <th>№</th>
              <th>Критерий поиска</th>
              <th style="text-align: center;">Да / Нет</th>
              <th>Ожидаемый результат</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="row-number">5.1</td>
              <td class="row-criterion">Поиск по слову <strong>«баллы»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="5" data-id="5.1">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
              <td class="row-hint">Находит статью «Условия накопительной карты»</td>
            </tr>
            <tr>
              <td class="row-number">5.2</td>
              <td class="row-criterion">Поиск по слову <strong>«скидки»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="5" data-id="5.2">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
              <td class="row-hint">Находит статью «Скидки по категориям»</td>
            </tr>
            <tr>
              <td class="row-number">5.3</td>
              <td class="row-criterion">Поиск по слову <strong>«карта»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="5" data-id="5.3">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
              <td class="row-hint">Находит статью «Как восстановить утерянную карту»</td>
            </tr>
            <tr>
              <td class="row-number">5.4</td>
              <td class="row-criterion">Поиск по слову <strong>«доставка»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="5" data-id="5.4">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
              <td class="row-hint">Находит статью «Условия бесплатной доставки»</td>
            </tr>
            <tr>
              <td class="row-number">5.5</td>
              <td class="row-criterion">Поиск по слову <strong>«зона»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="5" data-id="5.5">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
              <td class="row-hint">Находит статью «Зоны покрытия»</td>
            </tr>
            <tr>
              <td class="row-number">5.6</td>
              <td class="row-criterion">Поиск по слову <strong>«время»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="5" data-id="5.6">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
              <td class="row-hint">Находит статью «Время доставки по районам»</td>
            </tr>
            <tr>
              <td class="row-number">5.7</td>
              <td class="row-criterion">Поиск по слову <strong>«пенсионер»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="5" data-id="5.7">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
              <td class="row-hint">Находит статью «Скидки по категориям»</td>
            </tr>
            <tr>
              <td class="row-number">5.8</td>
              <td class="row-criterion">Поиск по слову <strong>«курьер»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="5" data-id="5.8">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
              <td class="row-hint">Находит статьи раздела «Доставка»</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>

    <!-- БЛОК 6 -->
    <div class="block" id="block6">
      <div class="block-header" onclick="toggleBlock('block6')">
        <div class="block-number">6</div>
        <div class="block-title">Интеграция с анкетой</div>
        <div class="block-count" id="block6-count">0 / 5</div>
      </div>
      <div class="block-content">
        <table>
          <thead>
            <tr>
              <th>№</th>
              <th>Критерий проверки</th>
              <th style="text-align: center;">Да / Нет</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="row-number">6.1</td>
              <td class="row-criterion">В стартовую форму анкеты <strong>«Аптечные пункты»</strong> добавлено расширение <strong>«База знаний»</strong></td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="6" data-id="6.1">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">6.2</td>
              <td class="row-criterion">Расширение корректно отображается в интерфейсе оператора</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="6" data-id="6.2">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">6.3</td>
              <td class="row-criterion">Через расширение выполняется поиск по ключевым словам — статьи находятся</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="6" data-id="6.3">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">6.4</td>
              <td class="row-criterion">При клике на статью открывается её полное содержание</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="6" data-id="6.4">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
            <tr>
              <td class="row-number">6.5</td>
              <td class="row-criterion">Таблицы и форматирование в статьях отображаются корректно</td>
              <td class="row-checkbox">
                <label class="checkbox-wrapper" data-block="6" data-id="6.5">
                  <input type="checkbox" onchange="updateResults()">
                </label>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>

    <!-- РЕЗУЛЬТАТЫ -->
    <div class="results-section">
      <div class="results-header">
        <div class="results-title">📊 Итоговый результат</div>
        <div class="results-counter">
          Выполнено: <strong id="total-done">0</strong> из <strong>34</strong>
        </div>
      </div>

      <div class="progress-bar">
        <div class="progress-fill" id="progress-fill" style="width: 0%"></div>
      </div>

      <div class="criteria-list">
        <div class="criteria-item excellent">
          <div class="label">Отлично</div>
          <div class="range">30–34 пункта «Да»</div>
          <div class="desc">Задание выполнено полностью. Можно переходить к следующему модулю</div>
        </div>
        <div class="criteria-item good">
          <div class="label">Хорошо</div>
          <div class="range">24–29 пунктов «Да»</div>
          <div class="desc">Есть недочёты. Перепроверьте блоки с «Нет»</div>
        </div>
        <div class="criteria-item needs-work">
          <div class="label">Нужно доработать</div>
          <div class="range">Менее 24 пунктов «Да»</div>
          <div class="desc">Обратитесь к материалам Модуля 6 или наставнику</div>
        </div>
      </div>

      <div class="status-message pending" id="status-message">
        ⏳ Отметьте критерии, чтобы увидеть итоговую оценку
      </div>

      <div class="actions">
        <button class="btn btn-primary" onclick="window.print()">
          🖨️ Распечатать
        </button>
        <button class="btn btn-secondary" onclick="resetChecklist()">
          🔄 Сбросить
        </button>
        <button class="btn btn-success" id="finish-btn" onclick="finishTask()" disabled>
          ✅ Завершить задание
        </button>
      </div>
    </div>
  </div>
</div>

<script>
  // Показ индикатора сохранения
  function showSaveIndicator() {
    const indicator = document.getElementById('save-indicator');
    indicator.classList.add('show');
    setTimeout(() => {
      indicator.classList.remove('show');
    }, 2000);
  }

  // Сохранение состояния чекбоксов
  function saveCheckboxes() {
    const checkboxes = document.querySelectorAll('.checkbox-wrapper input');
    const state = {};
    checkboxes.forEach(cb => {
      const id = cb.parentElement.getAttribute('data-id');
      if (id) {
        state[id] = cb.checked;
      }
    });
    localStorage.setItem('checklist5_state', JSON.stringify(state));
    showSaveIndicator();
  }

  // Загрузка состояния чекбоксов
  function loadCheckboxes() {
    const saved = localStorage.getItem('checklist5_state');
    if (saved) {
      const state = JSON.parse(saved);
      document.querySelectorAll('.checkbox-wrapper input').forEach(cb => {
        const id = cb.parentElement.getAttribute('data-id');
        if (id && state[id] !== undefined) {
          cb.checked = state[id];
          cb.parentElement.classList.toggle('checked', state[id]);
        }
      });
    }
  }

  // Функция сворачивания/разворачивания блоков
  function toggleBlock(blockId) {
    const block = document.getElementById(blockId);
    block.classList.toggle('collapsed');
    
    // Сохраняем состояние в localStorage
    const isCollapsed = block.classList.contains('collapsed');
    localStorage.setItem('block5_' + blockId + '_collapsed', isCollapsed);
  }

  // Обработка клика по чекбоксу
  document.querySelectorAll('.checkbox-wrapper').forEach(wrapper => {
    wrapper.addEventListener('click', function(e) {
      e.preventDefault();
      e.stopPropagation();
      const input = this.querySelector('input');
      input.checked = !input.checked;
      this.classList.toggle('checked', input.checked);
      updateResults();
      saveCheckboxes();
    });
  });

  function updateResults() {
    const checkboxes = document.querySelectorAll('.checkbox-wrapper input');
    const total = checkboxes.length;
    let done = 0;
    let block1 = 0, block2 = 0, block3 = 0, block4 = 0, block5 = 0, block6 = 0;

    checkboxes.forEach(cb => {
      if (cb.checked) {
        done++;
        const block = cb.parentElement.getAttribute('data-block');
        if (block === '1') block1++;
        if (block === '2') block2++;
        if (block === '3') block3++;
        if (block === '4') block4++;
        if (block === '5') block5++;
        if (block === '6') block6++;
      }
    });

    // Обновление счётчиков
    document.getElementById('block1-count').textContent = `${block1} / 5`;
    document.getElementById('block2-count').textContent = `${block2} / 4`;
    document.getElementById('block3-count').textContent = `${block3} / 4`;
    document.getElementById('block4-count').textContent = `${block4} / 8`;
    document.getElementById('block5-count').textContent = `${block5} / 8`;
    document.getElementById('block6-count').textContent = `${block6} / 5`;
    document.getElementById('total-done').textContent = done;

    // Прогресс-бар
    const percent = (done / total) * 100;
    document.getElementById('progress-fill').style.width = `${percent}%`;

    // Статусное сообщение
    const statusMsg = document.getElementById('status-message');
    const finishBtn = document.getElementById('finish-btn');

    if (done === 0) {
      statusMsg.className = 'status-message pending';
      statusMsg.textContent = '⏳ Отметьте критерии, чтобы увидеть итоговую оценку';
      finishBtn.disabled = true;
    } else if (done >= 30) {
      statusMsg.className = 'status-message success';
      statusMsg.textContent = `🎉 Отлично! Выполнено ${done} из ${total} критериев. Задание выполнено полностью!`;
      finishBtn.disabled = false;
    } else if (done >= 24) {
      statusMsg.className = 'status-message warning';
      statusMsg.textContent = `⚠️ Хорошо. Выполнено ${done} из ${total}. Перепроверьте блоки с «Нет».`;
      finishBtn.disabled = true;
    } else {
      statusMsg.className = 'status-message danger';
      statusMsg.textContent = `❌ Нужно доработать. Выполнено ${done} из ${total}. Обратитесь к материалам Модуля 6.`;
      finishBtn.disabled = true;
    }
  }

  function resetChecklist() {
    if (!confirm('Сбросить все отметки?')) return;
    document.querySelectorAll('.checkbox-wrapper input').forEach(cb => {
      cb.checked = false;
    });
    document.querySelectorAll('.checkbox-wrapper').forEach(w => {
      w.classList.remove('checked');
    });
    localStorage.removeItem('checklist5_state');
    updateResults();
    showSaveIndicator();
  }

  function finishTask() {
    const done = document.querySelectorAll('.checkbox-wrapper input:checked').length;
    if (done < 30) {
      alert('Для завершения задания необходимо выполнить минимум 30 критериев.');
      return;
    }
    alert(`✅ Поздравляем! Практикум №5 завершён.\n\nВыполнено критериев: ${done} из 34.\n\nНажмите "Продолжить" для перехода к следующему модулю.`);
  }

  // Восстановление состояния при загрузке страницы
  window.addEventListener('DOMContentLoaded', function() {
    // Загрузка чекбоксов
    loadCheckboxes();
    
    // Восстановление состояния блоков
    ['block1', 'block2', 'block3', 'block4', 'block5', 'block6'].forEach(blockId => {
      const isCollapsed = localStorage.getItem('block5_' + blockId + '_collapsed') === 'true';
      if (isCollapsed) {
        document.getElementById(blockId).classList.add('collapsed');
      }
    });
    
    // Обновление результатов
    updateResults();
  });
</script>

</body>
</html>
