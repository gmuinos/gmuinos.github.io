<h3>Iced Coffee Calculator</h3>

<label for="coffeeAmount">
How much liquid coffee do you want? (milliliters)
</label>
<br><br>

<input type="number" id="coffeeAmount" placeholder="Enter ml">
<button onclick="calculateCoffee()">Calculate</button>

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
    You need to prepare ${beans.toFixed(2)} grams of coffee beans,
    ${ice.toFixed(2)} gr of ice, and boil a total of
    ${totalWater.toFixed(2)} grams of water.<br><br>

    Use ${bloom.toFixed(2)} grams of water for the bloom and
    ${rest.toFixed(2)} grams of water for the rest.
    `;

    document.getElementById("result").innerHTML = output;
}
</script>
