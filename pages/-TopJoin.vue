<template>
    <div class="p-join">
        <h1>Join</h1>
        <div class="p-join__box">
            <h3>詳しく知りたい方は<br>まずは資料請求！</h3>
            <div class="p-claim">
                <a>資料請求</a>  
            </div>
            <div class="p-apply">  
                <a>申し込み</a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    .p-join {
        background-color: #E15F52;
        text-align: center;
        height: 560px;
        color: #FFFFFF;
    }
    .p-join h1 {
        padding-top: 50px;
        font-family: Voces,Voces;
        font-size: 40px;
    }
    .p-join__box {
        color: #FFFFFF;
        border: solid 4px #ffffff;
        margin-top: 50px;
        height: 346px;
        margin-right: 20px;
        margin-left: 20px;
    }
    .p-join__box h3 {
        font-size: 18px;
        margin-top: 60px;
        font-weight: bold;
        margin-bottom: 50px;
    }
    .p-claim {
        display: block;
        margin: 0 auto;
        width: 160px;
        height: 50px;
        color:#E15F52;
        background-color: #FFFFFF;
        padding-top: 8px;
        border: solid 2px;
        border-radius: 25px;
        font-size: 22px;
        font-weight: bold;
    }
    .p-apply {
        background-color: #E15F52;
        display: block;
        margin: 0 auto;
        width: 160px;
        height: 50px;
        color: #FFFFFF;
        padding-top: 8px;
        border: solid 2px;
        margin-top: 30px;
        border-radius: 25px;
        font-size: 22px;
        font-weight: bold;
    }
</style>