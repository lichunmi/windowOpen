# windowOpen  
```html
    <!-- 1 -->
    <a href="#" class="link" onclick="openLink();">새 탭에서 팝업탕 열기</a>
    <!-- 2 -->
    <a href="#" class="link" >새 탭에서 팝업탕 열기</a>
    <script>
        //  1
        const link = document.querySelector('.link');
        link.addEventListener('click', function(){
            window.open("https://www.naver.com/", "_blank", "width=500, height=500");
        })
        // 2
        function openLink(){
            window.open('https://ssd0908.tistory.com/entry/JavaScript-windowopen-%EC%83%88%EC%B0%BD%EC%9C%BC%EB%A1%9C-%EC%97%B4%EA%B8%B0-%EC%82%AC%EC%9A%A9%EB%B2%95', '_blank', "width=500, height=500");
        };
    </script>
```
