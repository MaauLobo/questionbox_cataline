<template>
    <body>
        <div class="container_main">
            <div class="imgastronauta">
                <img src="../assets/astronaut.svg" alt="Astronauta" />
            </div>

            <div class="text-container">
                <h3>Perguntas frequentes</h3>
                <p class="categoria">Escolha a categoria desejada</p>
            </div>

            <div class="button-container">
                <a href="#">
                    <img src="../assets/rocket.svg" alt="Icon 1" />
                    <span>Basecamp</span>
                </a>
                <a href="#">
                    <img src="../assets/astronaut-helmet.svg" alt="Icon 2" />
                    <span>Bootcamp</span>
                </a>
                <a href="#">
                    <img src="../assets/student-hat.svg" alt="Icon 3" />
                    <span>Cataline</span>
                </a>
                <a href="#">
                    <img src="../assets/partnership.svg" alt="Icon 4" />
                    <span>Parcerias</span>
                </a>
            </div>
        </div>
    </body>
</template>
  
<script>
export default {
    setup() {
        return {};
    },
};
</script>
  
<style>
.container_main {
    display: grid;
    grid-template-rows: auto 1fr auto;
    justify-content: center;
    align-items: center;
    height: 457px;
    width: 305px;
    background: rgb(64, 68, 81);
    background: linear-gradient(180deg, rgba(64, 68, 81, 1) 0%, rgba(38, 40, 44, 1) 100%);
    border-radius: 15px;
    box-shadow: 0px 10px 30px #3F445266;
    opacity: 1;
}

.imgastronauta {
    height: 280px;
    width: 280px;
}

.text-container {
    text-align: left;
    padding: 20px;
    grid-row: 2;
    margin-top: -380px;
}

h3 {
    color: #f5f6f8;
    font: normal normal bold 20px/24px Lato;
    letter-spacing: 0px;
}

.categoria {
    color: #f5f6f8;
    font: normal normal normal 13px/16px Lato;
}

.button-container {
    display: grid;
    grid-template-columns: 1fr;
    gap: 15px;
    justify-content: left;
    margin-top: -300px;
    padding: 20px;
    
}

a {
    display: flex;
    align-items: center;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    padding: 5px;
    width: 100%;
    cursor: pointer;
    transition: background-color 0.3s;
    
}

a:hover {
    background-color: #4d5559f3;

}

a img {
    margin-right: 10px;
    width: 25px;
    
}

span {
    flex-grow: 1;
    text-align: center;
    font-size: 14px;
    margin-right: 100px;
    font: normal normal normal 14px/14px Lato;
}</style>
  