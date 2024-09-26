<script>
    import { onMount } from "svelte";

    onMount(() => {
        redirect();
    });
    function redirect() {
        setTimeout(function () {
            window.location.href = "https://open.kakao.com/o/gHJyFmpg"; // 원하는 URL로 변경
        }, 2500); // 5000 밀리초 = 5초
    }
</script>

<div class="max-w-96 w-2/3 mx-auto mt-40 custom-font">
    <div class="my-8 text-center text-xl">
        <p>사이트 이동중입니다.</p>
        <p>잠시만 기다려주세요</p>
    </div>
    <img src="/loading.gif" alt="" />
</div>

<style>
    .custom-font {
        font-family: "GangwonEduPowerExtraBoldA", sans-serif;
    }

    @font-face {
        font-family: "GangwonEduPowerExtraBoldA";
        src: url("https://fastly.jsdelivr.net/gh/projectnoonnu/noonfonts_2201-2@1.0/GangwonEduPowerExtraBoldA.woff")
            format("woff");
        font-weight: normal;
        font-style: normal;
    }
</style>
