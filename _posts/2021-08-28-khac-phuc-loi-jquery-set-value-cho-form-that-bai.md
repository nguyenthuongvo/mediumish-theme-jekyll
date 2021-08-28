---
layout: post
title: "Khắc phục lỗi JQuery set value cho form input không hoạt động"
author: soln
categories: [ tech ]
tags: [ble, life]
image: assets/images/2021-08-28-1.png
---

Lỗi này khá khốn nạn, tui đã bị dính lỗi này khi code chức năng tự điền refer code từ URL vào cái METFORM (Wordpress Plugin), sau 7 x 7 49 lần code kiết các kiểu từ .val() .prop('value","CODE"), trigger, change. Tui thật sự thất bại.

## Bế tắc

Tui nghĩ mình đã lâm vào bế tắc, mọi thứ như sụp đỗ trước mắt tui vì nếu cho ông USER điền code vào ô INPUT thì thật sự **chuối**. Một trải nghiệm sử dụng không hề tốt. Và tôi không hề muốn nó xảy ra.

## Tìm ra bí kíp

  ```javascript
var  input = document.getElementsByName("element_name")[0];
input.value = 'CODE';
input.dispatchEvent(new  Event('input', { bubbles:  true }));
```

Với 3 dòng code trên, 1 chân trời mới đã hiện ra trước mắt tui.

It's work!!!!!!!!!!!!!!!

## Không lời giải thích
Tui thật không hiểu JQuery đã bị sự cố gì với mấy cái function set value đó, nhưng chuyển qua xài Javscript không  quá tệ khi nó giải quyết được vấn đề.