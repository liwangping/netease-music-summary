- querySelector 类选择器 
## h5
- 音频
- musicBtn.addEventListener('click',()=>{
            if(defautMusicPlay){
                bgm.play();
                // musicBtn.classList.remove('off');  //*1
            }else{
                bgm.pause();
                // musicBtn.classList.add('off');      //*2
            }
            defautMusicPlay = !defautMusicPlay;
            //切换
            musicBtn.classList.toggle('off');
            //toggle方法可以代替上面的*1和*2适用于对于一个事情有两种情况的结果，因为他改变的变量是boolean类型的，所以对于off这个样式有启用和不启用两种情况。所以适用
        })
-  <script src="https://cdnjs.cloudflare.com/ajax/libs/Swiper/4.0.2/js/swiper.min.js"></script>引入了Swiper插件可以说是非常厉害的插件了
- const swiper = new Swiper('.swiper-container',{
            direction: 'vertical',
        })//创建一个竖向滑动容器
- <div class="swiper-container">
        <div class="swiper-wrapper">
            <div class="swiper-slide">
                slide-1
            </div>
            <div class="swiper-slide">
                slide-2
            </div>
            <div class="swiper-slide">
                slide-3
            </div>
        </div>
    </div>//swiper分屏的创建方式

- .view {
    height: 100%;
    width: 100%;
    overflow: hidden;  /*overflow 属性规定当内容溢出元素框时发生的事情。hidden表示
    内容会被修剪，并且其余内容是不可见的。  */
    }

- background-image: linear-gradient(60deg,#f8ddd1,#faece5 73%,#fad2c0);
    /* 60度倾斜，左到右73%前两个颜色平分，剩下是27%后两种颜色 这是属于 */

-   transform: scale(.5);/* 会根据不同大小来进行压缩*/
    transform-origin: top right;/* 设置旋转元素的基点位置：右上方*/
    top:-140px;/*向下移140px*/

-   transform-origin: -16% -29%; //x轴左移16% y轴上移29% 
    animation: ani_qiuqian 6s ease-in-out infinite(无限播放);
    animation: name duration timing-function delay iteration-count direction fill-mode;
    //keyframe名称 完成动画所花费的时间 动画的速度曲线 在动画开始之前的延迟 动画应该播放的次数 是否应该轮流反向播放动画