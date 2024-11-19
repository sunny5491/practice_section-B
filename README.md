<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p> begins here</p>
    <form> 
       
        <label for="name">drop your name here  :</label>
        <input type="name" id="name"  value ="sample" placeholder="name" required minlength="7" maxlength="10" size="25">
        <br>
        <br>

        <label for="email">drop your email here  :</label>
        <input type="email" id="email" placeholder="email" minlength="7" maxlength="10" size="25">
        <br>
        <br>

        <label for="password">drop your password here :</label>
        <input type="checkbox" id="password"  value ="sample" placeholder="password" required minlength="7" maxlength="10" size="25">
        <br>
        <br>

        <label for="male">male:</label>
        <input type="radio" id="male"  value ="" placeholder="" >
        <br>
        <br>

        <label for="female">female :</label>
        <input type="radio" id="female"  value ="" placeholder="" >
        <br>
        <br>

        <label for="date">enter the date :</label>
        <input type="date" id="date"  value ="" placeholder="date" >
        <br>
        <br>

        <label for="lunchtime">enter the lunch-time :</label>
        <input type="time" id="time" min="11:00:01" max="23:00:04" >
        <br>
        <br>


        <label for ="animal-select" > favourite animals</label>
        <select name="animals" id="animal-select" multiple>
            <option value="dog" >Dog</option>
            <option value="cat" >cat</option>
            <option value="horse" >horse</option>
            <option value="zebra" >zebra</option>
            <option value="lion" >lion</option>
        </select>




        <button>submit Details</button>
   


        
    
    </form>
    
</body>
</html>
