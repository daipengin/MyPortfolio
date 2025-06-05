<script setup>
    import MainImage from "@/assets/img/page2/main.jpg";
    import sub1 from "@/assets/img/page2/sub1.jpg";
    import sub2 from "@/assets/img/page2/sub2.jpg";
    import sub3 from "@/assets/img/page2/sub3.jpg";
    import sub4 from "@/assets/img/page2/sub4.jpg";


</script>

<template>
    <div class="waku">
        <div class="setumei">
            <h1>ダーク胡蝶</h1>
            <p>概要</p>
            <p>ダーク胡蝶みたいな女性を描きました。</p>
            <p>制作期間</p>
            <p>2023年03月〜2023年03月</p>
            <p>制作にかかった期間</p>
            <p>〜1週間</p>
            <p>意識したこと</p>
            <p>冷たいが優しい女性を描きたいので、このイラストを作成しました。画面全体の彩度が低いが、目玉だけの彩度を高め、人の視線を奪うポイントになります。</p>

    <div class="wrapper">
        <div><img class="subimg" :src="sub1" style="width: 50%;" /><br>ラフ</div>
        <div><img class="subimg" :src="sub2" style="width: 50%;" /><br>顔の描き込み</div>
        <div><img class="subimg" :src="sub3" style="width: 50%;" /><br>髪の毛の描き込み</div>
        <div><img class="subimg" :src="sub4" style="width: 50%;" /><br></div>
    </div>
        </div>
        <div>
            <img class="Mainimg" :src="MainImage" style="width: 100%;" />
        </div> 
    </div>
    
    


    <h1><a href="#/">←TOP</a></h1> 
</template>

<style>
.Mainimg{
    height: 1129px;
    object-fit: cover;
}
.waku{
  display: grid;
  grid-template-columns: 50% 70%;
}
.wrapper {
  display: grid;
  grid-template-columns: 50% 50%;
}
</style>