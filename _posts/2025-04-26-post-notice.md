---
title: "Post: Notice"
date: 2025-04-26
categories:
  - Post Formats
tags:
  - Post Formats
  - notice

excerpt: "블로그에 Notice Box를 추가하는 방법에 대해 알아보자."
---

Notice Box는 콘텐츠 안에서 중요한 정보나 알림을 강조해서 보여주는 박스를 말한다. 

"알려드립니다", "주의하세요", "성공했습니다" 같은 메시지를 강조할 때 사용하는데 보통 색깔(파랑, 빨강, 노랑 등)이나 아이콘(ℹ️⚠️✅❌)을 같이 써서 의미를 구분한다.

mmistakes 테마는 notice 기능을 기본적으로 완비하고 있다 때문에 따로 커스터마이징 해 줄 필요 없이 바로 사용할 수 있다.

지금부터 그 사용법을 알아보자. 

Notice 박스를 추가하려면 텍스트 뒤에 {:.notice--타입}만 추가하면 간편하게 강조박스를 만들 수 있다:

```
**Info Notice:** Lorem ipsum dolor sit amet, [consectetur adipiscing elit](#). Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.
{: .notice--info}

**Warning Notice:** Lorem ipsum dolor sit amet, consectetur adipiscing elit. [Integer nec odio](#). Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.
{: .notice--warning}

**Danger Notice:** Lorem ipsum dolor sit amet, consectetur adipiscing elit. [Integer nec odio](#). Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.
{: .notice--danger}

**Success Notice:** Lorem ipsum dolor sit amet, consectetur adipiscing elit. [Integer nec odio](#). Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.
{: .notice--success}
```

**Info Notice:** Lorem ipsum dolor sit amet, [consectetur adipiscing elit](#). Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.
{: .notice--info}

**Warning Notice:** Lorem ipsum dolor sit amet, consectetur adipiscing elit. [Integer nec odio](#). Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.
{: .notice--warning}

**Danger Notice:** Lorem ipsum dolor sit amet, [consectetur adipiscing](#) elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.
{: .notice--danger}

**Success Notice:** Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at [nibh elementum](#) imperdiet.
{: .notice--success}

---
***reference***
- <https://mmistakes.github.io/minimal-mistakes/post%20formats/post-notice/>
- <https://github.com/blacklabelx1/better-me/blob/main/_sass/minimal-mistakes/_notices.scss>
- layout: <https://mmistakes.github.io/minimal-mistakes/docs/layouts/>