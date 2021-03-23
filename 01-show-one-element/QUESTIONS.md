# DOM Atomic 01: Show One Element

## Questions

---

> If you click the link to reveal more text and then refresh the page, does the text remain revealed, or is it hidden again? Why?

Teksta slēpšanu nosaka notikums, kad noklikšķināt uz saites. Atsvaidzinot lapu, tā tiek atjaunota stāvoklī, kurā šis klikšķis nav noticis, tāpēc teksts joprojām tiek paslēpts.

---

> Remove `window.addEventListener("load", function(){` (and the closing `})`) from **global.js**. Does the link still reveal the text? What is the purpose of this code that you've removed?

Būtībā jūs noņemat notikumu, kas ielādē visu, kas tam seko. Šajā gadījumā window.onload ielādē visu JS, kad lapa ir pabeigta. Bez tā tā ir tikai nenosauktā funkcija.

---

> Describe the the `addEventListener` method. (Remember that there is a specific, technical, methodical way to describe methods. Your reply should match that format.)

Jums jāpasaka, kuru notikumu tā klausās un kas jādara, kad notikums notiek.
