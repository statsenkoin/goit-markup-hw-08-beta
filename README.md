# goit-markup-hw-08

    base/ — включает глобальные стили, такие как сброс стилей, типография, цвета и т.д.
    components/ — содержит отдельные компоненты с отдельным файлом .scss для каждого из них.
    layout/ — содержит стили для основных компонентов макета, таких как хедер, футер, навигация и т.д.
    pages/ — содержит стили, специфичные для отдельных страниц, если это необходимо.
    themes/ — стили для разных тем.
    utils/ — глобальные миксины, функции, вспомогательные селекторы и т.д.
    vendors/ — стили, миксины и прочее от третьих сторон
    main.scss — выходной файл, в котором объединяются все стили.

    480/768/1200
    normalize
    fonts
    vars
    buttons
    @media - web-kit

    // @media screen and (min-width: 480px) {
    //   width: 480px;
    // }
    // @media screen and (min-width: 768px) {
    //   width: 768px;
    // }
    // @media screen and (min-width: 1200px) {
    //   width: 1200px;
    //   padding-block: 94px;
    // }

        <picture>
            <source srcset="" media="" sizes="" type="" />
            <source srcset="" media="" sizes="" type="" />
            <img src="" alt="" />
        </picture>
        <picture>
            <source srcset="photo.webp 1x, photo@2x.webp 2x"type="image/webp" />
            <source srcset="photo.jpg 1x, photo@2x.jpg 2x"type="image/jpeg" />
            <img src="photo.jpg" alt="Кіт" />
        </picture>
        <img
            srcset="photo-300.jpg 300w, photo-600.jpg 600w,photo-1200.jpg 1200w"
            sizes="300px"
            src="photo-300.jpg"
            alt="Опис зображення для всіх версій"
        />

         <picture>
            <source
                srcset="photo.webp 1x, photo@2x.webp 2x"
                media=""
                sizes="370px"
                type="image/webp" />
            <source
                srcset="photo.jpg 1x, photo@2x.jpg 2x"
                media=""
                sizes="370px"
                type="image/jpeg" />
            <img
                src="./images/activity/desktop-app-370x294.jpg"
                alt="Десктопні додатки"
            />
        </picture>

    sizes="(min-width: 900px) 600px, (min-width: 600px) 300px, 100vw"
