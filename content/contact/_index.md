---
title: "Contact"
summary: "联系信息"
showtoc: false
---

<div class="contact-wrap">

<h2 class="contact-title">Contact</h2>
<p class="contact-lead">填写表单或直接用以下方式联系我们。</p>

<div class="contact-card">
  <div class="contact-grid">
    <div>
      <div class="contact-label">Email</div>
      <div class="contact-value"><a href="mailto:info@wogen.eu">info@wogen.eu</a></div>
    </div>
    <div>
      <div class="contact-label">Phone</div>
      <div class="contact-value"><a href="tel:+491744964585">+49 1744964585</a></div>
    </div>
    <div>
      <div class="contact-label">Address</div>
      <div class="contact-value">Berlin, Germany</div>
    </div>
  </div>
</div>

<div class="form-card">
  <h3 style="margin-top:0">在线留言</h3>
  <p class="small-note">我们会在 1–2 个工作日内回复。</p>

  <form action="https://formspree.io/f/xpwkzazj" method="POST">
    <input type="hidden" name="_subject" value="New message from wogen.eu">
    <!-- 本地调试可先去掉 _next；上线后指向 /thanks/ -->
    <input type="hidden" name="_next" value="/thanks/">
    <input type="text" name="_gotcha" style="display:none">

    <div class="form-row">
      <label for="name">你的名字</label>
      <input id="name" class="form-input" type="text" name="name" required>
    </div>

    <div class="form-row">
      <label for="email">邮箱</label>
      <input id="email" class="form-input" type="email" name="email" required>
    </div>

    <div class="form-row">
      <label for="phone">电话（可选）</label>
      <input id="phone" class="form-input" type="tel" name="phone" placeholder="+49 …">
    </div>

    <div class="form-row">
      <label for="message">留言</label>
      <textarea id="message" class="form-textarea" name="message" rows="6" required></textarea>
    </div>

    <div class="form-actions">
      <button class="btn-primary" type="submit">发送</button>
    </div>

    <p class="small-note">提交即表示你同意我们仅将信息用于联系与答复，不会对外分享。</p>
  </form>
</div>

</div>