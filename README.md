
## About
SensorVault is a research data-collection app used for the Universal Navigation Interface (UNI). UNI, which encompases the development of the SensorVault app, is a research project developed by the RIVeR Lab at Northeastern University in Boston, MA. The UNI probject focuses on the developing field of autonomous mobility aides. UNI uses a walker (or other wheeld platform such as a rollator or cart) and gimbal, as well as an iPhone with the SensorVault App, to collect data. The phone is helped at approximately 90 cm above the ground and points forward along the direction of travel. Through the SensorVault App, UNI records sensor data during walks for research on autonomous accessibility navigation — specifically, training navigation policies for autonomous wheelchairs and assistive mobility robots.

***UNI is currently distributed via TestFlight to researchers and collaborators working on robot navigation, accessibility, and mobile robotics. Broader access for community contributors is in development.***


## Content

<img src="https://github.com/user-attachments/assets/be76bfc6-c851-42e8-891b-497b0276e8d8" alt="App Home Page" style="width:30%; height:auto;">
<img src="https://github.com/user-attachments/assets/f075d0d7-77ce-44b0-b650-fa11f2d01603" alt="App Configuration Page" style="width:30%; height:auto;">

<img id="mainImage" src="https://github.com/user-attachments/assets/be76bfc6-c851-42e8-891b-497b0276e8d8" usemap="#image-map" alt="Map Image">

<map name="image-map">
  <area shape="rect" coords="34,44,270,350"
        href="#"
        onclick="changeImage('image1.jpg'); return false;"
        alt="Region 1">

  <area shape="circle" coords="130,136,60"
      href="#"
      onclick="changeImage('https://github.com/user-attachments/assets/f075d0d7-77ce-44b0-b650-fa11f2d01603'); return false;"
      alt="Region 2">

  <area shape="poly" coords="300,50,400,150,350,200"
        href="#"
        onclick="changeImage('image3.jpg'); return false;"
        alt="Region 3">
</map>

<script>
function changeImage(newSrc) {
  document.getElementById("mainImage").src = newSrc;
}
</script>
