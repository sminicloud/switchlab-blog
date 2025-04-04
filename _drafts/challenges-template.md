# 📄 Challenges Template (`_drafts/challenges-template.md`)
---
title: "[{{ site.time | date: "%d-%m-%Y" }}] Challenges Faced"
date: {{ site.time | date: "%Y-%m-%d" }}
permalink: /project/challenges/
layout: single
sidebar:
  nav: "project"
---

## 🚧 Challenges Faced

### 😵 Problems
- Sidebar not rendering on About page
- Font Awesome icons not showing

### 🔍 Investigation
- Checked head.html, CDN, author-profile.html
- Found issue in `site.author` assignment

### ✅ Solution
- Corrected `author` value in `_config.yml`
- Re-enabled Font Awesome in head.html

---

*Last updated: {{ site.time | date: "%d-%m-%Y" }}*


<!-- ⚔️ challenges-template.md
🔥 역할:
개발 중 마주친 문제/이슈를 기록하는 페이지야.
문제 발생 → 해결 과정을 정리하면 추후 회고나 인터뷰 때도 유용해.

✅ 예시 내용:

어떤 문제였는지
디버깅 과정
해결 방법
이후 개선점 -->