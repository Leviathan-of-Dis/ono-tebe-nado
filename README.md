# Проект после исправления ошибок и обработки замечаний.

## Изменения

### HTML
1. Cекция cover-title изменена на заголовок h1.
2. Изменены уровни заголовков. 
3. Теги section изменены на div в секции about.
4. Убран лишний тег section из socials.   

### CSS
1. Фиксированные значения width и height у контентных и тектовых блоков удалены или изменены на связку max-width и width:100%
2. Position Absolute изменён на Reletive у Logo в Header
3. Класс cover-span удален. 
   Правила содержащиеся в нём были распределены по вновь созданому классу text position left и уже имеющимся text position right, center.
4. Создан новый класс footer social link заместо классов social VK, YouTube и Pinterest.

## Коментарии
Прошу обратить внимание на тот факт, что эталонная верстка в тестах на GitHub сильно отличается от макета в Figma.
Это привело к тому что моя изначальная верстка, провереная мной с помощью плагина Pixel Perfect, была мной переделана
на этапе первых тестов GitHub, так как не соответствовала эталону.


После подгонки верстки под эталон, прохождения тестов и ревью, осознания разности макета и эталона,  
а также бесполезности проделаной работы мне пришлось откатить изменения до комита с первоначальной версткой  
и создать от этого комита **_новую ветвь After-Review. В ней я исправил ошибки указаные в ревью.
Потом мне подсказали что вы получаете на проверку файлы только из ветки main, и вот все изменения здесь**_.

## [HTTPS ссылка на репозиторий](https://github.com/Leviathan-of-Dis/ono-tebe-nado.git)

  
