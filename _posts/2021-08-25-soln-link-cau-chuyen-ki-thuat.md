---
layout: post
title:  "Soln.link câu chuyện kĩ thuật"
author: john
categories: [ soln, stories ]
tags: [red, yellow]
image: assets/images/11.jpg
description: "Tui đã xây dựng Blog Soln.link bằng công cụ gì, tại sao tui làm như thế?"
featured: false
hidden: true
rating: 3
---

# Soln.link được tạo ra như thế nào?

> Bài viết này tôi tập trung nói về kĩ thuật, hơn là chia sẽ ý nghĩa, lý
> do tạo trang Soln.link như thế nào.
 
Soln.link là một  trang blog tĩnh, được build từ [Jekyll](https://jekyllrb.com/) - một static site generator. Vỏ bọc xây dựng bởi theme Mediumish (nhìn y như bản sao của Medium :smile:). Trong nhiều cách viết Blog, nhiều nền tảng hỗ trợ viết Blog như Blogger, Wordpress, Wix,... tui chọn cách dùng Jekyll build ra static site rồi push lên Gitpage, gắn Domain. Một cách làm hơi lòng vòng, nhưng tui thích làm như vậy vì sau:

 1. Trang tĩnh thì nhẹ, load nhanh
 2. Chi phí bỏ ra thấp, chỉ cần mua domain là đủ
 3. Có thể lập trình bố cục, chức năng riêng theo ý của tui
 4. Vì đang tìm hiểu Jamstack là gì nên muốn thử nó
 

## [Jekyll](https://jekyllrb.com/)

Jekyll là một thằng chuyên tạo site tĩnh được viết bằng Ruby bởi ông Preston-Werner. Do đó bạn phải cài môi trường Ruby các kiểu trước khi chạy Jerkyll, cách này đặt trên máy chạy Ubuntu khá dễ, còn tui cài nó hơi khoai, do chạy Windows  11 phải cài WSL các thứ, rồi dùng Linux Shell để chạy source code.

### Ngoài thằng Jekyll, còn thằng nào generate static site nữa không?
Còn chứ, ví dụ như:
1. Gatsby
2. Next.js
3. Gridsome
4. Nuxt.js
5. 11ty
6. Hugo
7. Scully
8. Sculpin
9. Sapper

Ai thích thằng nào thì quất thằng đó, riêng tui không biết xài thằng nào nhưng thấy Gitpage đề xuất **Jekyll** nên xài nó luôn.

## [Mediumish](https://github.com/wowthemesnet/mediumish-theme-jekyll)

Cái này giống như vô tình lụm được bí kíp luôn, giữa muôn nghìn [theme](https://jamstackthemes.dev/theme/) trên [Jamstackthem](https://jamstackthemes.dev/theme/)
tui đã tìm thấy em nó. Nhìn chung 9 với 10 với giao diện Medium, rất mượt, nhẹ nhàng và đầy đủ Option. Theme này đã quá đầy đủ với 1 người viết Blog dăm ba bữa như tui.

Share với mấy bạn link [Github](https://github.com/wowthemesnet/mediumish-theme-jekyll) của em nó. Fork về xài cho đã.

## Github Page

Gitpage hẵn quá quen thuộc với những người xài Github, một nơi publish static site miễn phí lại có thể custom domain. Cùng nhờ tìm đến Gitpage mà tui biết được Jekyll là cái gì? Với những người ít tiền như tui Gitpage mang lại rất nhiều giá trị, nó cho tui publish site với **HTTPS** - làm Landing Page gắn Mess Plugin thì hết sảy, và còn nhiều thứ nữa...

## Kết luận
Tui vẫn trong quá trình trải nghiệm cái Jekyll này, phải cần một thời gian nữa để đánh giá ưu nhược điểm của nó. Khi đó tui sẽ viết một bài khác về nó. Mọi người hãy chờ xem nhá.




