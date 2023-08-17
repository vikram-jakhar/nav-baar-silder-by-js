let open = document.querySelector(".open"); //main button
let cross = document.querySelector(".cursor"); //x sign
let overlay = document.querySelector(".overlay"); //page
let sidebar = document.querySelector(".sidebar"); //sidebar

open.addEventListener("click", function () {
    if (sidebar.classList !== document.querySelector("show")) {
        sidebar.classList.add("show");
        open.classList.add("b1");
        overlay.style.display = "block";
    }
});

cross.addEventListener("click", function () {
    sidebar.classList.remove("show");
    open.classList.remove("b1");
    overlay.style.display = "none";
});

overlay.addEventListener("click", function () {
    sidebar.classList.remove("show");
    open.classList.remove("b1");
    overlay.style.display = "none";
});