# goit-markup-hw-05

Подчеркивание выбранной страницы(код элемента): .link.carrent::after { content: ''; display: block;
position: absolute; width: 100%; height: 4px; bottom: 0; right: 0;

border-radius: 4px; background: #2196f3; }

- в макете стоит так что налезает на бордер хедера. У меня же он стоит над бордером. Тоесть есть
  зазор, очень хорошо видно на главной странице. Это является ошибкой? Если да то как исправить?
  Т.к. бордер стоит на предке(section-header), а само подчеркивание(::after) стоит на ссылке
  (.link.carrent). Я сделал смещение эмелента на -1рх(шырину рамки хедера), но тогда визуально оно
  немного налезает на картинку, как лучше оставить?
