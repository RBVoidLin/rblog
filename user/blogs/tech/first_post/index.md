---
title: Start From Hereð Site Building History 
description: The first post about how this website wants to share and introduce the site Building History
summary: ð å¼å¾æ¶ç¥çç¬¬ä¸ç¯æç« 
published: '2022-12-26T00:00:00.000+08:00'
updated: '2023-02-25T14:00:00.000+08:00'
cover: ./cover.jpg
coverStyle: 'TOP'
coverCaption: Photo by <a href="https://unsplash.com/@etiennegirardet?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Etienne Girardet</a> on <a href="https://unsplash.com/s/photos/motivation?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
tags:
  - [QWER]
---

<script lang="ts">
  import Youtube from '$lib/components/youtube.svelte'
  import Spotify from '$lib/components/spotify.svelte'
  import Custom from '$custom/custom.svelte'
  const const_variable = 999;

  import Folder from '$lib/components/folder.svelte'

  let configFolder = [
    { name: 'QWER.config.js', icon: 'i-vscode-icons-file-type-typescript-official' },
    { name: 'site.ts', icon: 'i-bxs-file-js' }
  ]
</script>

## ð Foreword
:::tip
Welcome! <br/>
éè£¡ææ¾æ¾å¹³å¸¸æ¬æ¥­çè¸©åç´éåæ°ç¼ç¾çé·æ±è¥¿<br/>
é¤æ­¤ä¹å¤éææ¾æ¾ååããè·è·è·³è·³è½è½ç«ç«çç´é<br/>
å¯ä»¥å©ç¨é¦é ä¸é¢çðææéç<kbd>tag</kbd>ð·ï¸æ¾æ¾ææ²æè½å¹«ä¸å¿çæ±è¥¿<br/>
:::

> <h2>éç¯æç« æç°¡å®ç´ééåç¶²ç«åºççéç¨</h2>

## æååæ­¡çåå
> å¹«ç¶²ç«æåé ç¼åå¥½è¨çåå­å§

æééæ¯é¸æ namecheap ä»åå®¶çæåï¼éå¸¸è¶ç­çåå­è¶å¥½è¨~~å»¢è©±~~ä½ä¹ææ¯è¼è²´<br/>
ç¶ç¶ä½ æ³è¦æ´ç«æ³¡çä¸­æååä¹èªç¶æ¯æ²åé¡
<ImgZoom src="/tech/first_post/namecheap.webp" alt="namecheap" class="h-full object-cover" width="500"/>

<br/>

æ¥èåªè¦æ¿åºé­æ³å°å¡æ½æ³ä¸ä¸å°±å¯ä»¥é²å¥DashBoardé é¢ç®¡çååäº
<ImgZoom src="/tech/first_post/namecheap_manage.webp" alt="Namecheap_manage" class="h-full object-cover" width="500"/>



## ç³è«ä¸»æ©
> å¹«ç¶²ç«æ¾åå®¶

æ±ºå®å¥½åå­å¾ï¼æåå°±å¯ä»¥åå¾é¦¬æ¯æ´éæ±éå­å¡çç¬¬äºå±¤äºï¼ä¸è¦è®ç¶²ç«æµè½è¡é ­<br/>
**éé¨ä»½é¸æå°±å¾å¤äºï¼å¯ä»¥é¸æè±é¢æ¶ç½ææ¯å¤è±é»å·¥å¤«æ¾æ¾ææ²æè½~~ç½å«ç~~**<br/>

### è¦æ ¼åOCIè¨»å
çµæ¼ï¼ä¸å¿ç½å«çææ¾å°ç²éª¨æé²ç«¯æå Oracle Cloud Infrastructure (OCI) éçæçï¼ä¾ççä»çè¦æ ¼å§<br/>

:::info 
CPU Arm Ampere A1 `4 OCPU` ã `24GB` è¨æ¶é« ã`200GB`å²å­ç©ºé å æ¯æ10TBåè²»æµé 
:::

