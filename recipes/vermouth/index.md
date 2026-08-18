# Dos Vermús

![fourSeasons](https://cdn.hswstatic.com/gif/redefinefourseasons-1.jpg)

This recipe includes two types of vermouth a summery dry white vermouth and a sweeter wintery one. On the bottom of the page there is information about how to make them and also a calculator to know how much distilled alcohol needs to be added.

## Primavera/Verano
### Vermú de la Pasión 
![spring](https://static.stacker.com/s3fs-public/styles/slide_desktop/s3/37oklahomaGCPA.jpg)

> Try with red wine. Remove red berries. Try flowers on their own.

16% alcohol
- hinojo: cucharilla rasa
- semillas de cilantro: dos cucharillas colmadas
- lavanda: un chis
- flor de hibisco: tres colmadas
- pétalos de rosa: tres colmadas
- jengibre: un cachito
- artemisa: media cucharilla
- albahaca seca: unos chis
- frutos rojos: un puñado
- 50 ml of simple syrup with wine instead of water

## Otoño/Invierno
### Glühmú

![autumn](https://images.stockcake.com/public/8/e/a/8eac5778-f460-4ac7-9104-bb7b61edd45c_large/autumn-meets-winter-stockcake.jpg)

- Salvia: Dos y media cucharillas colmadas
- Nuez moscada: cucharilla rasa
- Canela: cucharilla rasa pero un poquito más
- Clavo: una cucharilla rasa
- Romero: cucharilla rasa
- Tomillo: tres chis
- Artemisa: cucharilla colmada
- 100ml simple syrup 
- Chorrito de vainilla

## Steps for one
- Make 100ml of honey syrup per bottle of sweet vermouth
- Open a bottle of wine
- Separate 250ml
- Take 250ml into a small pot
- Add herbs and spices
- Warm up the wine until it is almost boiling
- Keep it at that temperature for around 10 minutes
- Add 250ml of the brandy to the bottle of wine
- Strain the warm liquid into the wine bottle
  - Add 100ml of honey syrup if sweet
- Top up with the previously separated wine if bottle is not full

## Basic ingredients
- Brandy, sherry, or vodka
- Honey
- White wine
- Red wine

## Special tools
- Metallic filter from AeroPress

## Calculator
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vodka Calculator</title>
</head>
<body>

    <h1>Alcohol Percentage Calculator</h1>

    <label for="desiredAlcohol">Desired alcohol percentage:</label>
    <input type="number" id="desiredAlcohol" step="0.1">
    <br><br>

    <label for="wineAlcohol">Current wine alcohol percentage:</label>
    <input type="number" id="wineAlcohol" step="0.1">
    <br><br>

    <label for="vodkaAlcohol">Current vodka alcohol percentage:</label>
    <input type="number" id="vodkaAlcohol" step="0.1">
    <br><br>

    <button onclick="calculateVodka()">Calculate</button>

    <h2 id="result"></h2>

    <script>
        function calculateVodka() {
            const desiredAlcohol = parseFloat(document.getElementById("desiredAlcohol").value);
            const wineAlcohol = parseFloat(document.getElementById("wineAlcohol").value);
            const vodkaAlcohol = parseFloat(document.getElementById("vodkaAlcohol").value);

            const total = 750;

            const vv =
                (total * (desiredAlcohol / 100 - wineAlcohol / 100)) /
                (vodkaAlcohol / 100 - wineAlcohol / 100);

            document.getElementById("result").textContent =
                "You need to add a total of " + vv.toFixed(2) + " ml of vodka.";
        }
    </script>

</body>
</html>

## Notes
> Consejos: menos lavanda, añadir azúcar, solo una cuchara rasa de artemisa,100 ml de colonia y more flowers 
18% alcohol 
- Hinojo: Una cucharilla rasa
- Semillas de cilantro: Una cucharilla colmada y media
- Lavanda: Una cucharilla rasa
- Flor de hibisco: Dos cucharillas colmadas
- Petalos de rosas: Dos cucharillas colmadas y media
- Jengibre: Un cachito
- Artemisa: Un cucharilla colmada
- Rayadura de un tercio de limón
- Manojo pequeño de albahaca (tras apagar el fuego)
- Frutos rojos: un puñado
