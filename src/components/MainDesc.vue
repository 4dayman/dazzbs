<template>
    <div class="main_desc_wrapper">
        <div class="main_desc">
            <div class="desc_left">
                <h2>Сяйво твоєї краси</h2>
                <h3>Здоровья.Краса</h3>
                <p>Б’юті-простір, що надихає</p>
            </div>
            <div class="desc_right">
                <img src="@/assets/Fotoram.io.png" alt="">
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.main_desc_wrapper{
margin-top: 60px;
}
.main_desc {
    position: relative;
    max-width: 1230px;
    padding: 0 20px;
    display: grid;
    margin: 0 auto;
    grid-template-columns: 1fr 1fr;
    margin-bottom: 50px;
    @media (max-width: 768px) {
        grid-template-columns: 1fr;
    }
}
.desc_left,
.desc_right {
    max-width: 100%;
}
.desc_left{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    text-align: left;
    color: #000000;
    @media (max-width: 768px) {
        align-items: center;
        text-align: center;
        background-size: cover;
    }
    h3{
        margin: 25px 0;
    }
    p{
        font-weight: 400;
        font-size: 16px;
        line-height: 180%;
        letter-spacing: 0.02em;
    }
}
.desc_right{
    img{
        width: 100%;
        height: 100%;
        object-fit: contain;
        opacity: 0.3;
    }
}
</style>