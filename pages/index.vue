<template>
  <div class="container">
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
          <dd>a</dd>
          <dt>SNS</dt>
          <dd>a</dd>
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
          <form action="">
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

<style lang="scss">
li,
ol {
  list-style: none;
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: left;
}

.l-block {
  &01 {
    width: 100%;
    height: 100vh;
    display: flex;
  }
  &02 {
    width: 50%;
  }
}

.c-box {
  &01 {
    width: 50%;
    padding: 200px;
    padding-left: 300px;
    background-color: #f2fef9;
    position: relative;
    &::before {
      content: '';
      position: absolute;
      background: url('~@/assets/img/account.svg');
      width: 100px;
      height: 100px;
      background-size: 100px;
      left: 165px;
      top: 300px;
    }
  }
  &02 {
    height: 50vh;
    padding: 120px;
    padding-left: 220px;
    background-color: #ffffff;
    position: relative;
    &::before {
      content: '';
      position: absolute;
      background: url('~@/assets/img/desktop.svg');
      width: 100px;
      height: 94px;
      background-size: 100px 94px;
      left: 65px;
      top: 230px;
    }
  }
  &03 {
    height: 50vh;
    padding: 120px;
    padding-left: 220px;
    background-color: #fcfcfc;
    position: relative;
    &::before {
      content: '';
      position: absolute;
      background: url('~@/assets/img/mail.svg');
      width: 100px;
      height: 95px;
      background-size: 100px 95px;
      left: 65px;
      top: 230px;
    }
  }
}

.c-title01 {
  margin-bottom: 30px;
}

.c-dl {
  &01 {
    display: flex;
    flex-wrap: wrap;
    dt {
      width: 120px;
      &:not(:first-of-type) {
        margin-top: 20px;
      }
    }
    dd {
      width: calc(100% - 120px);
      &:not(:first-of-type) {
        margin-top: 20px;
      }
    }
  }
  &02 {
    margin-top: 15px;
  }
}

.c-list01 {
  $root: &;
  display: flex;
  flex-wrap: wrap;
  &__item {
    width: 200px;
    & + #{$root}__item {
      margin-left: 20px;
    }
    a {
      text-decoration: none;
      color: #333;
    }
  }
}

.c-more01 {
  text-decoration: none;
  width: 68px;
  height: 68px;
  color: #333;
  border: 1px solid #dcdcdc;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  background: #fff;
  position: absolute;
  right: 200px;
  bottom: 200px;
}
</style>
