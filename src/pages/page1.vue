<script setup>
    import MainImage from "@/assets/img/page1/main.jpg";
    import sub1 from "@/assets/img/page1/sub1.jpg";
    import sub2 from "@/assets/img/page1/sub2.jpg";
    import sub3 from "@/assets/img/page1/sub3.jpg";
    import sub4 from "@/assets/img/page1/sub4.jpg";


</script>

<template>
    <div class="waku">
        <div class="setumei">
            <h1>黒パール</h1>
            <p>概要</p>
            <p>黒パールをイメージし、強気の女の子のデザインをしました。</p>
            <p>制作期間</p>
            <p>制作にかかった期間</p>
            <p>〜1週間</p>
            <p>今年(2023)のイラスト集の表紙創作</p>
            <p>表紙のため描いたイラストなので、人の目をしっかり掴めるイラストがいいと思いました。今年「パール」という洋画を観て、女性の本質、あるいは「本当に自分」に考えてみて、イラスト創作をしました。</p>

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