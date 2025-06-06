# 🔥 News
- [2025/04/28] 🎉 Three papers (2 oral, 1 poster) were accepted by ICIC 2025!
- [2025/03/21] 🎉 One paper was accepted by ICME 2025!
- [2025/02/06] 🎉 One paper was accepted by IVC!
- [2025/01/04] 🎉 One paper was accepted by Information Fusion!
- [2024/12/21] 🎉 Three papers were accepted by ICASSP 2025!
- [2024/10/28] 🎉 One paper was accepted by ESWA!
- [2024/10/27] 🏆 We won the Outstanding Paper Award in the 5th CSIG ChinaMFS Conference.
- [2024/10/23] 🎉 One paper was accepted by ASOC!
- [2024/09/15] 🏆 Our team won the Top 20 Excellence Award in The Global Multimedia Deepfake Detection.
- [2024/08/26] 🎉 A proactive deepfake detection project was funded by NSFC.
- [2024/06/25] 🎉 One paper was accepted by PRCV 2024!
- [2024/05/31] 🎉 One paper was accepted by IPM!
- [2024/04/11] 🎓 I was selected as a doctoral supervisor.
- [2024/04/03] 🎤 I was invited to participate in the 12th Boda Information Forum and gave a report.


<!-- 最新消息（始终显示） -->
<div class="recent-news">
  <p>2025-06-06: 新增项目案例研究</p>
  <p>2025-06-01: 网站UI升级完成</p>
</div>

<!-- 旧消息（默认隐藏） -->
<details id="oldNews">
  <summary class="more-button">显示更多</summary>
  <div class="older-news">
    <p>2025-05-20: 参加开发者大会</p>
    <p>2025-04-15: 开源项目发布</p>
    <!-- 更多旧消息... -->
  </div>
</details>

<style>
  .more-button {
    cursor: pointer;
    color: #0366d6;
    font-weight: bold;
    padding: 8px 0;
    display: inline-block;
  }
  .older-news {
    margin-top: 10px;
    border-left: 2px solid #eee;
    padding-left: 15px;
  }
</style>

<script>
  // 自动隐藏超过5条后的内容
  document.addEventListener('DOMContentLoaded', () => {
    const newsItems = document.querySelectorAll('p');
    const maxRecent = 5; // 显示的最新消息数量
    
    if(newsItems.length > maxRecent) {
      for(let i = maxRecent; i < newsItems.length; i++) {
        newsItems[i].classList.add('older-news-item');
      }
    }
  });
</script>
