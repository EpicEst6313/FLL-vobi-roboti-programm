# Baasrobot


## Head küljed

- Kasutame sõitmise ajal maksimum võimsust, mis tähendab, et mootorid on täpsemad ja vahemaa läbimine on täpsem
- kuubi kujulise roboti peale on hea ehitada erinevaid moodulied

## Halvad küljed

- Ülekanne käib üle, teeb roboti ebatäpsemaks ning roboti maksimum kiirus on aeglane,
- Spike robotis olev gyroskoop ei ole usaldusväärne ning ei tööta ja ei lase otse sõitu parandada
- Ei pidanud drop testi vastu.

## Miks sellise versiooni tegime

tahtsin proovida uut disaini hammasratastega ning parandada viga, et laadimis port oli väga raske ligi pääseda.

## Pildid

<img src="roboti%20pildid/baas1.png" alt="Alt Text" width="500">       <img src="roboti%20pildid/baas2.png" alt="Alt Text" width="500">
<img src="roboti%20pildid/baas3.jpg" alt="Alt Text" width="500">

## Vanad versioonid

### Vana roboti disain (2. disain)

**Head küljed**

-kompaktne ja pidas drop testi vastu,
- massi kese peamiselt sõidu rataste peal
- laadimis port oli kergesti juurdepääsetav kuni otsustasime pöörata spike hubi ümber sest nupud olid väärakas kohas.

**Halvad küljed**

- Laadimis port oli kinni kaetud
- gyroga ei saa teha otse sõitu sest see lihtsalt ei ole töötanud aga eelmine aasta parandas roboti täpsust väga korralikult
- ratta valik on ka natuke halb, kuna need rattad saavad libiseda ja see aga jälle tähendab, et roboti täpsus kannatab


**Pildid**

<img src="roboti%20pildid/vana1.jpg" alt="Alt Text" width="500">       <img src="roboti%20pildid/vana2.jpg" alt="Alt Text" width="500">
<img src="roboti%20pildid/vana3.jpg" alt="Alt Text" width="500">

### Algne Robot disain (1. disain)

**Head küljed**

- See robot oli väga kompaktne ja ei raisanud ruumi
- Aku vahetus oli kerge ning sai kasutada teist hub’i et laadida akut samal ajal kasutades teise hub’i akut programmeerimiseks.

**Halvad küljed**

- Roboti massi kese täpselt keskel mis tähendab, aga seda et tagumistele ratastele ei jäänud mingisugust viisi liigutada, kui moodulid peale panna.

**Pildid**

<img src="roboti%20pildid/algne1.jpg" alt="Alt Text" width="500">       <img src="roboti%20pildid/algne2.jpg" alt="Alt Text" width="500">
<img src="roboti%20pildid/algne3.jpg" alt="Alt Text" width="500">

# 1. moodul

korjab üless platsilt ühe kirilli ja võtab veeproovi, vabastab hai ja lükkab korallipungad õiget pidi ja võtab kaasa sukelduja ja läheb kodualasse

**Algrõhk moodulil:** 2 bari või 30 psi

## Punktid

- **Korallrahu segmentide ära toomine:** -10 p
- **Korallipungad:** +20 p
- **Sukelduja ära toomine:** +20 p
- **Hai koobast vabastamine:** +20 p
- **Veeproov:** +5 p

**Kokku:** 55 p

## Paigutus platsil

<img src="roboti%20pildid/20250211_144552.jpg" alt="Alt Text" width="500">       <img src="roboti%20pildid/20250211_144557.jpg" alt="Alt Text" width="500">
<img src="roboti%20pildid/20250211_144609.jpg" alt="Alt Text" width="500">

## Pildid moodulist

<img src="roboti%20pildid/1.moodul3.jpg" alt="Alt Text" width="500">        <img src="roboti%20pildid/esimene_moodul1.jpg" alt="Alt Text" width="500">
<img src="roboti%20pildid/esimenemoodul2.jpg" alt="Alt Text" width="500">

## Sõidu plaan

<img src="roboti%20pildid/Kuvatõmmis%202025-03-28%20180601.png" alt="Alt Text" width="500"> 

## Head küljed