æå±~éç¨®è¦æ ¼å¦ææä½æ¯ä¸è¬ä»è²»çVPSä¹æ¯è¦ 500 NTD/æ ä»¥ä¸äº<br/>
OK! æ¢ç¶æ±ºå®äºå°±éå§ç³è«ã ä¾å§!!! å¤¢éå§çå°æ¹
[OCI free VPS ç³è«å¥å£](https://www.oracle.com/cloud/free/)
<ImgZoom src="/tech/first_post/OCI.webp" alt="OCI" class="h-full object-cover" width="500"/>


å¾ä¸é¢ç<kbd>Start for free</kbd>Buttonéå§ä½ çæç¨ï¼ä¸æ¹æ¢åäºä¸äºå¯è½ç¢°å°ççæ³åè§£æ±ºæ¹æ³<br/>

- è¨»åæ¶ä¸å°é©è­ä¿¡ <kbd>â</kbd> éåæé»çï¼åªè½éå¯å¹¾æ¬¡ææåä¿¡ç®±äº
- ä¿¡ç¨å¡è¢«æ£é¢äº <kbd>â</kbd> è¨»åéç¨ä¸­æ¯éè¦æä¾ä¿¡ç¨å¡ä¿¡æ¯çï¼ä»æåæ£ä¸å¡ç¾éä¹å¾æåè½éçµ¦ä½ 
- å¸³æ¶åµå»ºå¤±æ <kbd>â</kbd> ç¡éä¸è¦å¨åä¸å°è¨­åé²è¡ä¸åçå¸³èè¨»åï¼ææ©èç¢¼è·ä¿¡ç¨å¡è³è¨åç

:::caution æ¥µãåº¦ãéãè¦
å¨é¸Regionçæåç¡éä¸è¦ææ¥æ¬ãæ°å å¡ç­å°ï¼å çºåè²»ç¸½æ¯è½å¸å¼å°ä¸å åæéæ¨£çäºº(? <br/>
èéäºé¢å°ç£è¼è¿æ©æ¿çè³æºå¾å¾é½æ¯ææ©è¢«æ¶åç<br/>
ééæ¯è¼å»ºè­°åéçé¸é 
:::

### åµå»ºVPS
åµå»ºæåå¾æåå°±å¯ä»¥éå§ç³è«ä¸»æ©ç©ºéå¦<br/>
åµå»ºçå§å®¹å¯ä»¥åèä¸æ¹çåä¾<br/>
1. Get Started<kbd>â</kbd>æ»¾è¼ªå¾ä¸æ»é»é¸ Create a VM instance
![OCI_Start](/tech/first_post/oci_start.mp4)

2. æ±ºå®ä½ vpsçåç¨±
3. Image and shape<kbd>â</kbd>Change image é¸æä½ è¦çOS<kbd>â</kbd>Change shape é¸æA1.Flex ç¶å¾ææ»¿
> éè£¡å¦ææ³åè¤æ¸åvpsï¼å¯ä»¥å¨ééèª¿éè³æºï¼ä¸éå¦æåªæ³æä¸åç·´ç¿å°±å¨çæ»¿å§

4. Add SSH keys <kbd>â</kbd> Generate a key pair to me <kbd>â</kbd> Save private and public key
> éåæ­¥é©ä¹å¾éè¦å!! OCI VPSåæä¾sshç»å¥ï¼æ²ækeyå­å¥½å°æç»ä¸é²å»å°±GGæ¹

![choose_shape](/tech/first_post/choose_shape.mp4)
<ImgZoom src="/tech/first_post/vps_all.webp" alt="OCI_Get_Started" class="h-full object-cover" width="500"/>



å®æä¸è¿°çæä½å¾æä¸<kbd>Create</kbd> <br/>
éæå°±æ¯èé©éæ°£çæåäºï¼å¦æä»ä¸çµ¦éï¼ä½ æä»¥ä¸å¹¾é é¸æ
1. åºå»å¤æ¶æ¶å¹¾ä½èå¥¶å¥¶éé¦¬è·¯
2. æä¸åRegionåä¾ä¸æ¬¡
3. ç¡¬ç¢°ç¡¬ï¼createå°éçºæ­¢ <kbd>â</kbd>éåé¨åå¯ä»¥å¯«è³æ¬è§£æ±ºï¼ä½æåæ¹å¤©åèå§

### Puttyç»å¥è¨­å®
å¤©å! æ­åç¬éæé è³½çéæ®µ<br/>
åä¾ççç®åçææå§! æåå¯ä»¥è§å¯ç®åvpsççæåç¸éè³è¨ï¼å¶ä¸­å¯ä»¥åæpublic IPè¨èµ·ä¾ï¼ç­ç­ç»å¥å°±æç¨å°äº<br/>
<ImgZoom src="/tech/first_post/vps_status.webp" alt="VPS_status" class="h-full object-cover" width="500"/>

å©ä¸å°±æprivate keyéé PuTTY Key Generatorè½ææputtyè½çæç.ppkæ ¼å¼å°±å¯ä»¥ç»å¥äº<br/>
- ä¸è¼ä¸¦éåPuTTY Key Generator <kbd>â</kbd> æ¿æppk file version to 2 <kbd>â</kbd> load and save to .ppk file
<ImgZoom src="/tech/first_post/putty_key_gen.webp" alt="Putty_Key_Gen" class="h-full object-cover" width="500"/>
- è¼¸å¥ååæå°çpublic IP <kbd>â</kbd> å¨Authè¼å¥ååçæç.ppk <kbd>â</kbd> é»é¸<kbd>Open</kbd>é²è¡é£ç·
<ImgZoom src="/tech/first_post/putty_login.webp" alt="PuttPutty_Login_OK" class="h-full object-cover" width="500"/>
ððð çµæ¼æåç»å¥æ¹ððð
<ImgZoom src="/tech/first_post/putty_ok.png" alt="Putty_OK" class="h-full object-cover" width="500"/>

## é¨ç½²é¨è½æ ¼
éæ¯æå¨GITHUB PAGESå°å°è¦è¦æç¼ç¾çå¥½æ<br/>
æå¥æ¼å¸¸è¦çåç«¯æ¡æ¶ä¸å·¨é ­ ReactãVueãAngularå¨é¢è¨Virtual DOMçæè½åé¡<br/>
è©²æ¨¡æ¿ä½¿ç¨çæ¯Svelteï¼ç°¡å®ç²æ´å°éééæç·¨è­¯çæ¹å¼æ¨æ£äºVirtual DOMçæä½<br/>
èå¯¦æ¯åç·´ç¿çå¥½å°è±¡<br/>
### ééä»ç´¹

:::tip
[QWER](https://github.com/kwchang0831/svelte-QWER)

ä½¿ç¨ SvelteKit è â¤ æé çé¨è½æ ¼çæå¨ï¼ç°¡å®å¥½ç¨ï¼å¥½è©æ¨å»£ä¸­ã
<ImgZoom src="/tech/first_post/preview.webp" alt="QWER" class="h-full object-cover" width="500"/>
:::
### äºåæºå
åè¦æºåäºåè¦æºåäº$#^%^&#$%$<br/>
å¥ææå¤§å¥éæ¬¡ççå¾å¿«

1. æª¢æ¥æ´æ°
   ```sh
   sudo apt-get update
   ```
2. å®è£ææ°çå¨åNodeJS

   ```sh
   sudo apt-get install -g nodejs latest
   ```
3. å®è£degit<br/>
   éåå¥ä»¶å¯ä»¥å®æ´è¤è£½gitsçå§å®¹ä¸¦æé¤æ.gitçç¸éçµæ§ï¼ä¿è­ç½ç½æ·¨æ·¨çå°ä½ çlocal
   ```sh
   npm install -g degit
   ```
4. å®è£pnpm
   ```sh
   npm i -g pnpm
   ```   
5. å®è£QWER<br/>
  <kbd>my-blog</kbd>æ¿ææä½ æ³è¦çè³æå¤¾åç¨± 
   ```sh
   npx degit kwchang0831/svelte-QWER my-blog
   ```  
### è·èµ·ä¾!å¯¶è²
1. å®è£ææç¸ä¾æ§å¥ä»¶
   ```sh
   pnpm i
   ```
2. Runèµ·ä¾!!!
   ```sh
   pnpm dev
   ```
3. å¯ççµæ
   ```sh
   VITE v3.1.1  ready in 1080 ms

   â  Local:   http://localhost:5173/
   â  Network: use --host to expose
   ```

## å°å°ç¸½çµ
ç°¡å®åé¡§äºä¸ä¸ç¶åç³è«å°å®è£çéç¨<br/>
å¶å¯¦éæå¾çºçååä»£çè·ååè§£æï¼ä¸éç¤æ¼ç¯å¹<br/>
ä»å¤©å°±åé¬å§
æè¬çå°éè£¡çä½ å¦³å°¼æ³¥...ä½ é.?

<ImgZoom src="/tech/first_post/hatori.jpg" alt="å°¼é" class="h-full object-cover">
Illustrated by <a href="https://www.instagram.com/bye_chicken_78/" target="_blank">å¬éåç</a>
</ImgZoom>
