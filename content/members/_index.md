---
title: "MEMBERS"
layout: "list"
---

<style>
  /* default: mobile (vertical) */
  .member-card {
    display: flex;
    flex-direction: column;
    align-items: center; 
    gap: 20px;
    margin-bottom: 50px;
    text-align: center;
  }

  .member-photo img {
    width: 200px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }

  .member-info h1 {
    margin-top: 0;
    margin-bottom: 10px;
    font-size: 1.4rem;
  }

  .member-info p {
    font-size: 1.1rem;
    line-height: 1.6;
    color: #333;
    text-align: left; /* 본문은 읽기 편하게 왼쪽 정렬 */
  }

  /* desktop: when min-width is 768 px; horizontal */
  @media (min-width: 768px) {
    .member-card {
      flex-direction: row;
      align-items: flex-start;
      text-align: left;
      gap: 30px;
    }
    
    .member-photo {
      flex-shrink: 0;
    }
  }
</style>

<div class="member-card">
  
  <div class="member-photo">
    <img src="/images/InjaeHong.jpg" alt="Injae Hong">
  </div>

  <div class="member-info">
    <h1><strong>Injae Hong / Principal Investigator</strong></h1>
    <p>
      Injae is an Assistant Professor in the Department of Psychology at Chungbuk National University. Her academic foundation was built at Yonsei University, where she earned her B.A. in Psychology and Philosophy, followed by an M.A. and Ph.D. under the mentorship of Dr. Min-Shik Kim. Prior to joining the faculty in 2026, she completed a postdoctoral fellowship with Dr. Jeremy M. Wolfe at Brigham and Women's Hospital / Harvard Medical School. Outside of research, Injae is a dedicated knitter who loves to craft clothes and dolls. While she is deeply committed to her current field, she's already manifesting her post-retirement plan: opening a little yarn store in town.
    </p>
  </div>

</div>
