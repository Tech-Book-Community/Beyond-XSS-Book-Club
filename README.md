<h1 align="center">
《Beyond XSS：探索網頁前端資安宇宙》讀書會
</h1>

<p align="center">
  書籍：<a href="https://www.tenlong.com.tw/products/9786267383803">Beyond XSS：探索網頁前端資安宇宙</a>
</p>

<div align="center">
  <img src="https://cf-assets2.tenlong.com.tw/products/images/000/210/576/original/DM2441_3D-750x933_0.jpg?1719564123" wdith="250px" height="250px"/>
</div>



## 讀書會規則：
- 認領該章節的導讀人有**閱讀責任**及**主持責任**，需要讀完該章節並做筆記（簡報）於讀書會期間分享螢幕畫面帶著與會者導讀，並自行出題目引導大家回答與討論。
- 若導讀人需要請假請於讀書會舉行前一週「自行」到讀書會組別頻道中尋求章節交換。
- 認領該筆記工的人需紀錄讀書會期間的討論，並將筆記上傳至 [GitHub 討論區](https://github.com/Tech-Book-Community/Beyond-XSS-Book-Club/discussions)。
- 成員都至少導讀人及筆記工個當一次，意即本次讀書會最多招收 9 人，這 9 人都當過一次導讀人及筆記工，最少 4 人，最少人數則會各當過 2 次。
- 若讀書會成員需要請假請自行於讀書會組別頻道中請假。
- 參加讀書會請務必持有「書籍」（實體、電子皆可），若不打算買書僅閱讀網路資源請勿認領章節
- **若你在讀書會期間有可能會請假兩次以上，建議以「旁聽者」身份參加（意即不用認領章節，時間到上線即可）。**
- 2024/10/17（四）晚上 20:30 ~ 22:00 舉行第一次讀書會，每雙週四舉辦一次，共舉辦九次，2025/2/20 結束。

## 導讀人流程：
- 自我介紹
- 前次回顧
- 本次導讀
- 引導每個人至少發言一次
    - 自行出本次章節的題目讓每個人至少回答一次
- 成員問題討論
    - 引導成員對本次章節的疑問及討論
- 成員回饋導讀人即讀書會
- 次回日期、章節導讀人及筆記工預告

## 章節分工：

<table>
  <tr>
    <th>日期</th>
    <th>章節</th>
    <th>導讀人</th>
    <th>筆記工</th>
    <th>Slide</th>
    <th>Note</th>
  </tr>
  <tr>
    <td>2024/10/17</td>
    <td>
     1-1 瀏覽器的安全模型</br>
     1-2 前端資安還是得從XSS 開始談起才對味</br>
     1-3 再多了解 XSS 一點點</br>
     1-4 危險的 javascript: 偽協議
    </td>
    <td>Lois</td>
    <td>Mi</td>
    <td><a href="https://hackmd.io/@LoisChen/Sy6nvVmkkx#/">Slide</a></td>
    <td><a href="https://github.com/Tech-Book-Community/Beyond-XSS-Book-Club/discussions/1">Note</a></td>
  </tr>
  <tr>
    <td>2024/10/31</td>
    <td>
      2-1 XSS 的第一道防線：Sanitization</br>
      2-2 XSS 的第二道防線：CSP</br>
      2-3 XSS 的第三道防線：降低影響範圍(39)
    </td>
    <td>Steven</td>
    <td>Lulu</td>
    <td>Slide</td>
    <td>Note</td>
  </tr>
  <tr>
    <td>2024/11/14</td>
    <td>
     2-4 最新的XSS 防禦：Trusted Types 與內建的Sanitizer API</br>
     2-5 繞過你的防禦：常見的CSP bypass</br>
     2-6 繞過你的防禦：Mutation XSS</br>2-7 最強的 XSS：Universal XSS(34)
    </td>
    <td>Mi</td>
    <td>Steven</td>
    <td>Slide</td>
    <td>Note</td>
  </tr>
  <tr>
    <td>2024/11/28</td>
    <td>
      3-1 利用原型鏈的攻擊方式：Prototype Pollution</br>
      3-2 HTML 也可以影響JavaScript ？ DOM clobbering 介紹</br>
      3-3 前端的模板注入攻擊：CSTI(56)
    </td>
    <td>Shirley</td>
    <td>Sam</td>
    <td>Slide</td>
    <td>Note</td>
  </tr>
  <tr>
    <td>2024/12/12</td>
    <td>
      3-4 只用CSS 也能攻擊？ CSS injection 基礎篇</br>
      3-5 CSS injection 進階篇</br>3-6 就算只有HTML 也能攻擊？(44)
    </td>
    <td>Sam</td>
    <td>Monica</td>
    <td>Slide</td>
    <td>Note</td>
  </tr>
  <tr>
    <td>2024/12/26</td>
    <td>
      4-1 重中之重：Same-origin policy 與site</br>
      4-2 跨來源資源共用CORS 基本介紹</br>4-3 跨來源的安全性問題(48)
    </td>
    <td>Monica</td>
    <td>Lois</td>
    <td>Slide</td>
    <td>Note</td>
  </tr>
  <tr>
    <td>2025/01/19</td>
    <td>
      4-4 跨站請求偽造 CSRF 一點就通</br>
      4-5 Same-site cookie，CSRF 的救星？</br>
      4-6 從same-site 網站打進你家</br>4-7 有趣又實用的Cookie bomb(44)
    </td>
    <td>Yo0</td>
    <td>Wanye</td>
    <td>Slide</td>
    <td>Note</td>
  </tr>
  <tr>
    <td>2025/01/23</td>
    <td>
      5-1 你的畫面不是你的畫面：Clickjacking 點擊劫持</br>
      5-2 結合MIME sniffing 發起攻擊</br>
      5-3 前端供應鏈攻擊：從上游攻擊下游</br>5-4 網頁前端攻擊在Web3 上的應用</br>
      5-5 最有趣的前端旁路攻擊：XS-Leaks</br>5-6 XS-Leaks 的進階應用XS-Search 與Cache 
    </td>
    <td>Wanye</td>
    <td>Shirley</td>
    <td>Slide</td>
    <td>Note</td>
  </tr>
  <tr>
    <td>2025/02/06</td>
    <td>
      6-1 差一點的Figma XSS</br>6-2 繞過層層防禦：Proton Mail XSS</br>
      6-3 隱藏在Payment 功能中的Chrome 漏洞</br>
      6-4 從Prototype Pollution 到Bitrix24 XSS</br>
      6-5 PHP 底層bug 引發的Joomla! XSS
    </td>
    <td>Lulu</td>
    <td>Yo0</td>
    <td><a href="https://chuchiang.github.io/marp_xss/">Slide</a></td>
    <td><a href="https://github.com/Tech-Book-Community/Beyond-XSS-Book-Club/discussions/6">Note</a></td>
  </tr>
  <tr>
    <td>2025/02/20</td>
    <td>
      全書回顧討論會 - 齊畫架構圖
    </td>
    <td>Lois</td>
    <td></td>
    <td>Slide</td>
    <td>Note</td>
  </tr>
</table>

