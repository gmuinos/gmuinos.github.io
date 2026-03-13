# Looking for Some Color

![winemaking](https://scontent.fein1-1.fna.fbcdn.net/v/t39.30808-6/481666345_1052283500264578_7444298062378240971_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=13d280&_nc_ohc=mFCLJTfxf2cQ7kNvwGBEuTt&_nc_oc=Adln4RyWlXKHVU40KOi7DpF-_bWhl7PAQIVfH2iURxrHFiaph5VjujD_l09GQlQ58wM&_nc_zt=23&_nc_ht=scontent.fein1-1.fna&_nc_gid=HmDVpzJV51h6xCW9RqmFhg&_nc_ss=8&oh=00_AfwKhmlS12CflSTJw1UOrFBitmjBajDzkqeUmZiRj_sXOg&oe=69B9A7E1)

# White wine

> Press. Separate. Ferment.

#### Today's example:

![mosel](https://wineinternationalassociation.org/wp-content/uploads/2019/11/The-Mosel-Valley-2048x1368.jpg)

***Area:*** Nahe, Germany

***Wine:*** Jakob Schneider, Tradition

***Grape:*** Riesling

<iframe width="425" height="350" src="https://www.openstreetmap.org/export/embed.html?bbox=1.636962890625%2C48.39999820442095%2C12.952880859375002%2C51.8900220583336&amp;layer=mapnik&amp;marker=50.17686504441581%2C7.294921875" style="border: 1px solid black"></iframe><br/><small><a href="https://www.openstreetmap.org/?mlat=50.177&amp;mlon=7.295#map=7/50.177/7.295">

# Orange wine

> Press white grapes. Keep together. Ferment. Separate.

#### Today's example:

![alsace](https://internationalliving.com/_next/image/?url=https%3A%2F%2Fimages.ctfassets.net%2Fwv75stsetqy3%2F7lIPEhQeqawJ8iownoSXZM%2F7962373ad77da59805b8b8d35d612096%2FAlsace__France.jpg%3Fw%3D1800%26h%3D600%26q%3D60%26fit%3Dfill%26fm%3Dwebp&w=3840&q=60)

***Area:*** Alsace, France

***Wine:*** Gustave Lorentz, Qui l’Eût Cru

***Grapes:*** Gewürztraminer, Pinot Gris, Sylvaner

<iframe width="425" height="350" src="https://www.openstreetmap.org/export/embed.html?bbox=1.4611816406250002%2C46.53784224512105%2C12.777099609375%2C50.15732228373545&amp;layer=mapnik&amp;marker=48.3797382432003%2C7.119140625" style="border: 1px solid black"></iframe><br/><small><a href="https://www.openstreetmap.org/?mlat=48.380&amp;mlon=7.119#map=7/48.380/7.119">


# Rosé wine

> Press red grapes. Keep together shortly. Separate. Ferment.

#### Today's example:

![provence](https://img.sandayagroupe.eu/images/_aliases/paragraph_image_col6/0/3/3/4/754330-7-eng-GB/adfb379a7bb6-Provence-1-.jpg)

***Area:*** Bandol, Provence, France

***Wine:*** Domaines Bunan, Mas de la Rouvière

***Grapes:*** Cinsault, Grenache, Mourvèdre

<iframe width="425" height="350" src="https://www.openstreetmap.org/export/embed.html?bbox=0.10986328125000001%2C41.22551893724908%2C11.425781250000002%2C45.19496437381082&amp;layer=mapnik&amp;marker=43.24255853368201%2C5.767822265625" style="border: 1px solid black"></iframe><br/><small><a href="https://www.openstreetmap.org/?mlat=43.243&amp;mlon=5.768#map=7/43.243/5.768">

# Red wine

> Press red grapes. Keep together. Ferment. Separate.

#### Today's example:

![piemonte](https://static2-viaggi.corriereobjects.it/wp-content/uploads/2015/06/piemonte-guide-getty-1080x720.jpg?v=136710)

***Area:*** Barbaresco, Piedmont, Italy

***Wine:*** Produttori del Barbaresco, Barbaresco

***Grapes:*** Nebbiolo

<iframe width="425" height="350" src="https://www.openstreetmap.org/export/embed.html?bbox=2.0214843750000004%2C43.3610759013348%2C13.337402343750002%2C47.193392807119075&amp;layer=mapnik&amp;marker=45.309611566558154%2C7.679443359375" style="border: 1px solid black"></iframe><br/><small><a href="https://www.openstreetmap.org/?mlat=45.310&amp;mlon=7.679#map=7/45.310/7.679">


<button id="floatingBtn">The four types</button>

<div id="imagePopup" style="display:none;">
  <img src="https://scontent.fein1-1.fna.fbcdn.net/v/t39.30808-6/481666345_1052283500264578_7444298062378240971_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=13d280&_nc_ohc=mFCLJTfxf2cQ7kNvwGBEuTt&_nc_oc=Adln4RyWlXKHVU40KOi7DpF-_bWhl7PAQIVfH2iURxrHFiaph5VjujD_l09GQlQ58wM&_nc_zt=23&_nc_ht=scontent.fein1-1.fna&_nc_gid=HmDVpzJV51h6xCW9RqmFhg&_nc_ss=8&oh=00_AfwKhmlS12CflSTJw1UOrFBitmjBajDzkqeUmZiRj_sXOg&oe=69B9A7E1" width="350">
</div>

<style>
#floatingBtn {
  position: fixed;
  bottom: 20px;
  right: 20px;
  padding: 12px 16px;
  background-color: #990293;
  color: white;
  border: none;
  border-radius: 50px;
  cursor: pointer;
}

#imagePopup {
  position: fixed;
  bottom: 80px;
  right: 20px;
  background: white;
  padding: 10px;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}
</style>

<script>
const btn = document.getElementById("floatingBtn");
const popup = document.getElementById("imagePopup");

btn.onclick = function() {
  if (popup.style.display === "none" || popup.style.display === "") {
    popup.style.display = "block";
  } else {
    popup.style.display = "none";
  }
};
</script>

