<template lang="ja">
    <div id="post-wrapper">
        <section class="result">
            <h2 class="result-title">学習の成果</h2>
            <div class="comment">
                <h3 class="comment-title">本日の学習コメント</h3>
                <!-- <form action="">
                    <textarea name="" id="" cols="50" rows="3" placeholder="今日はテキスト第二章まで進めた！">
                    
                    </textarea>
                </form> -->
                <p style="white-space: pre-line;">{{ message }}</p>
                <textarea v-model="message" placeholder="ここに記入"></textarea>
            </div>
            <div class="study-hours">
                <h3 class="study-hours-title">学習時間</h3>
                <p style="white-space: pre-line;">{{ message }}</p>
                <textarea v-model="message" placeholder="ここに記入"></textarea>
            </div>
        </section>
        
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="">

</style>