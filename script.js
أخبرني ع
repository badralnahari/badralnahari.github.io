
// Language Toggle
const langToggle = document.getElementById("langToggle");

let currentLanguage = "ar";

langToggle.addEventListener("click", function () {

    if (currentLanguage === "ar") {
        currentLanguage = "en";
    } else {
        currentLanguage = "ar";
    }

    document.documentElement.lang = currentLanguage;

    document.documentElement.dir =
        currentLanguage === "ar" ? "rtl" : "ltr";

    document.querySelectorAll("[data-ar]").forEach(function (element) {

        element.textContent =
            element.getAttribute("data-" + currentLanguage);

    });

    langToggle.textContent =
        currentLanguage === "ar" ? "English" : "العربية";

});
