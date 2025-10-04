<script setup>
</script>

<template>
  <div>
    <section class="hero">
      <div class="hero-content">
        <h1>提升你的健康力<br>健身與飲食控制</h1>
        <p>透過專業的健身與飲食課程，讓你科學管理體態與提升健康素質，打造理想身材與活力生活。</p>
        <div class="hero-buttons">
          <button class="btn-primary">索取體驗課程</button>
          <button class="btn-secondary">關於FitDiet？</button>
        </div>
        <div class="hero-stats">
          <div class="stat">
            <span>16,032</span>
            <p>參與學員</p>
          </div>
          <div class="stat">
            <span>10M</span>
            <p>完成健身計劃</p>
          </div>
          <div class="stat">
            <span>119</span>
            <p>服務國家／地區</p>
          </div>
        </div>
      </div>
      <div class="hero-image placeholder"></div>
    </section>

    <section class="benefits">
      <h2>線上健身·飲食規劃優勢</h2>
      <ul>
        <li>專業運動營養師設計</li>
        <li>零基礎也能輕鬆上手</li>
        <li>靈活學習、隨時隨地運動</li>
      </ul>
    </section>

    <section class="courses">
      <h2>熱門健身與飲食課程</h2>
      <div class="course-list">
        <div class="course-card">
          <div class="course-img placeholder"></div>
          <h3>入門增肌計劃：從飲食到訓練</h3>
          <span>30堂課 · 線上課程</span>
        </div>
        <div class="course-card">
          <div class="course-img placeholder"></div>
          <h3>科學減脂飲食：健康瘦身不復胖</h3>
          <span>24堂課 · 線上課程</span>
        </div>
        <div class="course-card">
          <div class="course-img placeholder"></div>
          <h3>健身菜單設計＆飲食規劃技巧</h3>
          <span>18堂課 · 線上課程</span>
        </div>
      </div>
    </section>

    <section class="instructor">
      <h2>成為專業教練</h2>
      <div class="instructor-img placeholder"></div>
      <p>用知識傳遞健康力量，分享運動與飲食專業，影響更多人信心邁向精實人生！</p>
      <button class="btn-primary">點此申請教練</button>
    </section>

    <section class="innovations">
      <h2>平台創新特色</h2>
      <div class="innovation-list">
        <div class="innovation-card">智能飲食紀錄</div>
        <div class="innovation-card">即時訓練成效追蹤</div>
        <div class="innovation-card">學員目標管理</div>
        <div class="innovation-card">科學化運動菜單</div>
        <div class="innovation-card">多元設備支援</div>
        <div class="innovation-card">專業教練互動</div>
      </div>
    </section>

    <section class="testimonial">
      <h2>學員分享見證</h2>
      <blockquote>
        「報名這個平台半年的成果超出預期，體脂肪大幅下降、身體更健康！專業的飲食建議讓飲食控制輕鬆許多。」
        <footer>王小明，健身學員</footer>
      </blockquote>
      <div class="testimonial-avatars">
        <div class="avatar placeholder"></div>
        <div class="avatar placeholder"></div>
        <div class="avatar placeholder"></div>
        <div class="avatar placeholder"></div>
        <div class="avatar placeholder"></div>
        <div class="avatar placeholder"></div>
        <div class="avatar placeholder"></div>
        <div class="avatar placeholder"></div>
      </div>
    </section>

    <section class="contact">
      <h2>線上諮詢</h2>
      <form id="subscribeForm">
        <input type="email" placeholder="請輸入電子郵件" required>
        <button type="submit" class="btn-primary">立即訂閱</button>
      </form>
    </section>
  </div>
</template>

<style scoped>
div, section, h1, h2, h3, h4, h5, h6, p, ul, li, span, button, input, form, blockquote {
  color: #ffffff;
}
.hero-buttons {
  margin-top: 1em;
  display: flex;
  justify-content: start;
}
.btn-primary {
  background: #2b00ff;
  color: #fff;
  border: none;
  border-radius: 6px;
  padding: 0.6em 1.4em;
  cursor: pointer;
}
.btn-secondary {
  background: #fff;
  color: #2b00ff;
  border: none;
  border-radius: 6px;
  margin-left: 0.5em;
  padding: 0.6em 1.4em;
  cursor: pointer;
}
.hero {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #383838;
  color: #fff;
  padding: 80px 40px;
  border-radius: 0 0 50% 50% / 0 0 6em 6em;
}
.hero-content h1 {
  font-size: 2.8em;
  line-height: 1.1em;
  text-align: start;
}
.hero-stats {
  display: flex;
  gap: 2em;
  margin: 2em 0;
}
.stat{
    background-color: #444444;
    padding: 1em 2em;
    border-radius: 12px;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.hero-image.placeholder {
  width: 340px;
  height: 340px;
  margin: 0 auto;
  background: #ddd;
  border-radius: 28px;
}
.benefits,
.courses,
.instructor,
.innovations,
.testimonial,
.contact {
  background: #383838;
  margin: 36px auto;
  border-radius: 24px;
  box-shadow: 0 2px 24px #e6e4fe44;
  padding: 44px 24px;
  width: 100%;
  max-width: 1440px;
}
.benefits ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 3em;
  padding: 0;
  margin-top: 1em;
  font-size: 24px;
}
.courses .course-list {
  display: flex;
  justify-content:space-around;
  gap: 2em;
}
.course-card {
  background: #444444;
  padding: 24px;
  border-radius: 16px;
  box-shadow: 0 2px 12px #eee;
  width: 270px;
}
.course-img.placeholder {
  width: 100%;
  max-width: 260px;
  height: 140px;
  margin-bottom: 1em;
  background: #ddd;
  border-radius: 10px;
}
.instructor-img.placeholder {
  width: 230px;
  height: 260px;
  margin: 0 auto 1em auto;
  background: #ddd;
  border-radius: 22px;
}
.innovation-list {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2em;
  justify-items: center;
}
.innovation-card {
  background: #444444;
  padding: 28px;
  border-radius: 16px;
  width: 100%;
  text-align: center;
  font-weight: 500;
  box-shadow: 0 2px 12px #e8e8fe99;
}
.testimonial {
  text-align: center;
}
.testimonial-avatars {
  display: flex;
  justify-content: center;
  gap: 1.2em;
  margin-top: 2em;
}
.avatar.placeholder {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  background: #ddd;
  display: inline-block;
}
.contact form {
  display: flex;
  gap: 1em;
  justify-content: center;
}
.contact input {
  width: 320px;
  padding: 0.75em;
  border-radius: 6px;
  border: 1px solid #ddd;
}
</style>
