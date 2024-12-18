<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lua GG Script Generator</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
            color: #333;
            background-color: #f9f9f9;
        }
        h1, h2 {
            text-align: center;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
        }
        .functions {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 20px;
        }
        .function {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            gap: 15px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 8px;
            background-color: white;
        }
        .code-box {
            white-space: pre-wrap;
            font-family: monospace;
            border: 1px solid #ccc;
            padding: 10px;
            background-color: white;
            margin: 20px 0;
            height: 300px;
            overflow-y: scroll;
        }
        button {
    font-size: 15px;
    font-weight: bold;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 10px;
    cursor: pointer;
    transition: background-color 0.3s, box-shadow 0.3s;
    background-image: linear-gradient(to right, #2196F3, #64B5F6);
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

button:hover {
    background-image: linear-gradient(to right, #2196F3, #64B5F6);
    box-shadow: 0 8px 16px rgba(10, 5, 5, 0.8);
}
        .menu-options {
            display: none;
            margin-top: 20px;
        }
        .menu-options.active {
            display: block;
        }
        .menu-settings {
            margin-bottom: 20px;
        }
		#emojiMenu select {
    width: 10%; /* Задайте ширину на 100% */
    height: auto; /* Змініть висоту відповідно до вмісту */
}


    </style>
</head>
<body>

 <h1 id="version-title" style="text-align: center;font-size: 24px; font-weight: bold; color: #2196F3; text-shadow: 0 0 10px #64B5F6; border-bottom: 4px solid #64B5F6; padding-bottom: 10px;">Script Lua Builder</h1>
 <h3 id="version-title" style="text-align: center;font-size: 24px; font-weight: bold; color: #2196F3; text-shadow: 0 0 10px #64B5F6; border-bottom: 4px solid #64B5F6; padding-bottom: 10px;">CreateD By - @LambaTyT</h3>
<div class="instructions-container">
    <button onclick="showInstruction()">Инструкция</button>
    <!-- Скрытый блок с инструкцией -->
    <div id="instructionBlock" style="display: none; margin-top: 15px; padding: 10px; border: 1px solid #ccc; background-color: #f9f9f9;">
        <h3>Пример использования `gg.getResults`:</h3>
        <p><strong>Описание:</strong> <code>gg.getResults</code> получает данные результатов (количество).</p>
        <p><strong>Пример:</strong></p>
        <pre style="background-color: #f4f4f4; padding: 10px; border-radius: 5px;">
-- Получить результаты поиска
gg.searchNumber("4", gg.TYPE_DWORD)
local results = gg.getResults(10) -- Получаем 10 найденных значений
gg.toast("Найдено " .. #results .. " результатов")
        </pre>
		<h3>Пример использования `gg.setVisible(false)`:</h3>
            <p><strong>Описание:</strong> <code>gg.setVisible(false)</code> делает интерфейс Game Guardian невидимым.</p>
            <p><strong>Пример:</strong></p>
            <pre style="background-color: #f4f4f4; padding: 10px; border-radius: 5px;">
-- Скрыть интерфейс Game Guardian
gg.setVisible(false)
-- Ваш следующий код
gg.toast("Game Guardian успешно скрыт")
            </pre>
			<h3>Пример использования `gg.setRanges`:</h3>
            <p><strong>Описание:</strong> <code>gg.setRanges</code> задает область памяти для поиска значений.</p>
            <p><strong>Пример:</strong></p>
            <pre style="background-color: #f4f4f4; padding: 10px; border-radius: 5px;">
-- Установить основной регион
gg.setRanges(gg.REGION_ANONYMOUS) -- Устанавливаем Анонимную память
-- Ваш следующий код
gg.toast("Регион установлен: Анонимная память")
            </pre>
			<h3>Пример использования `gg.setRanges` с кастомными регионами:</h3>
            <p><strong>Описание:</strong> <code>gg.setRanges</code> выбирает несколько областей памяти (например, C-ALLOC и C-DATA).</p>
            <p><strong>Пример:</strong></p>
            <pre style="background-color: #f4f4f4; padding: 10px; border-radius: 5px;">
-- Установить кастомные регионы памяти
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_C_DATA)
-- Ваш следующий код
gg.toast("Регион установлен: C-ALLOC и C-DATA")
            </pre>
			<h3>Пример использования `gg.getResults`:</h3>
            <p><strong>Описание:</strong> <code>gg.getResults</code> получает данные результатов (количество).</p>
            <p><strong>Пример:</strong></p>
            <pre style="background-color: #f4f4f4; padding: 10px; border-radius: 5px;">
-- Получить результаты поиска
gg.searchNumber("4", gg.TYPE_DWORD) -- Выполняем поиск числа "4"
local results = gg.getResults(10) -- Получаем 10 найденных значений
gg.toast("Найдено " .. #results .. " результатов")
            </pre>
        <button onclick="hideInstruction()">Закрыть инструкцию</button>
    </div>

<div class="container">
    <!-- Ввод имени функции -->
    <input type="text" id="functionNameInput" placeholder="Введите название функции (например: myFunction)">
    <button onclick="setFunctionName()">Установить название функции</button>
    <br><br>

  

    <!-- Добавление главного меню -->
    <label for="mainMenuFunction">Введите название меню (например: OP):</label>
    <input type="text" id="mainMenuFunction" placeholder="Введите название меню">
    <button onclick="addMenu()">Добавить меню</button>
    <br><br>

    <!-- Кнопка настройки "Главного меню" -->
    <button onclick="setupMainMenu()">Настроить "Главное меню"</button>
    
    <div id="menuSettings" class="menu-options">
        <div class="menu-settings">
            <label for="menuFunctionCount">Количество функций:</label>
            <input type="number" id="menuFunctionCount" min="1" placeholder="Введите число">
        </div>

   <div class="menu-settings">
    <label for="menuAuthor">Автор меню:</label>
    <input type="text" id="menuAuthor" placeholder="Введите имя автора">

    <label for="menuText">Текст в меню:</label>
    <input type="text" id="menuText" placeholder="Введите текст для меню">
</div>

        <div class="menu-settings">
    <label for="menuType">Тип меню:</label>
    <select id="menuType">
        <option value="choice">Обычное меню (gg.choice)</option>
        <option value="multiChoice">Мультивыбор (gg.multiChoice)</option>
    </select>
</div>

        <div class="menu-settings">
    <label for="menuItemNames">Названия пунктов меню (через запятую):</label>
    <input type="text" id="menuItemNames" placeholder="Пример: Взлом патронов, Вода, Земля">
</div>
<div class="menu-settings">
    <label for="menuFunctionNames">Названия функций (через запятую):</label>
    <input type="text" id="menuFunctionNames" placeholder="Пример: F1, F2, F3">
</div>
<div class="menu-settings">
    <label for="menuEmojis">Эмодзи пунктов меню (через запятую):</label>
    <input type="text" id="menuEmojis" placeholder="Пример: 🔥,🌊,🌍">
</div>

        <button onclick="generateMainMenu()">Сгенерировать главное меню</button>
    </div>
	 <!-- Кнопка настройки "Главного меню" -->
    <button onclick="setupMainF()">Настроить "Меню Функций"</button>
	<div class="menu-settings">
	<div id="menuSettingss" class="menu-options">
        <div class="menu-settings">
    <label for="subMenuFunctionName">Название подменю/функции:</label>
    <input type="text" id="subMenuFunctionName" placeholder="Введите название функции подменю (например, OP)">
</div>
<div class="menu-settings">
    <label for="subMenuItemNames">Названия пунктов подменю (через запятую):</label>
    <input type="text" id="subMenuItemNames" placeholder="Пример: Настройка1, Настройка2">
</div>
<div class="menu-settings">
    <label for="subMenuFunctions">Названия вызываемых функций из подменю (через запятую):</label>
    <input type="text" id="subMenuFunctions" placeholder="Пример: SubOp1, SubOp2">
</div>
<div id="drawer">
        <button onclick="toggleEmojiMenu()">Емодзi для функцій</button>
        
        <div id="emojiMenu" style="display: none;"></div>
    </div>
<!-- повторюйте для кожної функції -->
 <div class="menu-settings">
        <label for="menuStyle">Стиль меню:</label>
        <select id="menuStyle">
            <option value="normal">1. Обычный</option>
            <option value="circle">2. Круг</option>
        </select>
    </div>
	<div class="menu-settings">
        <label for="functionStyle">Стиль функций:</label>
        <select id="functionStyle">
            <option value="default">Обычный</option>
            <option value="brackets">『 ➱ 』</option>
            <option value="arrow">➤</option>
            <option value="bars">▁▂▃ (начало) ▃▂▁ (конец)</option>
        </select>
    </div>

<button onclick="generateSubMenu()">Сгенерировать подменю/функцию</button>
</div>
    <h2>Настройка вашей функции</h2>
	    <!-- Невидимость GG -->
    <div class="functions">
    <div class="function">
        <input type="checkbox" id="hideGG">
        <label for="hideGG">Скрыть Game Guardian (gg.setVisible(false))</label>
    </div>
	<div class="function">
        <input type="checkbox" id="usePrimaryRegion">
        <label for="primaryRegion">Выберите основной регион:</label>
        <select id="primaryRegion" disabled>
        <option value="gg.REGION_ANONYMOUS">Анонимная память</option>
        <option value="gg.REGION_C_ALLOC">C-ALLOC</option>
        <option value="gg.REGION_C_BSS">C-BSS</option>
        <option value="gg.REGION_C_DATA">C-DATA</option>
        <option value="gg.REGION_CODE_APP">Код приложения</option>
        <option value="gg.REGION_CODE_SYS">Код системы</option>
        <option value="gg.REGION_JAVA_HEAP">Java Heap</option>
        <option value="gg.REGION_STACK">Стек</option>
        <option value="gg.REGION_VIDEO">Видео</option>
        <option value="gg.REGION_OTHER">Другое</option>
        <option value="gg.REGION_BAD">Неиспользуемая память</option>
    </select>
</div>
<div class="function">
    <label>Кастомные регионы (максимум 3):</label>
    <div id="customRegions">
        <label for="customRegion1">Регион 1:</label>
        <select id="customRegion1">
            <option value="">Не выбран</option>
            <option value="gg.REGION_ANONYMOUS">Анонимная память</option>
            <option value="gg.REGION_C_ALLOC">C-ALLOC</option>
            <option value="gg.REGION_C_BSS">C-BSS</option>
            <option value="gg.REGION_C_DATA">C-DATA</option>
            <option value="gg.REGION_CODE_APP">Код приложения</option>
            <option value="gg.REGION_CODE_SYS">Код системы</option>
            <option value="gg.REGION_JAVA_HEAP">Java Heap</option>
            <option value="gg.REGION_STACK">Стек</option>
            <option value="gg.REGION_VIDEO">Видео</option>
            <option value="gg.REGION_OTHER">Другое</option>
            <option value="gg.REGION_BAD">Неиспользуемая память</option>
        </select>

        <label for="customRegion2">Регион 2:</label>
        <select id="customRegion2">
            <option value="">Не выбран</option>
            <option value="gg.REGION_ANONYMOUS">Анонимная память</option>
            <option value="gg.REGION_C_ALLOC">C-ALLOC</option>
            <option value="gg.REGION_C_BSS">C-BSS</option>
            <option value="gg.REGION_C_DATA">C-DATA</option>
            <option value="gg.REGION_CODE_APP">Код приложения</option>
            <option value="gg.REGION_CODE_SYS">Код системы</option>
            <option value="gg.REGION_JAVA_HEAP">Java Heap</option>
            <option value="gg.REGION_STACK">Стек</option>
            <option value="gg.REGION_VIDEO">Видео</option>
            <option value="gg.REGION_OTHER">Другое</option>
            <option value="gg.REGION_BAD">Неиспользуемая память</option>
        </select>

        <label for="customRegion3">Регион 3:</label>
        <select id="customRegion3">
            <option value="">Не выбран</option>
            <option value="gg.REGION_ANONYMOUS">Анонимная память</option>
            <option value="gg.REGION_C_ALLOC">C-ALLOC</option>
            <option value="gg.REGION_C_BSS">C-BSS</option>
            <option value="gg.REGION_C_DATA">C-DATA</option>
            <option value="gg.REGION_CODE_APP">Код приложения</option>
            <option value="gg.REGION_CODE_SYS">Код системы</option>
            <option value="gg.REGION_JAVA_HEAP">Java Heap</option>
            <option value="gg.REGION_STACK">Стек</option>
            <option value="gg.REGION_VIDEO">Видео</option>
            <option value="gg.REGION_OTHER">Другое</option>
            <option value="gg.REGION_BAD">Неиспользуемая память</option>
        </select>
    </div>
    <div class="functions">
        <!-- gg.clearResults -->
        <div class="function">
            <input type="checkbox" id="clearResults">
            <label for="clearResults">gg.clearResults()</label>
        </div>

        <!-- gg.alert -->
        <div class="function">
            <input type="checkbox" id="alert">
            <label for="alert">gg.alert()</label>
            <input type="text" id="alertMessage" placeholder="Введите сообщение для gg.alert">
        </div>
<div class="function">
    <label for="alertPlacement">Розташування gg.alert:</label>
    <select id="alertPlacement">
        <option value="start">На початку</option>
        <option value="end">У кінці</option>
    </select>
</div>
<!-- gg.toast -->
<div class="function">
    <input type="checkbox" id="toast">
    <label for="toast">gg.toast()</label>
    <input type="text" id="toastMessage" placeholder="Введите сообщение для gg.toast">
</div>

<div class="function">
    <label for="toastPlacement">Розташування gg.toast:</label>
    <select id="toastPlacement">
        <option value="start">На початку</option>
        <option value="end">У кінці</option>
    </select>
</div>

        <!-- gg.searchNumber -->
<div class="function">
    <input type="checkbox" id="searchNumber">
    <label for="searchNumber">gg.searchNumber()</label>
    <input type="text" id="searchValue" placeholder="Введите значение для поиска">
    <select id="searchType">
        <option value="gg.TYPE_FLOAT">Float</option>
        <option value="gg.TYPE_DWORD">Dword</option>
    </select>
</div>
<!-- gg.getResults -->
<div class="function">
    <input type="checkbox" id="getResults">
    <label for="getResults">gg.getResults()</label>
    <input type="number" id="resultsCount" placeholder="Введите количество результатов" min="1">
</div>
<!-- gg.refineNumber -->
<div class="function">
    <input type="checkbox" id="refineNumber">
    <label for="refineNumber">gg.refineNumber()</label>
    <input type="text" id="refineValue" placeholder="Введите значение для уточнения">
    <select id="refineType">
        <option value="gg.TYPE_FLOAT">Float</option>
        <option value="gg.TYPE_DWORD">Dword</option>
    </select>
</div>
        <!-- Обычная замена -->
        <div class="function">
    <input type="checkbox" id="editAll">
    <label for="editAll">Обычная замена (gg.editAll)</label>
    <input type="text" id="editValue" placeholder="Введите значение для замены">
    <select id="editType">
        <option value="gg.TYPE_FLOAT">Float</option>
        <option value="gg.TYPE_DWORD">Dword</option>
    </select>
</div>

        <!-- Замена через ввод значений -->
        <div class="function">
            <input type="checkbox" id="replaceInput">
            <label for="replaceInput">Замена через ввод значений (диапазон, тип)</label>
            <input type="text" id="rangeMin" placeholder="Минимальное значение">
            <input type="text" id="rangeMax" placeholder="Максимальное значение">
            <input type="text" id="defaultPromptValue" placeholder="Значение по умолчанию">
            <select id="replaceType">
                <option value="gg.TYPE_FLOAT">Float</option>
                <option value="gg.TYPE_DWORD">Dword</option>
            </select>
        </div>

        <!-- Замена через колёсико -->
        <div class="function">
            <input type="checkbox" id="editWheel">
            <label for="editWheel">Замена через "колёсико" (множитель, диапазон, тип)</label>
            <input type="text" id="wheelMultiplier" placeholder="Введите множитель (например: 2)">
            <input type="text" id="wheelMin" placeholder="Минимальное значение">
            <input type="text" id="wheelMax" placeholder="Максимальное значение">
            <select id="wheelType">
                <option value="gg.TYPE_FLOAT">Float</option>
                <option value="gg.TYPE_DWORD">Dword</option>
            </select>
        </div>
		<div class="functions">
    <!-- gg.freeze -->
    <div class="function">
        <input type="checkbox" id="freezeValues">
        <label for="freezeValues">Заморозить значения</label>
        <input type="text" id="freezeValue" placeholder="Значение для заморозки (например: 100)">
    </div>
	<div class="function">
        <input type="checkbox" id="editViaForLoop">
        <label for="editViaForLoop">Замена через for (с использованием result list)</label>
        <input type="text" id="forLoopValue" placeholder="Введите значение для замены (например: 1000000)">
    </div>
	<!-- Сохранение значений -->
<div class="function">
    <input type="checkbox" id="saveValues">
    <label for="saveValues">Сохранить значения (gg.addListItems)</label>
</div>
    </div>
<div class="useful-functions">
    <!-- Основная кнопка -->
    <div class="useful-functions">
    <!-- Основная кнопка -->
    <button onclick="toggleUsefulFunctions()">ПОЛЕЗНЫЕ ФУНКЦИИ</button>
    
    <!-- Скрытый список полезных функций -->
    <div id="usefulFunctionsList" style="display: none; margin-top: 10px; padding: 10px; border: 1px solid #ccc; background-color: #f9f9f9;">
        <button onclick="generateSelectMemoryFunction()">ВЫБОР РЕГИОНОВ</button>
        <button onclick="generatePasswordFunction()">СОЗДАНИЕ ПАРОЛЯ</button>

        <!-- Контейнер для сгенерированного кода -->
        <div id="generatedCodeContainer" style="display: none; margin-top: 10px;">
            <h3>Сгенерированный код:</h3>
            <textarea id="generatedCodeArea" style="width: 100%; height: 150px; padding: 10px; font-family: monospace;" readonly></textarea>
            <button onclick="copyGeneratedCode()">Копировать код</button>
            <button onclick="deleteLastFunction()">Удалить последнюю добавленную функцию</button>
            <button onclick="restoreLastDeletedFunction()">Восстановить последнюю удалённую</button>
        </div>
    </div>
</div>
</div>
    <h2>Сгенерированный Lua-код</h2>
    <div id="output" class="code-box">// Здесь появится сгенерированный Lua-код</div>

    <!-- Кнопки для выполнения действий -->
    <button onclick="generateScript()">Сгенерировать</button>
    <button onclick="downloadScript()">Скачать</button>
<button onclick="removeLastAddedFunction()">Удалить последнюю добавленную функцию</button>
<button onclick="restoreLastRemovedFunction()">Восстановить последнюю удалённую</button>
	
</div>

<script>
let generatedFunctions = [];
    let allFunctions = ""; // Все сгенерированные функции
    let mainMenuName = "HM"; // По умолчанию имя главного меню
	let functionName = "myFunction";
    let mainMenuCode = "";
	let allFunctionsList = []; // Список всех добавленных функций
	let deletedFunctions = [];
	// Функция для показа/скрытия списка "ПОЛЕЗНЫЕ ФУНКЦИИ"
// Показ/скрытие списка "ПОЛЕЗНЫЕ ФУНКЦИИ"
function toggleUsefulFunctions() {
    const functionsList = document.getElementById('usefulFunctionsList');
    functionsList.style.display = (functionsList.style.display === 'none' || functionsList.style.display === '') 
        ? 'block' : 'none';
}

// Генерация функции выбора региона памяти
function generateSelectMemoryFunction() {
    const functionCode = `
function SelectMemory()
    local UserRanges = gg.choice({"CA", "O", "A"}, 0, "Select Memory Ranges")
    if UserRanges == nil then
        gg.alert("Please Select Memory Ranges")
        SelectMemory()
    end
    if UserRanges == 1 then
        gg.setRanges(gg.REGION_C_ALLOC)
    end
    if UserRanges == 2 then
        gg.setRanges(gg.REGION_OTHER)
    end
    if UserRanges == 3 then
        gg.setRanges(gg.REGION_ANONYMOUS)
    end
end`;

    addFunctionToContainer(functionCode);
}

// Генерация функции создания пароля
function generatePasswordFunction() {
    const functionCode = `

-- Создать переменную для ввода пользователя
local password = gg.prompt({"Enter Password"}, {[1] = '0'}, {[1] = 'text'})

-- Проверяем введённый пароль
if password[1] == "1028371" then
    gg.alert("Correct Password")
else
    gg.alert("Incorrect Password")
end`;

    // Додаємо згенеровану функцію до блоку з кодом
    addFunctionToContainer(functionCode);
    alert("Функция пароля добавлена.");
}
// Удаляем последнюю добавленную функцию
function deleteLastFunction() {
    if (generatedFunctions.length === 0) {
        alert("Нет добавленных функций для удаления.");
        return;
    }

    // Удаляем последнюю функцию и сохраняем её в массив удалённых
    const lastFunction = generatedFunctions.pop();
    deletedFunctions.push(lastFunction);

    updateCodeContainer();
}

// Восстановление последней удалённой функции
function restoreLastDeletedFunction() {
    if (deletedFunctions.length === 0) {
        alert("Нет удалённых функций для восстановления.");
        return;
    }

    // Перемещаем функцию из удалённых в добавленные
    const restoredFunction = deletedFunctions.pop();
    generatedFunctions.push(restoredFunction);

    updateCodeContainer();
    alert("Последняя удалённая функция восстановлена.");
}

// Добавляем функцию в контейнер
function addFunctionToContainer(functionCode) {
    generatedFunctions.push(functionCode);
    updateCodeContainer();
    alert("Функция добавлена.");
}

// Обновляем содержимое текстового поля с функциями
function updateCodeContainer() {
    const codeContainer = document.getElementById('generatedCodeContainer');
    const codeArea = document.getElementById('generatedCodeArea');

    // Если функции нет, скрываем блок с кодом
    if (generatedFunctions.length === 0) {
        codeContainer.style.display = 'none';
        codeArea.value = '';
    } else {
        codeContainer.style.display = 'block';
        codeArea.value = generatedFunctions.join('\n\n');
    }
}

// Копируем код из текстового поля
function copyGeneratedCode() {
    const codeArea = document.getElementById('generatedCodeArea');
    codeArea.select();
    document.execCommand('copy');
    alert("Код скопирован в буфер обмена!");
}
	function showInstruction() {
    const instructionBlock = document.getElementById('instructionBlock');
    instructionBlock.style.display = 'block'; // Показываем блок инструкции
}

function hideInstruction() {
    const instructionBlock = document.getElementById('instructionBlock');
    instructionBlock.style.display = 'none'; // Скрываем блок инструкции
}
	document.getElementById("usePrimaryRegion").addEventListener("change", function () {
        // Проверка: если чекбокс включен — разблокировать, иначе — заблокировать
        const primaryRegionSelect = document.getElementById("primaryRegion");
        primaryRegionSelect.disabled = !this.checked;
    });
document.getElementById('subMenuFunctions').addEventListener('input', function() {
    var functions = this.value.split(',');
    var emojiMenu = document.getElementById('emojiMenu');

    emojiMenu.innerHTML = '';
    
    functions.forEach(function(func, index) {
        var label = document.createElement('label');
        label.for = "functionEmojis"+(index+1);
        label.innerHTML = "Емодзi для "+func.trim()+": ";

        var select = document.createElement('select');
        select.id = "functionEmojis"+(index+1);
    
        var emojis = ["✅", "⚙️", "⭐", "💡", "🔑", "🔍", "👍", "⛔", "⚡", "💥", "🆘", "🆕", "🆙", "🔄","🤑", "❄️", "☄️", "🔥", "🌪️", "🌀", "🪐", "📌", "🔒", "🛡️", "📁", "🔨", "👑", "🌍"];
        
        emojis.forEach(function(emoji) {
            var option = document.createElement('option');
            option.value = emoji;
            option.innerHTML = emoji;
            select.appendChild(option);
        });

        emojiMenu.appendChild(label);
        emojiMenu.appendChild(select);
    });
});

function toggleEmojiMenu() {
    var menu = document.getElementById('emojiMenu');
    menu.style.display = (menu.style.display === "none") ? "block" : "none";
}
  function setupMainF() {
      document.getElementById("menuSettingss").classList.toggle("active"); // Показать настройки меню
    }

function generateSubMenu() {
    // отримання даних користувача
    const functionName = document.getElementById("subMenuFunctionName").value.trim() || "Підменю";
    const itemNames = document.getElementById("subMenuItemNames").value.split(",").map(i => i.trim());
    const functionCalls = document.getElementById("subMenuFunctions").value.split(",").map(f => f.trim());
    let emojis = [];
    for(let i = 1; i <= functionCalls.length; i++) {
    emojis.push(document.getElementById(`functionEmojis${i}`).value);
}
    const menuStyle = document.getElementById("menuStyle").value;
    const functionStyle = document.getElementById("functionStyle").value;

    // перевірка правильності даних
    if (itemNames.length !== functionCalls.length) {
        alert("Помилка: Кількість пунктів та функцій повинна співпадати!");
        return;
    }

    // створення коду меню
    let menuCode = `-- Функція: ${functionName}\nfunction ${functionName}()\n`;
    menuCode += "  menu = gg.choice({\n";

    // генерація пунктів меню з урахуванням стилю функцій
     itemNames.forEach((item, index) => {
        const emoji = emojis[index] || ""; // якщо емодзі немає, просто залишимо поле пустим
        let styledItem = item;

        // застосування стилю до пунктів
        switch (functionStyle) {
            case "brackets":
                styledItem = `『 ➱ ${item} 』`;
                break;
            case "arrow":
                styledItem = `➤ ${item}`;
                break;
            case "bars":
                styledItem = `▁▂▃ ${item} ▃▂▁`;
                break;
            default:
                styledItem = `${item}`; // простий стиль
        }

        menuCode += `    "${emoji} ${styledItem}",\n`;
    });

    // додання пункту "Вихід"
    menuCode += `    "❌ Вийти зі скрипта"\n  })`;

    // додання коду закриття меню
    if (menuStyle === "normal") {
        menuCode += `, nil, "Виберіть пункт"\n`;
    } else if (menuStyle === "circle") {
        menuCode += `, 0, "Виберіть пункт"\n`;
    }

    menuCode += `  if menu == nil then return end\n`; // перевірка на скасування вибору

    // логіка виклику функцій
    itemNames.forEach((_, index) => {
        const funcName = functionCalls[index] || `SubFunction${index+1}`;
        menuCode += `  if menu == ${index + 1} then ${funcName}() end\n`;
    });

    // логіка виходу з меню
   menuCode += `  if menu == ${itemNames.length + 1} then gg.toast("Вихід зі скрипта") gg.exit() end\n`;

    menuCode += "end\n"; // Закінчуємо функцію

    // Додаємо готову функцію в список
    allFunctionsList.push(menuCode);
 
    // Оновлюємо загальний Lua-код
    refreshAllFunctions();
}
function generateMainMenuWithFunctions() {
    const mainMenuFunctionName = document.getElementById("mainMenuFunctionName").value.trim() || "HM"; // Название главного меню
    const itemNames = document.getElementById("mainMenuItemNames").value.split(",").map(i => i.trim()); // Названия пунктов главного меню
    const functionNames = document.getElementById("mainMenuFunctions").value.split(",").map(f => f.trim()); // Функции, вызываемые пунктами
    const menuEmojis = document.getElementById("mainMenuEmojis").value.split(",").map(e => e.trim()); // Эмодзи для главного меню

    let menuCode = `function ${mainMenuFunctionName}()\n`;
    menuCode += "  menu = gg.choice({\n";

    // Создаем пункты главного меню
    for (let i = 0; i < itemNames.length; i++) {
        const emoji = menuEmojis[i] || ""; // Если нет эмодзи для пункта, игнорируем
        const itemName = itemNames[i] || `Пункт ${i + 1}`;
        menuCode += `    "${emoji} ${itemName}",\n`; // Вставляем название пункта с эмодзи
    }

    menuCode += `  }, nil, "Выберите действие")\n`;
    menuCode += `  if menu == nil then return end\n`;

    // Добавляем выполнение соответствующих функций
    for (let i = 0; i < functionNames.length; i++) {
        const funcName = functionNames[i] || `F${i + 1}`;
        menuCode += `  if menu == ${i + 1} then ${funcName}() end\n`;
    }

    menuCode += "end\n";

    // Добавляем готовую функцию в список
    allFunctionsList.push(menuCode);

    // Обновляем общий Lua-код
    refreshAllFunctions();
}

    // Установка имени функции
    function setFunctionName() {
        const input = document.getElementById("functionNameInput").value.trim();
        functionName = input || "myFunction";
        alert(`Название функции установлено: ${functionName}`);
    }

     // Устанавливаем название главного меню
    function addMenu() {
      const menuName = document.getElementById("mainMenuFunction").value.trim();
      mainMenuName = menuName || "HM";
      const mainMenu = `function main()\n  ${mainMenuName}()\nend\n`;
      allFunctions = mainMenu + allFunctions;
      document.getElementById("output").textContent = allFunctions;
    }

   // Настройка главного меню
    function setupMainMenu() {
      document.getElementById("menuSettings").classList.toggle("active"); // Показать настройки меню
    }

    // Генерация главного меню
    function generateMainMenu() {
    // Получаем настройки от пользователя
    const functionCount = parseInt(document.getElementById("menuFunctionCount").value) || 1; // Количество пунктов меню
    const author = document.getElementById("menuAuthor").value.trim() || "Автор"; // Имя автора
    const menuText = document.getElementById("menuText").value.trim() || "By Lambo"; // Если поле пустое, используем "By Lambo"
    const menuType = document.getElementById("menuType").value; // Тип меню (choice/multiChoice)
    const itemNames = document.getElementById("menuItemNames").value.split(",").map(i => i.trim()); // Названия пунктов меню
    const functionNames = document.getElementById("menuFunctionNames").value.split(",").map(f => f.trim()); // Названия функций
    const menuEmojis = document.getElementById("menuEmojis").value.split(",").map(e => e.trim()); // Эмодзи для пунктов меню

    // Создаём код меню
    let menuCode = `-- Автор: ${author}\nfunction ${mainMenuName}()\n`;
    menuCode += menuType === "multiChoice" ? "  menu = gg.multiChoice({\n" : "  menu = gg.choice({\n";

    // Генерируем пункты меню
    for (let i = 0; i < functionCount; i++) {
        const emoji = menuEmojis[i] || ""; // Если нет эмодзи, оставляем пустую строку
        const itemName = itemNames[i] || `Пункт ${i + 1}`; // Если название пункта не указано, генерируем название
        menuCode += `    "${emoji} ${itemName}",\n`; // Формат пункта: "🔥 Название"
    }

    // Добавляем пункт "Выход"
    menuCode += `    "❌ Выйти из скрипта"\n`; // Последний пункт меню

    // Текст меню
    const formattedMenuText = `${author} | ${menuText}`; // Комбинируем автора и дополнительный текст

    // Завершаем создание меню
    menuCode += `  }, nil, "${formattedMenuText}")\n`; // Название меню наверху
    menuCode += `  if menu == nil then return end\n`; // Проверка, если пользователь ничего не выбрал

    // Логика вызова функций
    for (let i = 0; i < functionCount; i++) {
        const funcName = functionNames[i] || `F${i + 1}`; // Если функция не указана, назначаем ей имя по умолчанию
        menuCode += `  if menu == ${i + 1} then ${funcName}() end\n`; // Логика: if menu == 1 then функция()
    }

    // Логика для выхода из скрипта
    menuCode += `  if menu == ${functionCount + 1} then gg.toast("Выход из скрипта") gg.exit() end\n`;

    menuCode += "end\n"; // Конец функции меню

    // Добавляем сгенерированное меню в общий список функций
    allFunctionsList.push(menuCode);
    refreshAllFunctions(); // Обновляем весь Lua-код в выводе
}
    // Генерация Lua-кода
function generateScript(onlyReturn = false) {
    let script = `function ${functionName}()\n`;

    if (document.getElementById("hideGG").checked) {
        script += `  gg.setVisible(false)\n`;
    }
    if (document.getElementById("clearResults").checked) {
        script += `  gg.clearResults()\n`;
    }

    // Проверка и добавление вызова gg.alert в начале
    if (document.getElementById("alert").checked) {
        const alertMessage = document.getElementById("alertMessage").value.trim() || "Повідомлення!";
        const alertPlacement = document.getElementById("alertPlacement").value;

        if (alertPlacement === "start") {
            script += `  gg.alert("${alertMessage}")\n`;
        }
    }

    // Додаємо gg.toast або gg.alert на початку, якщо обрано
    if (document.getElementById("toast").checked) {
        const message = document.getElementById("toastMessage").value.trim() || "Скрипт запущен!";
        const placement = document.getElementById("toastPlacement").value;

        if (placement === "start") {
            script += `  gg.toast("${message}")\n`;
        }
    }

    // Работа с основным регионом (чекбокс и выбор)
    const usePrimaryRegion = document.getElementById("usePrimaryRegion").checked; // Проверяем, активен ли основной регион
    if (usePrimaryRegion) {
        const primaryRegion = document.getElementById("primaryRegion").value;
        if (primaryRegion) {
            script += `  gg.setRanges(${primaryRegion})\n`;
            script += `  gg.toast("Основной регион установлен!")\n`;
        }
    }

    // Работа с кастомными регионами
    const customRegion1 = document.getElementById("customRegion1").value;
    const customRegion2 = document.getElementById("customRegion2").value;
    const customRegion3 = document.getElementById("customRegion3").value;

    let customRegions = [];
    if (customRegion1) customRegions.push(customRegion1);
    if (customRegion2) customRegions.push(customRegion2);
    if (customRegion3) customRegions.push(customRegion3);

    if (customRegions.length > 0) {
        const customRegionCode = customRegions.join(" | "); // Объединяем выбранные регионы через |
        script += `  gg.setRanges(${customRegionCode})\n`;
        script += `  gg.toast("Кастомные регионы установлены!")\n`;
    }

   

    if (document.getElementById("searchNumber").checked) {
        const searchValue = document.getElementById("searchValue").value || "0"; // Значение для поиска
        const searchType = document.getElementById("searchType").value; // Тип поиска: Float или Dword
        script += `  gg.searchNumber("${searchValue}", ${searchType})\n`; // Генерация Lua-кода
    }
    if (document.getElementById("getResults").checked) {
        const resultsCount = document.getElementById("resultsCount").value || "1"; // Количество результатов по умолчанию — 1
        script += `  local results = gg.getResults(${resultsCount})\n`; // Генерация Lua-кода для получения результатов
        script += `  gg.toast("Получено результатов: " .. #results)\n`; // Уведомление об их количестве
    }
    if (document.getElementById("refineNumber").checked) {
        const refineValue = document.getElementById("refineValue").value || "0"; // Уточняемое значение
        const refineType = document.getElementById("refineType").value; // Выбранный тип данных (Float/Dword)
        script += `  gg.refineNumber("${refineValue}", ${refineType})\n`; // Генерация кода
    }
   if (document.getElementById("editAll").checked) {
     script += `  revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil))\n`; // Добавляем текущие результаты в список
        const editValue = document.getElementById("editValue").value.trim();
        const editType = document.getElementById("editType").value;

        // Перевіряємо, чи є введене значення
        if (editValue) {
            script += `  gg.editAll(${editValue}, ${editType})\n`;
        } else {
            alert("Введите значение для замены в gg.editAll!");
            return;
        }
    }

    // Замена через ввод значений (prompt)
    if (document.getElementById("replaceInput").checked) {
        const rangeMin = document.getElementById("rangeMin").value || "0";
        const rangeMax = document.getElementById("rangeMax").value || "0";
        const defaultPromptValue = document.getElementById("defaultPromptValue").value || "0";
        const valueType = document.getElementById("replaceType").value;
        script += `  local powerMenu = gg.prompt({"[${rangeMin};${rangeMax}]"}, {${defaultPromptValue}}, {"number"})\n`;
        script += `  if powerMenu == nil then\n`;
        script += `    gg.toast("Отмена")\n`;
        script += `    return\n`;
        script += `  end\n`;
        script += `  gg.editAll(powerMenu[1], ${valueType})\n`;
    }

    if (document.getElementById("editWheel").checked) {
        const multiplier = document.getElementById("wheelMultiplier").value || "1";
        const rangeMin = document.getElementById("wheelMin").value || "0";
        const rangeMax = document.getElementById("wheelMax").value || "0";
        const valueType = document.getElementById("wheelType").value;
        script += `  local powerMenu = gg.prompt({"[${rangeMin};${rangeMax}]"}, {"${multiplier}"}, {"number"})\n`;
        script += `  if powerMenu == nil or powerMenu[1] == "" then\n`;
        script += `    gg.toast("Отмена")\n`;
        script += `    return\n`;
        script += `  end\n`;
        script += `  local newValue = tonumber(powerMenu[1])\n`; 
        script += `  gg.editAll(newValue, ${valueType})\n`;
    }

    if (document.getElementById("freezeValues").checked) {
        const freezeValue = document.getElementById("freezeValue").value || "0";
        script += `  for i, v in ipairs(results) do\n`;
        script += `    results[i].value = ${freezeValue}\n`;
        script += `    results[i].freeze = true\n`;
        script += `  end\n`;
        script += `  gg.setValues(results)\n`;
        script += `  gg.addListItems(results)\n`;
        script += `  gg.toast("Значения заморожены: ${freezeValue}")\n`;
    }
    if (document.getElementById("saveValues").checked) {
        script += `  gg.addListItems(results)\n`; // Добавляем текущие результаты в список
        script += `  gg.toast("Результаты сохранены в пользовательский список.")\n`;
    }
// Додаємо gg.toast або gg.alert у кінці, якщо обрано
    if (document.getElementById("toast").checked) {
        const message = document.getElementById("toastMessage").value.trim() || "Скрипт завершён!";
        const placement = document.getElementById("toastPlacement").value;

        if (placement === "end") {
            script += `  gg.toast("${message}")\n`;
        }
    }
	if (document.getElementById("alert").checked) {
        const alertMessage = document.getElementById("alertMessage").value.trim() || "Повідомлення!";
        const alertPlacement = document.getElementById("alertPlacement").value;

        if (alertPlacement === "end") {
            script += `  gg.alert("${alertMessage}")\n`;
        }
    }
    script += `end\n`;

    allFunctionsList.push(script); // Обновляем список всех функций
    refreshAllFunctions(); // Обновляем итоговый Lua-код
    return script;
}
function refreshAllFunctions() {
    allFunctions = allFunctionsList.join("\n"); // Соединяем все функции из списка
    document.getElementById("output").textContent = allFunctions; // Отображаем результат
}

// Удаление последней функции
function removeLastAddedFunction() {
    if (allFunctionsList.length === 0) {
        alert("Нет функций для удаления.");
        return;
    }

    // Избегать удаления главного меню
    if (allFunctionsList.length === 0) {
        alert("Главное меню не может быть удалено.");
        return;
    }

    const lastFunction = allFunctionsList.pop();
    deletedFunctions.push(lastFunction);

    refreshAllFunctions();
    alert("Последняя добавленная функция удалена.");
}

// Восстановление последней удалённой функции
function restoreLastRemovedFunction() {
    if (deletedFunctions.length === 0) {
        alert("Нет удалённых функций для восстановления.");
        return;
    }

    // Берём последнюю удалённую функцию и добавляем её обратно в общий список
    const lastRemovedFunction = deletedFunctions.pop();
    allFunctionsList.push(lastRemovedFunction);

    // Обновляем общий Lua-код
    refreshAllFunctions();

    alert("Последняя удалённая функция восстановлена.");
}
    // Сброс всех полей ввода
    function resetInputs() {
        functionName = "myFunction";
        document.getElementById("functionNameInput").value = "";
        document.getElementById("clearResults").checked = false;
        document.getElementById("alert").checked = false;
        document.getElementById("alertMessage").value = "";
        document.getElementById("toast").checked = false;
        document.getElementById("toastMessage").value = "";
        document.getElementById("searchNumber").checked = false;
        document.getElementById("searchValue").value = "";
        document.getElementById("editAllSimple").checked = false;
        document.getElementById("editValue").value = "";
        document.getElementById("replaceInput").checked = false;
        document.getElementById("rangeMin").value = "";
        document.getElementById("rangeMax").value = "";
        document.getElementById("defaultPromptValue").value = "";
        document.getElementById("editWheel").checked = false;
        document.getElementById("wheelMultiplier").value = "";
        document.getElementById("wheelMin").value = "";
        document.getElementById("wheelMax").value = "";
        document.getElementById("wheelType").value = "gg.TYPE_FLOAT";
        document.getElementById("mainMenuFunction").value = "";
    }
	

    // Скачивание итогового Lua-кода
    function downloadScript() {
        const blob = new Blob([allFunctions], { type: "text/plain" });
        const link = document.createElement("a");
        link.href = URL.createObjectURL(blob);
        link.download = "script.lua";
        link.click();
    }
</script>

</body>
</html>
