time = new Decimal(10);
clickPower = new Decimal(1);
timePerSecond = new Decimal(0);

var exp;

function Update()
{   
    time = time.plus(timePerSecond / 300);

    if (time.lt(1000))
    {
        document.getElementById("time").innerHTML = "You have " + time.toFixed(0) + " time";  
    }
    else
    {
        document.getElementById("time").innerHTML = "You have " + (time.m.toPrecision(3) + "e" + time.e) + " time";   
    }

    if (clickPower.lt(1000))
    {
        document.getElementById("foldTime").innerHTML = "Fold Event" + "<br>" + "+" + clickPower + " time"; 
    }
    else
    {
        document.getElementById("foldTime").innerHTML = "Fold Event" + "<br>" + "+" + (clickPower.m.toPrecision(3) + "e" + clickPower.e) + " time";
    }
}
function Clicked()
{
    time = time.plus(clickPower);
}
setInterval(Update, 1000/300);
                
                