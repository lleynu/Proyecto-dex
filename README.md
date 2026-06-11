<!DOCTYPE html>
<html>
<head>
    <title>Mikkits</title>
</head>
<body>
    <header>
        <h1>Mikkits</h1>
        <figure>
            <img id="header-img" width="200" src="https://template.canva.com/EAGArm1sLvc/1/0/1600w-c5aK5eb_4JY.jpg" alt="Una imagen del logo del restaurante">
        </figure>
    </header>

    <nav>
        <a href="#menu">Menú</a>
        <br>
        <a href="#formulario-de-pedido">Formulario De Pedido</a>
    </nav>

    <main>
        <section class="Menus" id="menu">
            <h2>Menú</h2>
            <br>
            <article>
                <h3>MiniPanqueques</h3>
                <img width="150" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSBPSGvWRIe-akT1Lc6rImqq66_CE5Wl1W-5Q&s" alt="Una imagen de minipanques preparados">
                <p>Son unos panqueques en miniatura empolvados en azucar<br>y con un par de moras de acompañamiento<br><i>Precio: 120MX</i></p>
            </article>

            <article id="tostilocos">
                <br>
                <h3>TostiLocos</h3>
                <img width="170" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcREJ273s4Koa0ZBGlDJZhMuGScMVdPFA6OBCA&s" alt="Unos tostitos con queso elote y verduras">
                <p>Unos tostitos con muchos dulces picosos/dulces diversos<br>y una que otra cosa<br><i>Precio: 95MX</i></p>
            </article>

            <article id="crepas">
                <br>
                <h3>Crepas Dulces</h3>
                <img width="150" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT3a6S3pTrfd_DAeAQuVh7yqCqEJFdzJJ3NTA&s" alt="Una crepa con un par de fresas encima y un poco de crema encima">
                <p>Un tipo de crepa con phidadelphia adentro<br>y fresas con batido de crema encima<br>y algunas fresas partidas y con un poco de nutella encima<br><i>Precio: 130MX</i></p>
            </article>
            
            <hr style="width: 95%;">
        </section>

        <section class="Menus" id="formulario-de-pedido">
            <h2>Realice Su Pedido</h2>
            <br><br>
            <form>
                <label for="crepas">Crepas (130MX):</label>
                <input type="number" id="crepas" name="crepas" min="0" value="0">
                <br>

                <h3>Elige lo que quieres en tu crepa</h3>
        
                <label><input type="radio" name="saborcrepas" value="fresas">Fresas</label>
                <br>
                <label><input type="radio" name="saborcrepas" value="platano">Platano</label>
                <br>
                <label><input type="radio" name="saborcrepas" value="philadelphia">Philadelphia</label>
                <br>
                <label><input type="radio" name="saborcrepas" value="nutella">Nutella</label>
                <br>
                <label><input type="radio" name="saborcrepas" value="crema_batida">Crema batida</label>
                <br><br>

                <p><i>Si deseas hacer un pedido especial llena este espacio con lo que quieras que contenga tu pedido especificamente</i></p>
                <textarea name="pedido_especial_crepas" rows="5" cols="20" placeholder="pedido especial"></textarea>
                
                <br><br><br>

                <label for="tostilocos">TostiLocos (95MX):</label>
                <input type="number" id="tostilocos" name="tostilocos" min="0" value="0">

                <h3>Elige lo que quieres en tus tostilocos</h3>

                <label><input type="radio" name="ingredientestosti" value="queso">Queso</label>
                <br>
                <label><input type="radio" name="ingredientestosti" value="elote">Elote</label>
                <br>
                <label><input type="radio" name="ingredientestosti" value="gusanitos">Gusanitos</label>
                <br>
                <label><input type="radio" name="ingredientestosti" value="cacahuates">Cacahuates</label>
                <br>
                <label><input type="radio" name="ingredientestosti" value="mas_dulces">Mas dulces</label>
                <br>
                <label><input type="radio" name="ingredientestosti" value="chamoy">Chamoy</label>
                <br>
                <label><input type="radio" name="ingredientestosti" value="salsa">Salsa</label>
                <br><br>

                <p><i>Si deseas hacer un pedido especial llena este espacio con lo que quieras que contenga tu pedido especificamente</i></p>
                <textarea name="pedido_especial_tostilocos" rows="5" cols="20" placeholder="pedido especial"></textarea>

                <br><br><br><br>

                <label for="minipanqueques">MiniPanqueques (120MX):</label>
                <input type="number" id="minipanqueques" name="minipanqueques" value="0" min="0">

                <br>

                <h3>Elige lo que quieres en tus minipanqueques</h3>
                <label><input type="radio" name="ingremini" value="lechera">Lechera</label>
                <br>
                <label><input type="radio" name="ingremini" value="chocolate">Chocolate derretido</label>
                <br>
                <label><input type="radio" name="ingremini" value="nutella">Nutella</label>
                <br>
                <label><input type="radio" name="ingremini" value="cacao">Cacao(en polvo)</label>
                <br>
                <label><input type="radio" name="ingremini" value="fresas">Fresas</label>
                <br>
                <label><input type="radio" name="ingremini" value="moras">Moras</label>
                <br><br>

                <p><i>Si deseas hacer un pedido especial llena este espacio con lo que quieras que contenga tu pedido especificamente</i></p>
                <textarea name="pedido_especial_minipanqueques" rows="5" cols="20" placeholder="Pedido especial"></textarea>
                
                <br><br><br>

                <input type="submit" value="Ir a la pagina de pago">
            </form>
        </section>
    </main>

    <footer>
        <p><i>Hecho con amor por Titix</i></p>
    </footer>
</body>
</html>
