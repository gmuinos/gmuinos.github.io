# Iced Coffee Calculator
## Subtitle test directly here

<label for="coffeeAmount">
How much liquid coffee do you want? (in milliliters)
</label>
<br><br>

<input type="number" id="coffeeAmount" placeholder="Final coffee in ml">
<button onclick="calculateCoffee()">Let the magic happen</button>

<p id="result"></p>

<script>
function calculateCoffee() {
    const final = parseFloat(document.getElementById("coffeeAmount").value);

    const beans = 65 * final / 1000;
    const ice = final * 0.4;
    const bloom = beans * 2.5;
    const rest = final - ice - bloom;
    const totalWater = final * 0.6;

    const output = `
    You need to grind ${beans.toFixed(2)} grams of coffee beans, prepare 
    ${ice.toFixed(2)} grams of ice, and boil a total of
    ${totalWater.toFixed(2)} grams of water.<br><br>

    Use ${bloom.toFixed(2)} grams of water for the bloom and
    ${rest.toFixed(2)} grams of water for the rest.
    `;

    document.getElementById("result").innerHTML = output;
}
</script>
