# Java
<p>function calculateDiameter() {
    var radiusInput = document.getElementById("radius");
    var radius = parseFloat(radiusInput.value);
    if (isNaN(radius)) {
        document.getElementById("result").textContent = "Некорректный ввод. Пожалуйста, введите число.";
    } else {
        var diameter = 2 * radius;
        document.getElementById("result").textContent = "Диаметр окружности равен: " + diameter;
    }
}</p>
