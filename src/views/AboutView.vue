
import DGTextBody from '@/components/dg/DGTextBody.vue';
<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col">
        <div class="dg-m-32">
          <DGTextBody class="dg-w-60">
            <p>本專案試圖縮短開發時間與溝通成本，協助設計師能快速制定視覺系統，程式開發人員更能花時間專心在非視覺功能性開發上。</p>
            <p>Design Guideline 網頁版設計原由是基於切版工作常常被設計師與工程師互踢皮球，到底切版應該是設計師還是工程師的工作。</p>
            <p>若切版工作歸屬於設計師，可能 css 無法如工程師預期符合後續開發所需，工程師會依照需要重新刻一個版本；</p>
            <p>若切版工作歸屬於工程師，設計師提出設計稿方便工程師對位，可能包含尺寸、間距等細節，反覆修正來回溝通費時費力，甚至放棄用憑感覺的方式來對位。</p>
            <p>為了解決問題，我提出了 Design Guideline 網頁版，協助處理切版歸屬難題。</p>
            <p>本專案的 Home Page，制定一套設計準則，將大部分設計師與工程師需溝通的文件用 html 來呈現，裡頭包含文字、顏色、圖示、按鈕、表單等，</p>
            <p>大部分元件設計樣式的工本專案已經制定好了，設計師可以依個人需求完成文字、顏色、圖示、按鈕、表單的視覺修定；</p>
            <p>很快的設計師可以快速配置頁面如 Sample Page，多數元件只要 copy paste 和微調，沒錯！</p>
            <p>對設計師而言不用再繪製 Design Guideline 和對位圖，僅需進行設定與切版；</p>
            <p>對程式設計師而言大幅減少溝通成本，發現設計缺失馬上做設定修正，非常簡單！工程師可專注在功能性開發上。</p>
          </DGTextBody>
        </div>
        <div class="dg-m-32"><DGTextBody>design by William77</DGTextBody></div>
      </div>
    </div>
  </div>
</template>
