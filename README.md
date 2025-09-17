# html
this is the test repo to put my html project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Radio</title>
</head>
<body>
    <!----Testing input type radio--->
    
    <form>
        <!----label tag box+descriptin jodega--->

        <label for="Male">Male</label>

        <!----input type (button  bataye) kaisa chahiye or id toh lebel ka hi part h  name attribute diye taki sab me unique name(gender) fill kare--->

        <input type="Radio" id="Male" name="gender"
        value="Male"><br>

        <label for="Female">Female</label>
        <input type="radio" id="male" name="gender"
        value="Female"><br>

        <label for="others">others</label>
            <input type="radio" id="others" name="gender"
            value="others"><br>

       

    </form>
    
</body>
</html>
