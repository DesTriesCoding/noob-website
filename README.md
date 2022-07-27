# noob-website
# Elements on my webpage get displaced when I minimize my web browser.

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" 
           content="width=device-width, initial-scale=1">
        <title>LMAO IM NEW TO THIS</title>
        <link rel="stylesheet" href="rushform.css" media="(min-width: 500px)" type="text/css">
        <style>@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');</style>
    </head>
  <body>
        <header>
            <div class="logo">
                <img src="lokasi-logo.png">
            <nav>
                <ul nav__links>
                    <li><a href="#">HELP</a></li>
                    <li><a href="#">HELP</a></li>
                    <li><a href="#">HELP</a></li>
                    <li><a href="#">HELP</a></li>
                </ul>
            </nav>
        </div>
        </header>
        <div class="container">
             <h2 id="current-time">12:00:00</h2>
            <div class="secondcontainer"></div>
            <div class="loginbox">
                <img src="avatar2.png" class="avatar" alt="avatar logo">
            <h2><marquee behavior="alternate">Hey there!<br>Sign into your account.</marquee></h2>
            <form>
                <p>Username:</p>
                <input id="userName" name="" type="text" placeholder="Enter Username">
                <p>Password:</p>
                <input id="Password" name="" type="password" placeholder="Enter Password"><br>
                <a href="#">LOGIN</a>
            </form>
            </div>
                <div class="link">
                    <a href="#" class="link">Omo ase, you don forget password. lmao!</a>
                </div>
                <img src="—Pngtree—airplane vector icon_3723570.png" class="plane">
        </div>
    <script>
            let time = document.getElementById("current-time");

            setInterval(() => {
            let d = new Date();            
            time.innerHTML = d.toLocaleTimeString();    
            }, 1000);
    </script>
  </body>
    
</html>
