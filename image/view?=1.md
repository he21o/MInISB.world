### 看下他们到底有多弱'智

------

笑死我了：

<div>
    <img class="dialog" src="https://user-images.githubusercontent.com/75876178/125181810-1e0c4300-e23b-11eb-9261-d2a0d310e286.png" width="100%">
    <div id="dialog_large_image"></div>
</div>

<script type="text/javascript">
    $(function () {
        $("img.dialog").click(function() {
            var large_image = '<img src= ' + $(this).attr("src") + '></img>';
            $('#dialog_large_image').html($(large_image).animate({ height: '50%', width: '50%' }, 500));
        });
    });
</script>
