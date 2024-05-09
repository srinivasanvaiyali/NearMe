# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE

SALEM.HTML
```
<html>
    <HEAD>
        <TITLE>My City</TITLE>
    </HEAD>
    <BODY>
        <h1 align="center">
            <font color="ligthred"><b>SALEM</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>SRINIVASAN (212222043008)</b></font>
        </h3>
        <CENTER>
            <img src="C:\Users\srini\Pictures\Screenshots\background.png" usemap="#mymap" height="500" width="1000">
            <map name="mymap">
                <area title="YERCAUD" href="YERCAUD.html" coords="652,320,880,398" shape="rect">
                <area title="1008 Lingam Temple" href="lingam.html" coords="452,600,208" shape="circle">
                <area title="METTUR" href="METTUR.html" coords="819,400,981,881" shape="rect">
                <area title="SRI KOTTAI MARIAMMAN" href="TEMPLE.html" coords="705,315,935,337,710,414,637,317" shape="poly">
               
            </map>

        </CENTER>
    </BODY>
</html>
```

YERCAUD
```
<HTML>
    <HEAD>
        <TITLE>YERCAUD</TITLE>
    </HEAD>
    <body bgcolor="lightblue">
        <h1 align="center">
            <font color="brown">SALEM</font>
        </h1>
        
        <h3 align="center">
            <font color="blue">YERCAUD</font>
        </h3>
        <hr color="green" align="center">
        <br>
        <p><h4>
            Yercaud is a hill station near Salem, in the Servarayan range of hills (anglicized as Shevaroys) in the Eastern Ghats. It is at an altitude of 1515 metres (4969 feet) above the see level. The total extent of Yercaud Taluk is 382.67 Sq.kms. including Reserve Forest. The entire Taluk is a Township. Yercaud has also a Panchayat Union with its Head Quarters at Yercaud and its Jurisdiction is the same as for Yercaud Taluk. Popular as the “Poor man’s Ooty”. Yercaud is one of the low cost hill station destination in India.
    </body>
</HTML>
```

LINGAM.HTML
```
<HTML>
    <HEAD>
        <TITLE>1008 Lingam Temple</TITLE>
    </HEAD>
    <body bgcolor="lightgreen">
        <h1 align="center">
            <font color="black">SALEM</font>
        </h1>
        
        <h3 align="center">
            <font color="white">1008 Lingam Temple</font>
        </h3>
        <hr color="red" align="center">
        <br>
        <p><h4>
            Salem, Tamil Nadu is a city of temples. The city has many beautiful, unique and historic temples which are famous all over the world. One of which is 1008 lingam temple. Located in Ariyanoor, a suburb of Salem city, 1008 Lingam Temple is one of the most beautiful temples in the country. It has 1007 shiv lingam, which surrounds the main temple of Shiva, and the main shiv linga in the center. It was created and now maintained by the private department of Vinayaka Mission
            1008 Lingam Temple is located in Ariyanoor, which is a suburb of Salem city on a hillock near Kunjmaala. The temple is managed by a separate dept. of Vinayaka Mission. The temple was constructed in 2010. The temple has 1007 lingams which surrounds the main shiv temple, which has the 1008th lingam with the holy cow Nandi’s statue in front. For visiting the temple, you have to go on Sangagiri to Salem highway, just after crossing the institutions of Vinayaka Mission.
    </body>
</HTML>
```

METTUR.HTML
```
<HTML>
    <HEAD>
        <TITLE>METTUR</TITLE>
    </HEAD>
    <body bgcolor="red">
        <h1 align="center">
            <font color="blue">SALEM</font>
        </h1>
        
        <h3 align="center">
            <font color="white">METTUR</font>
        </h3>
        <hr color="lightgreen" align="center">
        <br>
        <p><h4>
            Mettur Dam is one of the largest dams in India, also known as Stanley Reservoir; is constructed in a gorge, where the Cauvery River enters the plains. It is located at Mettur, district Salem in Tamil Nadu. The catchment area of Cauvery River upto the dam site is 42924 sq kmIt was constructed under the supervision of an Irish engineer, Vincent Hart, who was also the chief engineer of the project. It took nine years[2] and the effort of 17,000 men to complete the dam project. After the construction was complete, Mettur Dam over Kaveri became the largest dam in the world.[3] The funds were provided from the taxes collected in the Madras Presidency. The Board of Revenue was headed by Sir C.P. Ramaswamy Iyer who initiated the building of the dam.[4] As a result, the dam authorities evacuated the people of Nayambadi and some other villages where the dam was sited. When the water level of the reservoir recedes, even now old Christian Church of Nayamabadi and some Hindu temples from other villages emerge from it as proof.[5] Those people who migrated from Nayambadi have settled down in Martalli, Cowdalli and other nearby villages in the Kollegal taluk of Chamarajanagar district of the state of Karnataka..
        </h4></p>
    </body>
</HTML>
```

TEMPLE.HTML
```
<HTML>
    <HEAD>
        <TITLE>SRI KOTTAI MARIAMMAN</TITLE>
    </HEAD>
    <body bgcolor="red">
        <h1 align="center">
            <font color="blue">SALEM</font>
        </h1>
        
        <h3 align="center">
            <font color="white">SRI KOTTAI MARIAMMAN</font>
        </h3>
        <hr color="lightgreen" align="center">
        <br>
        <p><h4>
            Sri Kottai Mariamman Temple is a refreshing experience for devotees in many ways. It is a 500 years old temple in Dindigul of Tamil Nadu district. Mariamman is the Hindu Goddess of Rain in South India. The place Dindigul is also famous for its Vasthu aspects.The Kottai Mariamman Temple is located on the banks of river Tirumanimutthar. It is regarded as one of the oldest pilgrimage centres of the city of Salem. The presiding deity at this temple is Goddess Kottai Mariamman. Pilgrims travel from near and distant places to seek blessings at this temple and to soak up the calm and quietness.
        </h4></p>
    </body>
</HTML>
```

## OUTPUT

![SALEM](https://github.com/srinivasanvaiyali/NearMe/assets/145117665/50ca442e-3063-4f6c-a07c-db845798430d)


![YERCAUD](https://github.com/srinivasanvaiyali/NearMe/assets/145117665/fa7381f8-3280-4466-91d3-8f7a2b93f833)


![1008 LINGAM TEMPLE](https://github.com/srinivasanvaiyali/NearMe/assets/145117665/5554e62d-0971-4771-b3ad-e9657e6ca5b4)


![METTUR](https://github.com/srinivasanvaiyali/NearMe/assets/145117665/a840ec27-314d-4482-8a85-c2a03b21f141)


![SRI KOTTAI MARIAMAN](https://github.com/srinivasanvaiyali/NearMe/assets/145117665/e130b975-702a-4d02-9fa6-073f9b44ab65)

## RESULT
The program for implementing image maps using HTML is executed successfully.
