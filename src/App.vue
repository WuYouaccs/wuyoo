<template lang="pug">
div(ref="affix")
  n-space(vertical)
    n-p.round 號
    n-p(style="font-weight: bold;color: #fff") @Yamaiddi
    n-p(style="color: #fff") 推特Twitter，Discord，instagram，Gmail，领英Linkedin等账号零售批发
    n-p(style="color: #fff") usdt支付请联系  <a href="https://t.me/yamaiddi" target="_blank" >@yamaiddi</a>
    n-p(style="color: red") 请确认添加tg客服的ＩＤ：@yamaiddi　　已有朋友因加错客服上当受骗。
  n-grid.content(cols="24" item-responsive responsive="screen" style="margin-top: 26px")
    n-gi(span="1 s:2 m:2 l:5 xl:6 2xl:6")
    n-gi(span="22 s:20 m:20 l:14 xl:12 2xl:12")
      n-space(size="large" vertical)
        .btn
          a(href="https://wuyoo.top/" target="_blank" )  www.wuyoo.top
        .btn
          a(href="https://t.me/yamaiddi" target="_blank")   请认准唯一客服@yamaiddi(可联系客服直接购买)        
        .btn
          a(href="https://t.me/accsou_com" target="_blank")   请关注telegram频道（补货通知，优惠码发放）        
        .btn
          a(href="https://t.me/wuyootop" target="_blank")   售前售后必看本教程频道（看不懂的不要购买）
                
    n-gi(span="1 s:2 m:2 l:5 xl:6 2xl:6")

  //- .footer
  div(style="position:fixed; left:0px; bottom:20px; width:100%; ")
    n-space(justify="center")
      n-text(style="color:#fff;text-align:center;font-size: 16px") © 2018-2022 Yamaiddi All Rights Reserved
        //- n-icon
        //-   <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 24 24"><path d="M22 11h-4.17l3.24-3.24l-1.41-1.42L15 11h-2V9l4.66-4.66l-1.42-1.41L13 6.17V2h-2v4.17L7.76 2.93L6.34 4.34L11 9v2H9L4.34 6.34L2.93 7.76L6.17 11H2v2h4.17l-3.24 3.24l1.41 1.42L9 13h2v2l-4.66 4.66l1.42 1.41L11 17.83V22h2v-4.17l3.24 3.24l1.42-1.41L13 15v-2h2l4.66 4.66l1.41-1.42L17.83 13H22v-2z" fill="currentColor"></path></svg>


</template>

<script setup>
import { reactive } from "vue"
const state = reactive({
   data: "4545"
})

const demo = () => {

}
</script>

<style lang="stylus" scoped>
.round
  border-radius: 50%
  width 90px
  height 90px
  background-color: black
  color: white
  padding: 20px
  font-size: 32px
  font-weight: bold
  margin:0 auto

.btn
  color: #fff
  background-color: #abb2b9
  padding 16px
  border: 2px solid rgb(66, 73, 73);
  border-radius: 8px
  box-shadow: rgb(66 73 73) 12px 12px 0px 0px;
  color: rgb(234, 242, 248);
  background-color: rgb(171, 178, 185);
  margin-bottom: 10px
  &:hover{-webkit-transform:translate(4px,4px);-ms-transform:translate(4px,4px);transform:translate(4px,4px);box-shadow:8px 8px 0 0 #424949;}/*!sc*/

  a
    color: #eaf2f8
    text-decoration: none
    font-size: 16px
    line-height:24px
  


  
</style>
