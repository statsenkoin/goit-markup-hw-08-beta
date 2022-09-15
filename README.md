# goit-markup-hw-07

    base/ — включает глобальные стили, такие как сброс стилей, типография, цвета и т.д.
    components/ — содержит отдельные компоненты с отдельным файлом .scss для каждого из них.
    layout/ — содержит стили для основных компонентов макета, таких как хедер, футер, навигация и т.д.
    pages/ — содержит стили, специфичные для отдельных страниц, если это необходимо.
    themes/ — стили для разных тем.
    utils/ — глобальные миксины, функции, вспомогательные селекторы и т.д.
    vendors/ — стили, миксины и прочее от третьих сторон
    main.scss — выходной файл, в котором объединяются все стили.

        // main.scss
    @import 'base/module';
    @import 'components/module';
    @import 'layout/module';
    @import 'pages/module';
    @import 'themes/module';
    @import 'utils/module';
    @import 'vendors/module';

    transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);

    transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);

    transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1),     background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);

    transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1),
    border 250ms cubic-bezier(0.4, 0, 0.2, 1);

    transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1),
    background-color 250ms cubic-bezier(0.4, 0, 0.2, 1),
    box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1);

    transition: box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1);

    transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1);

    transition: opacity 250ms cubic-bezier(0.4, 0, 0.2, 1);

    transition: border 250ms cubic-bezier(0.4, 0, 0.2, 1);

    transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1);

    transition: border 250ms cubic-bezier(0.4, 0, 0.2, 1),
    background-color 250ms cubic-bezier(0.4, 0, 0.2, 1),
    border-width 250ms cubic-bezier(0.4, 0, 0.2, 1);
