<template>
    <div class="header">
        <div class="logo">
            <!-- <a href=""><img src="../assets/logo.png" alt=""></a>-->
        <h1>HuLaMotos</h1>
        </div>
        <div>
            <div class="compleinput">
                <form action="">
                    <input type="text" placeholder="Pesquisar...">
                    <button type="submit">Pesquisar</button>
               </form>
            </div>
        </div>
        <nav>
        <ul>
            <li><a href="#home">Vender</a></li>
            <li><a href="#contact">Contatos</a></li>
        </ul>
        </nav>
    </div>
</template>

<style scoped>

.header {
    display: flex;
    justify-content: space-around;
    align-items: center;

    height: 80px;
    background-color: black;
    color: white;
    padding: 10px;
}
h1{
    color: white;
    font-size: 30px;
    font-family: 'Courier New', Courier, monospace;
    font-weight: bold;
    text-align: center;
}
.logo img{
    width: 100px;
    height: 50px;
    border-radius: 20px;
}
 form input {
    width: 400px;
    padding: 5px;
    border-radius: 5px;
    border: none;
    margin-right: 10px;
    background-color: white;
 }

 form button {
    padding: 5px 10px;
    border-radius: 5px;
    border: none;
    background-color: #1eb44b;
    color: black;
    cursor: pointer;
 }
 .compleinput{
   
    background-color: white;
    border-radius: 20px;
    padding: 10px;
    
 }



nav ul {
    list-style: none;
    display: flex;
    gap: 50px;

    
    margin: 0;
    padding: 0;
}
nav {
   
}

nav ul li a{
    display: inline;
    color: white;
    text-decoration: none;
}


</style>