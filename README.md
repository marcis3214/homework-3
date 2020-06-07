<!DOCTYPE html>
<html lang="en"><head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Page Title</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" media="screen" href="styles/style.css">
    <script src="scripts/script.js" defer=""></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
</head>
<body>
    <main>
        <h1>FIZZ BUZZ</h1>
        <div class="navContainer">
            <label>MIN number: </label><input type="number" name="field" id="minInput" min="1" max="99" onpaste="return false">
            <label>MAX number: </label><input type="number" name="field" id="maxInput" min="2" max="100" onpaste="return false">
            <button id="btnOne">RESET</button>
            <button id="btnTwo">REFRESH</button>
            <button id="btnThree">FIZZ</button>
            <button id="btnFour">BUZZ</button>
            <button id="btnFive">FIZZBUZZ</button>
        </div>
        <div id="container"><div id="div_1" class="num"><p>1</p></div><div id="div_2" class="num"><p>2</p></div><div id="div_3" class="fiz"><p>3 = FIZZ</p></div><div id="div_4" class="num"><p>4</p></div><div id="div_5" class="buz"><p>5 = BUZZ</p></div><div id="div_6" class="fiz"><p>6 = FIZZ</p></div><div id="div_7" class="num"><p>7</p></div><div id="div_8" class="num"><p>8</p></div><div id="div_9" class="fiz"><p>9 = FIZZ</p></div><div id="div_10" class="buz"><p>10 = BUZZ</p></div><div id="div_11" class="num"><p>11</p></div><div id="div_12" class="fiz"><p>12 = FIZZ</p></div><div id="div_13" class="num"><p>13</p></div><div id="div_14" class="num"><p>14</p></div><div id="div_15" class="fizbuz"><p>15 = FIZZ BUZZ</p></div><div id="div_16" class="num"><p>16</p></div><div id="div_17" class="num"><p>17</p></div><div id="div_18" class="fiz"><p>18 = FIZZ</p></div><div id="div_19" class="num"><p>19</p></div><div id="div_20" class="buz"><p>20 = BUZZ</p></div><div id="div_21" class="fiz"><p>21 = FIZZ</p></div><div id="div_22" class="num"><p>22</p></div><div id="div_23" class="num"><p>23</p></div><div id="div_24" class="fiz"><p>24 = FIZZ</p></div><div id="div_25" class="buz"><p>25 = BUZZ</p></div><div id="div_26" class="num"><p>26</p></div><div id="div_27" class="fiz"><p>27 = FIZZ</p></div><div id="div_28" class="num"><p>28</p></div><div id="div_29" class="num"><p>29</p></div><div id="div_30" class="fizbuz"><p>30 = FIZZ BUZZ</p></div><div id="div_31" class="num"><p>31</p></div><div id="div_32" class="num"><p>32</p></div><div id="div_33" class="fiz"><p>33 = FIZZ</p></div><div id="div_34" class="num"><p>34</p></div><div id="div_35" class="buz"><p>35 = BUZZ</p></div><div id="div_36" class="fiz"><p>36 = FIZZ</p></div><div id="div_37" class="num"><p>37</p></div><div id="div_38" class="num"><p>38</p></div><div id="div_39" class="fiz"><p>39 = FIZZ</p></div><div id="div_40" class="buz"><p>40 = BUZZ</p></div><div id="div_41" class="num"><p>41</p></div><div id="div_42" class="fiz"><p>42 = FIZZ</p></div><div id="div_43" class="num"><p>43</p></div><div id="div_44" class="num"><p>44</p></div><div id="div_45" class="fizbuz"><p>45 = FIZZ BUZZ</p></div><div id="div_46" class="num"><p>46</p></div><div id="div_47" class="num"><p>47</p></div><div id="div_48" class="fiz"><p>48 = FIZZ</p></div><div id="div_49" class="num"><p>49</p></div><div id="div_50" class="buz"><p>50 = BUZZ</p></div><div id="div_51" class="fiz"><p>51 = FIZZ</p></div><div id="div_52" class="num"><p>52</p></div><div id="div_53" class="num"><p>53</p></div><div id="div_54" class="fiz"><p>54 = FIZZ</p></div><div id="div_55" class="buz"><p>55 = BUZZ</p></div><div id="div_56" class="num"><p>56</p></div><div id="div_57" class="fiz"><p>57 = FIZZ</p></div><div id="div_58" class="num"><p>58</p></div><div id="div_59" class="num"><p>59</p></div><div id="div_60" class="fizbuz"><p>60 = FIZZ BUZZ</p></div><div id="div_61" class="num"><p>61</p></div><div id="div_62" class="num"><p>62</p></div><div id="div_63" class="fiz"><p>63 = FIZZ</p></div><div id="div_64" class="num"><p>64</p></div><div id="div_65" class="buz"><p>65 = BUZZ</p></div><div id="div_66" class="fiz"><p>66 = FIZZ</p></div><div id="div_67" class="num"><p>67</p></div><div id="div_68" class="num"><p>68</p></div><div id="div_69" class="fiz"><p>69 = FIZZ</p></div><div id="div_70" class="buz"><p>70 = BUZZ</p></div><div id="div_71" class="num"><p>71</p></div><div id="div_72" class="fiz"><p>72 = FIZZ</p></div><div id="div_73" class="num"><p>73</p></div><div id="div_74" class="num"><p>74</p></div><div id="div_75" class="fizbuz"><p>75 = FIZZ BUZZ</p></div><div id="div_76" class="num"><p>76</p></div><div id="div_77" class="num"><p>77</p></div><div id="div_78" class="fiz"><p>78 = FIZZ</p></div><div id="div_79" class="num"><p>79</p></div><div id="div_80" class="buz"><p>80 = BUZZ</p></div><div id="div_81" class="fiz"><p>81 = FIZZ</p></div><div id="div_82" class="num"><p>82</p></div><div id="div_83" class="num"><p>83</p></div><div id="div_84" class="fiz"><p>84 = FIZZ</p></div><div id="div_85" class="buz"><p>85 = BUZZ</p></div><div id="div_86" class="num"><p>86</p></div><div id="div_87" class="fiz"><p>87 = FIZZ</p></div><div id="div_88" class="num"><p>88</p></div><div id="div_89" class="num"><p>89</p></div><div id="div_90" class="fizbuz"><p>90 = FIZZ BUZZ</p></div><div id="div_91" class="num"><p>91</p></div><div id="div_92" class="num"><p>92</p></div><div id="div_93" class="fiz"><p>93 = FIZZ</p></div><div id="div_94" class="num"><p>94</p></div><div id="div_95" class="buz"><p>95 = BUZZ</p></div><div id="div_96" class="fiz"><p>96 = FIZZ</p></div><div id="div_97" class="num"><p>97</p></div><div id="div_98" class="num"><p>98</p></div><div id="div_99" class="fiz"><p>99 = FIZZ</p></div><div id="div_100" class="buz"><p>100 = BUZZ</p></div></div>

    </main>
    const inputMin = document.getElementById("minInput");
