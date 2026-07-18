---
layout: single
classes: wide
title: "Contact"
permalink: /contact/
header:
  overlay_image: /assets/Tools.jpeg # Resume에 썼던 근본 툴 사진을 그대로 활용하거나 다른 사진을 쓰세요!
  overlay_filter: 0.4
---

<div style="display: flex; flex-wrap: wrap; gap: 50px; margin-top: 40px;">

  <!-- 왼쪽: 메시지 전송 폼 (Let's Talk) -->
  <div style="flex: 1; min-width: 300px;">
    <h2>Let's Talk</h2>
    <form action="https://formspree.io/f/mrenqbqg" method="POST" style="display: flex; flex-direction: column; gap: 15px;">
      <div>
        <label style="display: block; margin-bottom: 5px; font-weight: bold;">Your Name *</label>
        <input type="text" name="name" required style="width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 4px;">
      </div>
      <div>
        <label style="display: block; margin-bottom: 5px; font-weight: bold;">Email *</label>
        <input type="email" name="_replyto" required style="width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 4px;">
      </div>
      <div>
        <label style="display: block; margin-bottom: 5px; font-weight: bold;">Message *</label>
        <textarea name="message" rows="6" required style="width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 4px; resize: vertical;"></textarea>
      </div>
      <button type="submit" class="btn btn--primary btn--large" style="align-self: flex-start; margin-top: 10px; padding: 12px 30px; border: none; cursor: pointer;">SEND MESSAGE</button>
    </form>
  </div>

  <!-- 오른쪽: 연락처 정보 (Contact Info) -->
  <div style="flex: 1; min-width: 250px;">
    <h2>Contact Info</h2>
    <div style="margin-top: 20px;">
      <a href="https://www.linkedin.com/in/jun-yoon-8ba283236/" target="_blank" style="font-size: 32px; color: #0077b5; text-decoration: none;">
        <i class="fab fa-linkedin"></i>
      </a>
      <div style="margin-top: 20px;">
        <strong style="display: block; margin-bottom: 5px;">Email Me</strong>
        <a href="mailto:yjs030909@gmail.com" style="color: #333; text-decoration: underline;">yjs030909@gmail.com</a>
      </div>
    </div>
  </div>

</div>
