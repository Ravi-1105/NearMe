# Ex04 Places Around Me

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Massachusetts Universities</title>
</head>
<style>
    * {margin: 0;}
</style>
<script>
    function coordinate(event) {
        let x = event.clientX;
        let y= event.clientY;
        document.getElementById("text1").value = x;
        document.getElementById("text2").value = y;
    }
</script>

<body>

    <IMG src="map.png " width="1000" height="500" 
    usemap="#MapNew" onmousemove="coordinate(event)">
    <MAP name="MapNew">
        <AREA shape="RECT" coords="116,33,228,112" href="https://www.harvard.edu/" title="Harvard University">
        <AREA shape="RECT" coords="574,409,661,446" href="https://web.mit.edu/" title="MIT">
    </MAP>
    <br>
    X-coordinate
    <input type="text" id="text1">
    <br>
    <br>
    Y-coordinate
    <input type="text" id="text2">
</body>
</html>
```
## OUTPUT

![image](https://github.com/Ravi-1105/NearMe/assets/139841688/5617e503-8f41-45e5-9c41-fa55e51013b1)
![image](https://github.com/Ravi-1105/NearMe/assets/139841688/b51ec70f-6cd3-49f8-90e0-cbf77213e0cf)
![image](https://github.com/Ravi-1105/NearMe/assets/139841688/9b6cf889-b174-4185-9460-b01782474a4a)
![image](https://github.com/Ravi-1105/NearMe/assets/139841688/e809bb83-d606-4fea-a99a-9bc09b368f38)

## RESULT
The program for implementing image maps using HTML is executed successfully.
