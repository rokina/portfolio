<template>
  <div class="c-container">
    <div class="l-block01">
      <section class="c-box01">
        <h2 class="c-title01">Profile</h2>
        <dl class="c-dl01">
          <dt>名前</dt>
          <dd>Sato Hiroki</dd>
          <dt>生年月日</dt>
          <dd>1993/10/7/（27歳）</dd>
          <dt>実務経験</dt>
          <dd>仙台のWeb制作会社にて<br />フロントエンド5年目</dd>
          <dt>できること</dt>
          <dd class="c-imgList01">
            <img src="@/assets/img/icon_nuxt.svg" alt="" />
            <img src="@/assets/img/icon_vue.svg" alt="" />
            <img src="@/assets/img/icon_ts.svg" alt="" />
            <img src="@/assets/img/icon_js.svg" alt="" />
            <img src="@/assets/img/icon_html.svg" alt="" />
            <img src="@/assets/img/icon_css.svg" alt="" />
            <img src="@/assets/img/icon_laravel.svg" alt="" />
            <img src="@/assets/img/icon_wp.svg" alt="" />
            <img src="@/assets/img/icon_php.svg" alt="" />
          </dd>
          <dt>SNS</dt>
          <dd class="c-imgList02">
            <img src="@/assets/img/icon_github.svg" alt="" />
            <img src="@/assets/img/icon_twitter.svg" alt="" />
          </dd>
        </dl>
        <a href="#" class="c-more01">もっと<br />みる</a>
      </section>
      <div class="l-block02">
        <section class="c-box02">
          <h2 class="c-title01">Works</h2>
          <ul class="c-list01">
            <li class="c-list01__item">
              <a href="#">
                <img src="http://placehold.jp/200x126.png" alt="" />
                <p>ポートフォリオサイト</p>
              </a>
              <dl class="c-dl02">
                <dt>使用技術</dt>
                <dd>Nuxt.js TypeScript</dd>
              </dl>
            </li>
            <li class="c-list01__item">
              <a href="#">
                <img src="http://placehold.jp/200x126.png" alt="" />
                <p>テストテスト</p>
              </a>
              <dl class="c-dl02">
                <dt>使用技術</dt>
                <dd>Laravel CakePHP</dd>
              </dl>
            </li>
          </ul>
          <a href="#" class="c-more01">もっと<br />みる</a>
        </section>
        <section class="c-box03">
          <h2 class="c-title01">Contact</h2>
          <form action="" class="c-form01">
            <label for="">名前<input type="text" /></label>
            <label for="">メールアドレス<input type="text" /></label>
            <label for="">
              メッセージ
              <textarea name="" cols="30" rows="10">メッセージ</textarea>
            </label>
          </form>
        </section>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" src="../assets/scss/index.scss" scoped />
