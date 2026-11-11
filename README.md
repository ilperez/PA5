# PA5
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Forms</title>
     <!-- BOOTSTRAP -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>

    <!-- CSS -->
    <link rel="stylesheet" href="style5.css">
</head>
<body>
    
<div class="container bg-danger p-5 mt-5 rounded">
    <form action="" method="post">

        <h2>custom sneaker order form</h2>

        <label for="form-name" class="form-label">name:</label> 
        <input type="text" name="username" id="form-name" class="textinput form-control">
    
        <label for="form-email">email:</label> 
        <input type="email" name="emailaddress" id="form-email" class="textinput form-control">

        <label for="form-tel">telephone:</label> 
        <input type="tel" name="telephone" id="form-tel"class="textinput form-control">

        <label for="form-story">tell us about yourself:</label> 
        <textarea name="story" maxlength="600" id="form-story" placeholder="No more than 600 characters long"></textarea class="textinput form-control">
        
        <label for="sizes">size:</label>
        <select class="form-select" name="size" id="sizes">
            <option>5</option>
            <option>6</option>
            <option>7</option>
            <option>8</option>
            <option>9</option>
            <option>10</option>
            <option>11</option>
            <option>12</option>
            <option>13</option>
        </select> 
        
        <em>Sizes reflect standard US men's sizes</em>
            
        <label for="colors">Sneaker Color:</label>
        <fieldset id="colors">
            <legend>Color</legend>

            
            <div class="form-check">
            <label class="form-check-label"><input type="radio" class="form-check-input" name="color" value="red"> red</label>
            </div>

            <div class="form-check">
            <label class="form-check-label"><input type="radio" class="form-check-input" name="color" value="blue"> blue</label> 
            </div>

            <div class="form-check">
            <label class="form-check-label"><input type="radio" class="form-check-input" name="color" value="black"> black</label> 
            </div>

            <div class="form-check">
            <label class="form-check-label"><input type="radio" class="form-check-input" name="color" value="silver"> silver</label>
            </div>
        </fieldset>
            
            
        <label for="features">Add-on Features:</label>
        <fieldset id="features">
            <legend>Feature</legend>


            <div class="form-check">
            <label><input type="checkbox" class="form-check-input" name="feature" value="laces"> sparkly laces</label>
            </div>            

            <div class="form-check">
            <label><input type="checkbox" class="form-check-input" name="feature" value="logo" checked> metallic logo</label>
            </div>

            <div class="form-check">
            <label><input type="checkbox" class="form-check-input" name="feature" value="heels"> light-up heels</label>
            </div>

            <div class="form-check">
            <label><input type="checkbox" class="form-check-input" name="feature" value="mp3"> mp3-enabled</label>
            </div>
        </fieldset>
            <br>
        <button type="button" class="btn btn-warning" value="ENTER">ENTER</button>
    </form>
    <form action="/action_page.php">
        <div class="mb-3 mt-3">

        </div>
    </form>
</div>

</body>
</html>
