# NEXT.JS

## 環境變數

在根目錄創建 .env 檔案，裡面所設置的變數在程式裡可以用 process.env.{var} 取得，[參考資料](https://nextjs.org/docs/app/building-your-application/configuring/environment-variables)。

## deploy

- docker: https://nextjs.org/docs/pages/building-your-application/deploying#docker-image

## 重新導入頁面

- 使用 next.config.js 中的 redirects ： https://nextjs.org/docs/pages/api-reference/next-config-js/redirects

## 埋入 GA

- 使用 next/script 埋入： https://www.makeuseof.com/nextjs-google-analytics/
- 額外的 gtag event 登記：
  - https://mariestarck.com/add-google-analytics-to-your-next-js-application-in-5-easy-steps/
  - https://developers.google.com/analytics/devguides/collection/gtagjs/events?hl=zh-tw