- istub ilusti roboti peal
- töötab 100% ajast kui enne muuta numbreid koodis
- pneumaatika töötab 100% ajast (kui ei unusta rõhku sisse pumbata)

## Halvad Küljed

- natuke suure on
- koralli tegemise asi libiseb vastu maad ja vahel teeb häält
- võib unustada rõhu üless pumbata

# 2. moodul

Tõstab masti üless ja varastab aarde laeka ning napsab kirilli eest ära ja paneb sukelduja korall rahule

## Punktid

- **Masti üless tõstmine:** +30 p
- **Aardelaek varastamine:** +20 p
- **sukelduja transport koralli toe külge:** +20 p

**Kokku:** 70p

## Paigutus platsil

<img src="roboti%20pildid/20250217_172351.jpg" alt="Alt Text" width="500">        <img src="roboti%20pildid/20250217_172401.jpg" alt="Alt Text" width="500">

## Pildid moodulist

<img src="roboti%20pildid/2.moodul1.jpg" alt="Alt Text" width="500">          <img src="roboti%20pildid/2.moodul2.jpg" alt="Alt Text" width="500">
<img src="roboti%20pildid/2.moodul3.jpg" alt="Alt Text" width="500">          <img src="roboti%20pildid/2.moodul4.jpg" alt="Alt Text" width="500">

## Sõidu plaan

<img src="roboti%20pildid/Kuvatõmmis%202025-03-28%20180552.png" alt="Alt Text" width="500"> 

## Head küljed

- jõuab kodualasse koguaeg tagasi
- sukelduja paneb 100% rippuma
- seda on hea progeda annab piisavalt eksimis ruumi

## halvad küljed

- sõidab vahepeal mastile liiga kiiresti otsa

## miks tegime vana mooduli number 2 ümber?

- Sellel oli raskuse probleemid
- kohmakalt suur
- probleeme käppadega liiga rasked ja pidi vastu raskust kasutama
- jõhkralt raske programmeerida
- ebatäpne
- üless sättimine võttis väga kaua aega

## Pildid vanast number 2 moodulist

<img src="roboti%20pildid/vanateine1.jpg" alt="Alt Text" width="500">          <img src="roboti%20pildid/vanateine2.jpg" alt="Alt Text" width="500">

# 3. moodul


## Punktid

- **Hai ära viimine:** 10p
- **4-jala rööv:** 20p

**Kokku:** 30p

## Paigutus platsil

<img src="roboti%20pildid/3.paigutus1.jpg" alt="Alt Text" width="500">        <img src="roboti%20pildid/3.paikutus2.jpg" alt="Alt Text" width="500">
<img src="roboti%20pildid/3.paikutus3.jpg" alt="Alt Text" width="500">

## Pildid moodulist

<img src="roboti%20pildid/3.1.jpg" alt="Alt Text" width="500">        <img src="roboti%20pildid/3.2.jpg" alt="Alt Text" width="500">
<img src="roboti%20pildid/3.3.jpg" alt="Alt Text" width="500">

## Sõidu plaan

<img src="roboti%20pildid/Kuvatõmmis%202025-03-28%20180544.png" alt="Alt Text" width="500"> 

## Head küljed

- Kerge programmeerida
- Kerge paika panna
- Kompaktne

## halvad küljed

- Vähe punkte
- Vahepeal sõidab objektile otsa

# 4. moodul


## Punktid

- **Pinnaseproov:** 10p
- **Ühisülesanne:** 30p
- **Merikurat:** 30p
- **Sonar:** 20p

**Kokku:** 90p

## Paigutus platsil



## Pildid moodulist

<img src="roboti%20pildid/4.1.jpg" alt="Alt Text" width="500">        <img src="roboti%20pildid/4.2.jpg" alt="Alt Text" width="500">
<img src="roboti%20pildid/4.3.jpg" alt="Alt Text" width="500">        <img src="roboti%20pildid/4.4.jpg" alt="Alt Text" width="500">

## Sõidu plaan

<img src="roboti%20pildid/Kuvatõmmis%202025-03-28%20180526.png" alt="Alt Text" width="500"> 

## Head küljed

- Palju punkte
- Kompaktne

## halvad küljed

- Kehv hammasrattaülekanne
- Suht suur võimalus ebatäpsuseks
