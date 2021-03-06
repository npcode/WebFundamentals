---
title: "非對稱式的動畫計時"
description: "打破對稱性，可為您的專案帶來對比和吸引力。 瞭解將此套用至您專案的時機與方法。"
updated_on: 2014-10-21
key-takeaways:
  code:
    - 使用非對稱式動畫計時，為您的工作加入個性和對比。
    - 一律以有利於使用者互動的方式設計；當回應點選或點擊時，使用較短的持續時間，並在其他情況下則預留較慢的持續時間。

---
<p class="intro">
  為您動畫持續時間加入非對稱式，有助於您的使用者體驗，讓您在表達個性的同時，還能快速回應使用者互動。 它還能為操作感提供對比效果，讓互動更具視覺吸引力。
</p>

{% include shared/takeaway.liquid list=page.key-takeaways.code %}

像大多數的動畫「規則」，您應該多嘗試不同方法，以找出最適合您應用程式的方式，但牽涉到使用者體驗的問題時，使用者是眾所周知地沒耐心。 一般的經驗法則是 **一律迅速回應使用者的互動**。 有鑑於此，大多數情況下的使用者的行為為非對稱式，因此動畫也可能是。

例如，當使用者點選以叫出側邊欄導覽時，您應該儘快將之帶上螢幕，持續時間約為 100ms 左右。 然而當使用者關閉功能表時，您能以動畫慢速淡出檢視，例如以約 300ms 為目標。

相較之下，當您帶出一個強制回應檢視時，這通常是要顯示錯誤或一些其他重要訊息。 在這種情況下，您可能以更慢的速度帶出檢視，一樣是約 300ms 左右，但由使用者觸發的關閉動作，則應該要儘快發生。

那麼一般的經驗法則是：

* 針對使用者互動觸發的 UI 動畫，例如檢視轉換或顯示元素，應該擁有快速開場 (短持續時間)，但使用緩慢的出場 (較長持續時間)。
* 您的程式碼觸發的 UI 動畫，例如錯誤或強制回應檢視，應該擁有較慢的開場 (較長持續時間)，但使用快速出場 (短持續時間)。


