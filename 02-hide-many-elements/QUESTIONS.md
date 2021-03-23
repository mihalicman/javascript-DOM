# DOM Atomic 02: Hide Many Elements

## Questions

---

> How did you go about selecting the DOM elements to hide? Describe the "contract" for that function.

Jums jāizmanto .getElementsByClassName (). Laukā () jūs norādāt, kuru klasi vēlaties kolekcionēt. Tas atgriezīs kolekciju, un jums ir jāpārskata kolekcija, lai paslēptu visus tajā esošos elementus.

---

> Describe how you were able to hide each element. Were you able to do it as one operation, or did you use a loop of some kind? Describe the "contracts" that were utilized to accomplish your goal.

Lai pārvietotos pa savāktajiem elementiem, tika izmantota cilpa. Bija jānorāda cikla lielums un kas jādara katram klases atribūtam.