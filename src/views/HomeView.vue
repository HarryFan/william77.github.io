<script setup>
import DGButtonS1LG from '@/components/dg/DGButtonS1LG.vue';
import DGButtonS1MD from '@/components/dg/DGButtonS1MD.vue';
import DGButtonS1SM from '@/components/dg/DGButtonS1SM.vue';
import DGButtonS2LG from '@/components/dg/DGButtonS2LG.vue';
import DGButtonS2MD from '@/components/dg/DGButtonS2MD.vue';
import DGButtonS2SM from '@/components/dg/DGButtonS2SM.vue';
import DGButtonS3LG from '@/components/dg/DGButtonS3LG.vue';
import DGButtonS3MD from '@/components/dg/DGButtonS3MD.vue';
import DGButtonS3SM from '@/components/dg/DGButtonS3SM.vue';
import DGButtonTextLG from '@/components/dg/DGButtonTextLG.vue';
import DGButtonTextMD from '@/components/dg/DGButtonTextMD.vue';
import DGButtonTextSM from '@/components/dg/DGButtonTextSM.vue';
import DGTextBody from '@/components/dg/DGTextBody.vue';
import DGTextCaption from '@/components/dg/DGTextCaption.vue';
import DGTextH1 from '@/components/dg/DGTextH1.vue';
import DGTextH2 from '@/components/dg/DGTextH2.vue';
import DGTextH3 from '@/components/dg/DGTextH3.vue';
import DGTextSubtitle from '@/components/dg/DGTextSubtitle.vue';
import DGTextTitle from '@/components/dg/DGTextTitle.vue';
import OtherThickLine from '@/components/others/OtherThickLine.vue';

</script>

