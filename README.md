# goit-markup-hw-05

1. - подчеркивание в хедере при ховере и фокусе (при помощи псевдокласса ::after)

2. +время перехода для всех интерактивных элементов (ссылки в хедере, контакты в хедере, иконки и
   лого, всплывающие окна)

«C4» В головній навігації, за допомогою псевдоелемента ::after, зроблено підкреслення посилання
поточної сторінки (на якій зараз знаходиться користувач).

«D8» Поява і приховування модального вікна анімовано за допомогою переходу з довільним ефектом,
наприклад scale або translate, і opacity.

Скрипт, який необхідно скопіювати і вставити у файл modal.js.

(() => { const refs = { openModalBtn: document.querySelector("[data-modal-open]"), closeModalBtn:
document.querySelector("[data-modal-close]"), modal: document.querySelector("[data-modal]"), };

refs.openModalBtn.addEventListener("click", toggleModal);
refs.closeModalBtn.addEventListener("click", toggleModal);

function toggleModal() { refs.modal.classList.toggle("is-hidden"); } })();