const inputMax = document.getElementById("maxInput");
const main = document.getElementById("container");
const btnOne = document.getElementById("btnOne");
const btnTwo = document.getElementById("btnTwo");

// starting value on page refresh.
inputMin.value = 1;
inputMax.value = 100;

const create = function () {            //Creating function that will generate 100 divs.
while (main.firstChild) {
    main.removeChild(main.firstChild);
};

//this line creates 100 divs and hides all that do not match input values.

for (let i = 1; i <= 100; i++) {     
// for( i = inputMin.value; i <= inputMax.value; i++ ) { // <--- 'UNcomment' this line to create divs according to input values.
    let newDiv = document.createElement("div");
    let newPar = document.createElement("p");

    newDiv.appendChild(newPar);
    main.appendChild(newDiv).setAttribute("id", "div_" + i);    // giving "id" name to every div

    if (i < inputMin.value || i > inputMax.value) {
        newDiv.style = "display: none";
    } else {
        if (i % 3 === 0 && i % 5 === 0) {                              
            newPar.appendChild(document.createTextNode(i + ' = FIZZ BUZZ'));
            main.appendChild(newDiv).setAttribute("class", "fizbuz");   // this adds class to divs

        } else if (i % 3 === 0) {
            newPar.appendChild(document.createTextNode(i + ' = FIZZ'));
            main.appendChild(newDiv).setAttribute("class", "fiz");

        } else if (i % 5 === 0) {
            newPar.appendChild(document.createTextNode(i + ' = BUZZ'));
            main.appendChild(newDiv).setAttribute("class", "buz");

        } else {
            newPar.appendChild(document.createTextNode(i));
            main.appendChild(newDiv).setAttribute("class", "num");
        }
    }
}
};    

create();

//This adds event to first INPUT - sets min value.

inputMin.onkeyup = function (e) {
    this.value = inputMin.value.replace(/^(0*)/, "");
    if (inputMin.value >= 1 && inputMin.value <= 100) {
        this.value = inputMin.value;
    } else if (inputMin.value.length === 0) {
        inputMin.value = null;
    } else {
        inputMin.value = null;
        alert("Incorrect number!");
    }
    if (!((e.keyCode > 95 && e.keyCode < 106)
        || (e.keyCode > 47 && e.keyCode < 58)
        || [8, 13, 37, 39].indexOf(e.keyCode) >= 0
    )) {
        return false;
    }
    create();
};

//This adds event to second INPUT - sets max value.

