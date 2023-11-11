<template>
    <div class="top-bar">
        <div class="title">Play Tecno</div>
        <div class="navbar">
            <div class="tab">Inicio</div>
            <div class="tab">Loja</div>
            <div class="tab">Categorias</div>
            <div class="tab">Carrinho</div>
            <div class="textfield">
                <div class="text">Pesquisar no site</div>
                <img class="ic-search" alt="Ic search" src="ic-search.svg" />
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: "TopBar",
};
</script>
<style>
.top-bar {
    align-items: center;
    background-color: #ffffff;
    display: flex;
    gap: 20px;
    height: 80px;
    justify-content: center;
    padding: 20px;
    position: relative;
    width: 1440px;
}

.top-bar .title {
    color: #000000;
    flex: 1;
    font-family: "Roboto-Medium", Helvetica;
    font-size: 28px;
    font-weight: 500;
    letter-spacing: 0;
    line-height: 36px;
    position: relative;
}

.top-bar .navbar {
    align-items: center;
    background-color: #ffffff;
    display: inline-flex;
    flex: 0 0 auto;
    gap: 40px;
    justify-content: center;
    position: relative;
}

.top-bar .tab {
    color: #000000;
    font-family: "Roboto-Regular", Helvetica;
    font-size: 16px;
    font-weight: 400;
    letter-spacing: 0;
    line-height: 24px;
    position: relative;
    white-space: nowrap;
    width: fit-content;
}

.top-bar .textfield {
    align-items: center;
    border: 1px solid;
    border-color: #0000001a;
    border-radius: 6px;
    display: flex;
    gap: 4px;
    justify-content: flex-end;
    padding: 8px;
    position: relative;
    width: 200px;
}

.top-bar .text {
    color: #00000080;
    flex: 1;
    font-family: "Roboto-Regular", Helvetica;
    font-size: 14px;
    font-weight: 400;
    letter-spacing: 0;
    line-height: 20px;
    margin-top: -1px;
    position: relative;
}

.top-bar .ic-search {
    height: 20px;
    position: relative;
    width: 20px;
}
</style>