# 15-9-video

【css】z-index 叠加层；正数在上层， 负数在下层

【js】button滑块 slide
btn.addEventListener("click",function(){
    if (!btn.classList.contains ("slide")){
        btn.classList.add("slide");
        video.pause();
    }else{
        btn.classList.remove("slide");
        video.play();
    }
})

【preloader】
window.addEventListener("load",function(){
    preloader.classList.add("hide-preloader");
})