inputMax.onkeyup = function (e) {
    this.value = inputMax.value.replace(/^(0*)/, "");
    if (inputMax.value >= 1 && inputMax.value <= 100) {
        this.value = inputMax.value;
    } else if (inputMax.value.length === 0) {
        inputMax.value = null;
        
    } else {
        inputMax.value = null;
        alert("Incorrect number!");
    }
    if (!((e.keyCode > 95 && e.keyCode < 106)
        || (e.keyCode > 47 && e.keyCode < 58)
        || [8, 13, 37, 39].indexOf(e.keyCode) >= 0
    )) {
        return false;
    }
    create();
};

// Buttons RESET and REFRESH

btnOne.onclick = function() {
    inputMin.value = "";
    inputMax.value = "";
    create();
};

btnTwo.onclick = function() {
    inputMin.value = 1;
    inputMax.value = 100;
    create();
};



// JQuery scripts for selecting divs according to class:

$(document).ready(function(){ $("#btnThree").click(function(){ 
    $(".num, .buz, .fizbuz").toggle();
  });
});

$(document).ready(function(){ $("#btnFour").click(function(){ 
    $(".num, .fiz, .fizbuz").toggle();
  });
});

$(document).ready(function(){ $("#btnFive").click(function(){ 
    $(".num, .buz, .fiz").toggle();
  });
});

html {
    margin: auto;
    padding: 10px;
    
}

body {
    font-family: 'Roboto', serif;
    font-weight: bold;
    background-color: grey;
 
}

main h1{
    text-align: center;
    font-size: 2em;
}

#container {
    margin-top: 2%;
    width: 100%;
    height: auto;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(180px, 1fr) ) ;
    grid-gap: 10px;
    align-content: center;
    justify-items: center;
    
}

#container p {
    margin: 0;
    padding: 0;
    text-align: center;
  
}

@media (max-width: 576px) {
    #container {
        grid-template-columns: 1fr 1fr;
    }

    .navContainer {
        width: 100%;
        min-height: 400px;
        flex-wrap: wrap;
        flex-direction: column;
    }
}    

/* FIZBUZ class */

.fizbuz {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    min-height: 100px;
    font-size: 1.5em;
    border-radius:4px;
    border:1px solid #bbb;

    transition: all 0.3s linear;
    background: linear-gradient(to top, #56B870 0%,#a5c956 100%); /* W3C */
}

.fizbuz:hover {
    box-shadow:rgba(0,0,0,0.8) 0px 5px 15px, inset rgba(0,0,0,0.15) 0px -10px 20px;
}

/* FIZ class */

.fiz {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    min-height: 100px;
    font-size: 1.5em;
    border-radius: 4px;
    border: 1px solid #bbb;

    transition: all 0.3s linear;
    background: linear-gradient(to top, #C655BE 0%,#cf0404 100%); /* W3C */
}

.fiz:hover {
    box-shadow:rgba(0,0,0,0.8) 0px 5px 15px, inset rgba(0,0,0,0.15) 0px -10px 20px;
}

/* BUZ class */

.buz {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    min-height: 100px;
    font-size: 1.5em;
    border-radius:4px;
    border:1px solid #bbb;

    transition: all 0.3s linear;
    background: linear-gradient(to top, #F3AAAA 0%,#febf04 100%); /* W3C */
}

.buz:hover {
    box-shadow:rgba(0,0,0,0.8) 0px 5px 15px, inset rgba(0,0,0,0.15) 0px -10px 20px;
}

/* NUM class */

.num {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    min-height: 100px;
    font-size: 1.5em;
    border-radius:4px;
    border:1px solid #bbb;

    transition: all 0.3s linear;
    background: linear-gradient(to top, #7abcff 0%,#60abf8 44%,#4096ee 100%); /* W3C */
}

.num:hover {
    box-shadow:rgba(0,0,0,0.8) 0px 5px 15px, inset rgba(0,0,0,0.15) 0px -10px 20px;
}

/* Navigation */

.navContainer {
    width: 100%;
    height: 80px;
    display: flex;
    flex-flow: row wrap;
    align-items: center;
    justify-content: space-evenly;
    background-color: #4096ee;
    font-size: 1.5em;
    border-radius: 4px;

}
  
  input, button {
      font-size: 1em;
      border-radius: 5px;
      width: 200px;
      text-align: center;
  }

    input::-webkit-outer-spin-button,
    input::-webkit-inner-spin-button {
    -webkit-appearance: none;
    }


    
    #btnOne {
        background-color: green; 
        color: yellow; 
        border: 5px solid #4CAF50;
      }
      
    #btnTwo {
        background-color: white; 
        color: black; 
        border: 5px solid #008CBA;
      }
      
    #btnThree {
        background-color: white; 
        color: red; 
        border: 5px solid #f44336;
      }
      
    #btnFour {
        background-color: white;
        color: gold;
        border: 5px solid #febf04;
      }
      
    #btnFive {
        background-color: white;
        color: black;
        border: 5px solid #a5c956;
      }

.hidden {
    display: none;

}










</body></html>
