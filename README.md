# week3-day4-to-do
Day 4 project
<!DOCTYPE html>
<html lang="en">
<head>
    <title>To-Do List</title>
    <script src="scripts/scripts.js" defer></script>
</head>
<body>
    <div class="container">
        <h1>To-Do List</h1>
        <ul class="list">
            <li>Cooking<button class="del">x</button></li>
            <li>Shopping<button class="del">x</button></li>
            <li>Wash Clothes<button class="del">x</button></li>
        </ul>
    </div>
    <div class="form_container">
        <form class='form'>
            <h3>New To-Do:</h3>
            <input type="text" name="inputItem" id="inputItem">
            <button class="submitBtn">Submit</button>
        </form>
        <span id="out"/>
    </div>
</body>
</html>