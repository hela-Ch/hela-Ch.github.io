<!doctype html>
<html lang ="en">
    <head>
        <title> my to do List</title>
        <meta charset="UTF-8"/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
	    <link rel="stylesheet" type="text/css" href="toDoList.css"/>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css" integrity="sha512-1PKOgIY59xJ8Co8+NE6FZ+LOAZKjy+KY8iq0G4B3CyeY6wYHN3yt9PW0XpSriVlkMXe40PTKnXrLnZ9+fkDaog==" crossorigin="anonymous" />
    </head>
    <body>
        <header>
            <h1 id ="title">   My Todo List</h1>
        </header>
            <form>
            <div class="flexContainer">    
            <input type="text" name="inputField" id="inputField" placeholder ="Enter the work">
            <button id="todo_button" type="submit" disabled >
              <i class="fa fa-plus-square"></i>
                </button>  
                </div>
            <select  name ="categories" id ="category">
                <option value ="All"> All </option>
                <option value ="Not Done">  Not Done </option>
                <option value ="Done"> Done </option>
    
            </select>
            </form>
            <div class ="todo_container">
              <ul id ="todo_list"></ul>
            </div>
        
    <script src="toDoList.js"></script>
    </body>
    </html>
