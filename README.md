# goit-markup-hw-05













«D8» Поява і приховування модального вікна анімовано за допомогою переходу з довільним ефектом, наприклад scale або translate, і opacity.

Відкриття/закриття модального вікна
Модальне вікно з формою заявки відкривається по натисканню на кнопку "Замовити послугу". Для того щоб скрипт спрацював, необхідно додати до розмітки спеціальні атрибути, за якими скрипт шукає елементи:

data-modal-open - на кнопку відкриття модального вікна.
data-modal-close - на кнопку закриття модального вікна.
data-modal - на бекдроп модального вікна.
Після чого, перед закриваючим тегом body додати тег script з посиланням на файл скрипту для модально вікна. Можна подивитися відео-інструкцію.

<body>
  <!-- Вся твоя розмітка, включно з розміткою модалки -->

  <!-- Ставимо перед закриваючим тегом body -->
  <script src="./js/modal.js"></script>
</body>

Скрипт, який необхідно скопіювати і вставити у файл modal.js.

(() => {
  const refs = {
    openModalBtn: document.querySelector("[data-modal-open]"),
    closeModalBtn: document.querySelector("[data-modal-close]"),
    modal: document.querySelector("[data-modal]"),
  };

  refs.openModalBtn.addEventListener("click", toggleModal);
  refs.closeModalBtn.addEventListener("click", toggleModal);

  function toggleModal() {
    refs.modal.classList.toggle("is-hidden");
  }
})();




«A2» Вихідний код відформатований за допомогою Prettier



Налаштуй GitHub Pages і додай посилання на живу сторінку в шапку GitHub-репозиторія.

Не вдається поставити тінь в портфоліо на карточки на focus не можу знайти проблеми, HELP