<template>
  <main class="container-fluid">
    <div class="row ">

      <!-- [ introduction ] -->
      <div class="col">
        <!-- goal -->
        <div class="dg-mt-32"><DGTextTitle>各位設計、程式開發人員好，</DGTextTitle></div>
        <div><DGTextBody>本專案試圖縮短開發時間與溝通成本，協助設計師能快速制定視覺系統，程式開發人員更能花時間專心在非視覺功能性開發上。</DGTextBody></div>
        
        <!-- advantage -->
        <div class="dg-mt-32"><DGTextTitle>優勢說明</DGTextTitle></div>
        <div><DGTextBody>1. 設計文件直接用程式碼建構，減少轉換成本。原先設計師規劃視覺系統供程式設計師參考，轉換成本為 1. 設計稿轉成 css. 2.多方構通校對的成本</DGTextBody></div>
        <div><DGTextBody>2. 8 point 設計規範，確定 padding、margin 保持 8px 的倍數，視覺將更有一致性。目前規範為 8, 16, 24, 32, 40, 48, 56 共 7 種距離</DGTextBody></div>
        <div><DGTextBody>3. 基礎 UI 語意化與元件化，讓設計師、工程師快速找到需要的元件，複製貼上即可生成相應元件</DGTextBody></div>
        <div><DGTextBody>4. 在 main.css 針對文字字型有全域設置，更改字型快速容易</DGTextBody></div>
        <div><DGTextBody>5. 若要開發新專案，僅需複製專案並且做少許設定即可完成新的 guideline 文件</DGTextBody></div>
        <div><DGTextBody>6. 開發高仿真原型非常容易，互動效果跟最後產出效果一致</DGTextBody></div>
        <div><DGTextBody>7. 若有兩個網站設計需保持一致性的外觀，只要兩個網站的設計文件一致即可</DGTextBody></div>
        <div><DGTextBody>8. 能確保 Responsive Design 的原型與最後設計成果一致</DGTextBody></div>
        <div><DGTextBody>9. 對切版人員是一大福音，大量縮短切版時間</DGTextBody></div>

        <!-- disadvantage -->
        <div class="dg-mt-32"><DGTextTitle>缺點說明</DGTextTitle></div>
        <div><DGTextBody>1. 需要有基礎程式語言開發能力，包含 css 與 js 框架的認知</DGTextBody></div>
      </div>
    </div>


    <!-- [ text settings ] -->
    <div class="row dg-mt-56">
      <div class="col">
        <OtherThickLine class="dg-bg-secondary3" thick="2px"/>
        <div class="dg-lh-5"><DGTextH2>文字設定</DGTextH2></div>
      </div>
    </div>

    <div class="row dg-mt-56">
      <div class="col">
        <div class="dg-lh-1"><DGTextTitle><i class="bi bi-app-indicator"></i> 字型 | font-family</DGTextTitle></div>
        <div class="dg-lh-1"><DGTextCaption class="dg-text-secondary3">請至 src/assets/main.css 查詢 --dg-font-family 並進行更改 </DGTextCaption></div>
        <hr class="dg-m-0 dg-mt-8 dg-mb-16 ">
        <div class="dg-lh-2"><DGTextBody>Arial</DGTextBody></div>
      </div>
    </div>

    <div class="row dg-mt-56">
      <div class="col">
        <div class="dg-lh-1"><DGTextTitle><i class="bi bi-app-indicator"></i> 字級 | font-size</DGTextTitle></div>
        <div class="dg-lh-1"><DGTextCaption class="dg-text-secondary3">可至 src/components/dg 下 DGTextH1.vue 裡進行 font-size 修正，其他依此類推</DGTextCaption></div>
        <hr class="dg-m-0 dg-mt-8 dg-mb-16 ">
        <div class="dg-lh-2"><DGTextH1>我是大標題 H1</DGTextH1> / <DGTextCaption>DGTextH1</DGTextCaption></div>
        <div class="dg-lh-2"><DGTextH2>我是大標題 H2</DGTextH2> / <DGTextCaption>DGTextH2</DGTextCaption></div>
        <div class="dg-lh-2"><DGTextH3>我是大標題 H3</DGTextH3> / <DGTextCaption>DGTextH3</DGTextCaption></div>
        <div class="dg-lh-2"><DGTextTitle>我是標題</DGTextTitle> / <DGTextCaption>DGTextTitle</DGTextCaption></div>
        <div class="dg-lh-2"><DGTextSubtitle>我是副標題</DGTextSubtitle> / <DGTextCaption>DGTextSubtitle</DGTextCaption></div>
        <div class="dg-lh-2"><DGTextBody>我是內文文字</DGTextBody> / <DGTextCaption>DGTextBody</DGTextCaption></div>
        <div class="dg-lh-2"><DGTextCaption>我是備註文字</DGTextCaption> / <DGTextCaption>DGTextCaption</DGTextCaption></div>
        <div class="dg-lh-2"><DGButtonTextLG>我是按鈕文字(大)</DGButtonTextLG> / <DGTextCaption>DGButtonTextLG</DGTextCaption></div>
        <div class="dg-lh-2"><DGButtonTextMD>我是按鈕文字(中)</DGButtonTextMD> / <DGTextCaption>DGButtonTextMD</DGTextCaption></div>
        <div class="dg-lh-2"><DGButtonTextSM>我是按鈕文字(小)</DGButtonTextSM> / <DGTextCaption>DGButtonTextSM</DGTextCaption></div>
      </div>
    </div>

    <div class="row dg-mt-56">
      <div class="col">
        <div class="dg-lh-1"><DGTextTitle><i class="bi bi-app-indicator"></i> 文字用色 | font-color</DGTextTitle></div>
        <div class="dg-lh-1"><DGTextCaption class="dg-text-secondary3">限制文字明度 5 個等級</DGTextCaption></div>
        <hr class="dg-m-0 dg-mt-8 dg-mb-16 ">
        <div class="dg-lh-4 dg-bg-80 dg-mb-16"><DGTextBody class="dg-ml-16 dg-text-0">.dg-text-0</DGTextBody></div>
        <div class="dg-lh-4 dg-bg-80 dg-mb-16"><DGTextBody class="dg-ml-16 dg-text-20">.dg-text-20</DGTextBody></div>
        <div class="dg-lh-4 dg-bg-80 dg-mb-16"><DGTextBody class="dg-ml-16 dg-text-40">.dg-text-40</DGTextBody></div>
        <div class="dg-lh-4 dg-bg-80 dg-mb-16"><DGTextBody class="dg-ml-16 dg-text-60">.dg-text-60</DGTextBody></div>
        <div class="dg-lh-4 dg-bg-80 dg-mb-16"><DGTextBody class="dg-ml-16 dg-text-100">.dg-text-100</DGTextBody></div>
      </div>
    </div>

    <!-- [ color settings ] -->
    <div class="row dg-mt-56">
      <div class="col">
        <OtherThickLine class="dg-bg-secondary3" thick="2px"/>
        <div class="dg-lh-5"><DGTextH2>顏色設定</DGTextH2></div>
      </div>
    </div>

    <div class="row dg-mt-56">
      <div class="col">
        <div class="dg-lh-1"><DGTextTitle><i class="bi bi-app-indicator"></i> 主要色調 | primary-color</DGTextTitle></div>
        <div class="dg-lh-1"><DGTextCaption class="dg-text-secondary3">呼籲使用者行動的按鈕、標題、重要資訊</DGTextCaption></div>
        <hr class="dg-m-0 dg-mt-8 dg-mb-16 ">
        <div class="dg-lh-4 dg-bg-primary1 dg-mb-16"><DGTextBody class="dg-ml-16 dg-text-100">.dg-bg-primary1</DGTextBody></div>
        <div class="dg-lh-4 dg-bg-primary2 dg-mb-16"><DGTextBody class="dg-ml-16 dg-text-100">.dg-bg-primary2</DGTextBody></div>
        <div class="dg-lh-4 dg-bg-primary3 dg-mb-16"><DGTextBody class="dg-ml-16 dg-text-100">.dg-bg-primary3</DGTextBody></div>
      </div>
    </div>

    <div class="row dg-mt-56">
      <div class="col">
        <div class="dg-lh-1"><DGTextTitle><i class="bi bi-app-indicator"></i> 次要色調 | secondary-color</DGTextTitle></div>
        <div class="dg-lh-1"><DGTextCaption class="dg-text-secondary3">次要按鈕、副標題、選單</DGTextCaption></div>
        <hr class="dg-m-0 dg-mt-8 dg-mb-16 ">
        <div class="dg-lh-4 dg-bg-secondary1 dg-mb-16"><DGTextBody class="dg-ml-16 dg-text-100">.dg-bg-secondary1</DGTextBody></div>
        <div class="dg-lh-4 dg-bg-secondary2 dg-mb-16"><DGTextBody class="dg-ml-16 dg-text-100">.dg-bg-secondary2</DGTextBody></div>
        <div class="dg-lh-4 dg-bg-secondary3 dg-mb-16"><DGTextBody class="dg-ml-16 dg-text-100">.dg-bg-secondary3</DGTextBody></div>
      </div>
    </div>

    <!-- [ common icons pickup ] -->
    <div class="row dg-mt-56">
      <div class="col">
        <OtherThickLine class="dg-bg-secondary3" thick="2px"/>
        <div class="dg-lh-5"><DGTextH2>圖示設定</DGTextH2></div>
      </div>
    </div>

    <div class="row dg-mt-56">
      <div class="col">
        <div class="dg-lh-1"><DGTextTitle><i class="bi bi-app-indicator"></i> 圖示揀選 | icons pickup</DGTextTitle></div>
        <div class="dg-lh-1"><DGTextCaption class="dg-text-secondary3">此為網站上常用的圖示選集，採用 bootstrap icons，應需要增加</DGTextCaption></div>
        <hr class="dg-m-0 dg-mt-8 dg-mb-16 ">
        <div class="dg-lh-2"><DGTextBody><i class="bi bi-search"></i> Search</DGTextBody> / <DGTextCaption>class="bi bi-search"</DGTextCaption></div>
        <div class="dg-lh-2"><DGTextBody><i class="bi bi-camera"></i> Camera</DGTextBody> / <DGTextCaption>class="bi bi-camera"</DGTextCaption></div>
        <div class="dg-lh-2"><DGTextBody><i class="bi bi-download"></i> Download</DGTextBody> / <DGTextCaption>class="bi bi-download"</DGTextCaption></div>
        <div class="dg-lh-2"><DGTextBody><i class="bi bi-person-circle"></i> Profile</DGTextBody> / <DGTextCaption>class="bi bi-person-circle"</DGTextCaption></div>
        <div class="dg-lh-2"><DGTextBody><i class="bi bi-gear"></i> Settings</DGTextBody> / <DGTextCaption>class="bi bi-gear"</DGTextCaption></div>
        <div class="dg-lh-2"><DGTextBody><i class="bi bi-card-image"></i> Image</DGTextBody> / <DGTextCaption>class="bi bi-card-image"</DGTextCaption></div>
        <div class="dg-lh-2"><DGTextBody><i class="bi bi-geo-alt"></i> Location</DGTextBody> / <DGTextCaption>class="bi bi-geo-alt"</DGTextCaption></div>
        <div class="dg-lh-2"><DGTextBody><i class="bi bi-trash3"></i> Trash</DGTextBody> / <DGTextCaption>class="bi bi-trash3"</DGTextCaption></div>
      </div>
    </div>

    <!-- [ button design ] -->
    <div class="row dg-mt-56">
      <div class="col">
        <OtherThickLine class="dg-bg-secondary3" thick="2px"/>
        <div class="dg-lh-5"><DGTextH2>按鈕設計</DGTextH2></div>
      </div>
    </div>

    <div class="row dg-mt-56">
      <div class="col">
        <div class="dg-lh-1"><DGTextTitle><i class="bi bi-app-indicator"></i> 按鈕尺寸 | icon-size</DGTextTitle></div>
        <div class="dg-lh-1"><DGTextCaption class="dg-text-secondary3">按鈕尺寸將分成三個等級，包含 DGButton[style]LG、DGButton[style]MD、DGButton[style]SM 大中小 3 個 x style 3 個，共 9 個</DGTextCaption></div>
        <hr class="dg-m-0 dg-mt-8 dg-mb-16 ">
        <div class="dg-lh-4"><DGButtonS1LG>我是按鈕文字</DGButtonS1LG> / <DGTextCaption>DGButtonS1LG</DGTextCaption></div> 
        <div class="dg-lh-4"><DGButtonS1MD>我是按鈕文字</DGButtonS1MD> / <DGTextCaption>DGButtonS1MD</DGTextCaption></div> 
        <div class="dg-lh-4"><DGButtonS1SM>我是按鈕文字</DGButtonS1SM> / <DGTextCaption>DGButtonS1SM</DGTextCaption></div> 

        <div class="dg-lh-4"><DGButtonS2LG>我是按鈕文字</DGButtonS2LG> / <DGTextCaption>DGButtonS2LG</DGTextCaption></div> 
        <div class="dg-lh-4"><DGButtonS2MD>我是按鈕文字</DGButtonS2MD> / <DGTextCaption>DGButtonS2MD</DGTextCaption></div> 
        <div class="dg-lh-4"><DGButtonS2SM>我是按鈕文字</DGButtonS2SM> / <DGTextCaption>DGButtonS2SM</DGTextCaption></div> 

        <div class="dg-lh-4"><DGButtonS3LG>我是按鈕文字</DGButtonS3LG> / <DGTextCaption>DGButtonS3LG</DGTextCaption></div> 
        <div class="dg-lh-4"><DGButtonS3MD>我是按鈕文字</DGButtonS3MD> / <DGTextCaption>DGButtonS3MD</DGTextCaption></div> 
        <div class="dg-lh-4"><DGButtonS3SM>我是按鈕文字</DGButtonS3SM> / <DGTextCaption>DGButtonS3SM</DGTextCaption></div> 
      </div>
    </div>

    <!-- [ form inputs design ] -->
    <div class="row dg-mt-56">
      <div class="col">
        <OtherThickLine class="dg-bg-secondary3" thick="2px"/>
        <div class="dg-lh-5"><DGTextH2>表單元件設計</DGTextH2></div>
      </div>
    </div>

    <div class="row dg-mt-56">
      <div class="col">
        <div class="dg-lh-1"><DGTextTitle><i class="bi bi-app-indicator"></i> 單選按鈕 | Radio Button</DGTextTitle></div>
        <div class="dg-lh-1"><DGTextCaption class="dg-text-secondary3"></DGTextCaption></div>
        <hr class="dg-m-0 dg-mt-8 dg-mb-16 ">
        <div class="dg-lh-2">
          <input type="radio" name="sex" value="male" checked/> 男生
          <input class="dg-ml-16" type="radio" name="sex" value="female"/> 女生 
        </div>
      </div>
    </div>

    <div class="row dg-mt-56">
      <div class="col">
        <div class="dg-lh-1"><DGTextTitle><i class="bi bi-app-indicator"></i> 複選框 | Checkbox</DGTextTitle></div>
        <div class="dg-lh-1"><DGTextCaption class="dg-text-secondary3"></DGTextCaption></div>
        <hr class="dg-m-0 dg-mt-8 dg-mb-16 ">
        <div class="dg-lh-2">
          <input type="checkbox" name="fruit" value="apple" checked/> 蘋果
          <input class="dg-ml-16" type="checkbox" name="fruit" value="banana"/> 香蕉 
          <input class="dg-ml-16" type="checkbox" name="fruit" value="pineapple"/> 鳳梨 
        </div>
      </div>
    </div>

    <div class="row dg-mt-56">
      <div class="col">
        <div class="dg-lh-1"><DGTextTitle><i class="bi bi-app-indicator"></i> 單行文本輸入框 | Text Input</DGTextTitle></div>
        <div class="dg-lh-1"><DGTextCaption class="dg-text-secondary3">請於 main.css 找尋 common ui 並設定</DGTextCaption></div>
        <hr class="dg-m-0 dg-mt-8 dg-mb-16 ">
        <div class="dg-lh-2">
          <input class="dg-pl-8 dg-pr-8" type="text" value="單行文本輸入框" placeholder="請輸入文字"/> 
        </div>
      </div>
    </div>

    <div class="row dg-mt-56">
      <div class="col">
        <div class="dg-lh-1"><DGTextTitle><i class="bi bi-app-indicator"></i> 多行文本輸入框 | Textarea</DGTextTitle></div>
        <div class="dg-lh-1"><DGTextCaption class="dg-text-secondary3">請於 main.css 找尋 common ui 並設定</DGTextCaption></div>
        <hr class="dg-m-0 dg-mt-8 dg-mb-16 ">
        <div class="dg-lh-2">
          <textarea class="dg-pl-8 dg-pr-8">多行文本輸入框</textarea>
        </div>
      </div>
    </div>

  </main>
</template>

<style scoped>
</style>