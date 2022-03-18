<template>
    <div class="sidebar">
        <h1>Dashboard</h1>
        <div class="options">
            <div>
                <img src="https://cdn-icons-png.flaticon.com/512/25/25694.png" width="35">
            </div>
            <p>Início</p>
        </div>
        <div class="options">
            <div>
                <img src="https://cdn-icons-png.flaticon.com/512/786/786306.png" width="35">
            </div>
            <p>Primeiros passos</p>
        </div>
        <div class="options">
            <div>
                <img src="https://cdn-icons.flaticon.com/png/512/2989/premium/2989838.png?token=exp=1647605211~hmac=8647b106bbc823502b7e64f3636fd01f" width="35">
            </div>
            <p>Ao vivo</p>
        </div>
        <h2>Mercados</h2>
        <div class="options">
            <div>
                <img src="https://cdn-icons-png.flaticon.com/512/60/60484.png" width="35">
            </div>
            <p>Bolsa de Valores</p>
        </div>
        <div class="options">
            <div>
                <img src="https://cdn-icons.flaticon.com/png/512/5751/premium/5751029.png?token=exp=1647605452~hmac=2d5d2e7eda147edbe027b5085355e55a" width="35">
            </div>
            <p>Criptoativos</p>
        </div>
        <h2>Impostos</h2>
        <div class="options">
            <div>
                <img src="https://cdn-icons-png.flaticon.com/512/126/126179.png" width="35">
            </div>
            <p>DARF de Bolsa</p>
        </div>
        <div class="options">
            <div>
                <img src="https://cdn-icons.flaticon.com/png/512/5751/premium/5751029.png?token=exp=1647605452~hmac=2d5d2e7eda147edbe027b5085355e55a" width="35">
            </div>
            <p>DARF de cripto</p>
        </div>
        <div class="options">
            <div>
                <img src="https://cdn-icons-png.flaticon.com/512/44/44499.png" width="35">
            </div>
            <p>Renda variável</p>
        </div>
        <div class="options">
            <div>
                <img src="https://cdn-icons-png.flaticon.com/512/2979/2979648.png" width="35">
            </div>
            <p>Fundos imobiliários</p>
        </div>
        <h2>Declaração Anual</h2>
        <div class="options">
            <div>
                <img src="https://cdn-icons-png.flaticon.com/512/768/768818.png" width="35">
            </div>
            <p>IRPF</p>
        </div>
        <div class="options">
            <div>
                <img src="https://cdn-icons.flaticon.com/png/512/1896/premium/1896317.png?token=exp=1647605769~hmac=b302f5725f95bf2f6b7cd49b70b61c08" width="35">
            </div>
            <p>GCAP Cripto</p>
        </div>
    </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@800&display=swap');

.sidebar{
    width: 20%;
    background: rgba(255, 255, 255, 0.849);
    height: 950px;
    display: flex;
    flex-direction: column;
    border-radius: 7px;
}

h1{
    font-size: 2.5rem;
    margin-top: .1em;
    padding-bottom: .5em;
    font-family: 'Poppins', sans-serif;
    text-align: center;
}

h2{
    margin-top: 1.2em;
    margin-left: .5em;
}

.options{
    display: flex;
    margin-left: .5em;
    margin-right: .5em;
    align-items: center;
    margin-top: 1em;
    transition: .3s;
    cursor: pointer;
}

.options:hover{
    background: grey;
}

.options p{
    margin-left: .5em;
}


</style>