---
layout: post_manual
title: 3.7.1.1.	측정 실행
date: 2025-03-31 13:20:23 +0900
category: "lite_kor"
lang: ko
order: 3711
---

# 3.7.1.1. 측정 실행

Keysight의 오실로스코프를 사용해서 SET를 관찰하려 할 때 사용합니다. (다른 오실로스코프도 사용 가능할 것이나 확인 필요) 사용자가 설정해둔 트리거 컨디션에 따라서 트리거가 발생할 경우 설정된 경로에 파형이 기록된 파일을 발생한 시간을 파일명으로 남깁니다. 대략적인 측정 속도는 10Hz 수준입니다.

-	Device: Refresh를 통해 연결된 장치 검색, 맞는 MSO 선택 후 connect 버튼을 통해서 연결
-	Trigger level: 트리거 레벨을 설정, 정상 동작 전압에서 500mV 이상 차이를 둘 것을 권장(트리거가 안 찍힐 때가 있음)
-	Trigger channel: 오실로스코프의 트리거 걸릴 채널을 설정
-	Edge type: 트리거의 에지 타입을 설정
-	MSO delay: 가장 낮은 값으로 설정하는 것을 권장. 오실로스코프의 종류에 따라 통신이 너무 빨리 이뤄지게 되면 오실로스코프가 먹통이 되는 현상이 있어 동작을 느리게 만드는 딜레이
-	Check: 현재 세팅으로 나오는 측정 속도 측정 (미구현)
-	Start: 눌러서 측정 수행, 다시 눌러서 중단

<!-- 이전/다음 페이지 버튼 -->
<br/>
<br/>
<div style="display: flex; justify-content: space-between; align-items: center; margin-top: 10;">
  <!-- 이전 페이지 버튼 -->
  <a href="/manuals/manuals_lite_kor/Chapter 3/Chapter 3-7-1/" class="btn btn-primary" style="display: inline-block; padding: 5px 10px; background-color: #6c757d; color: white; text-decoration: none; border-radius: 5px;">
    ← Previous
  </a>

  <!-- 다음 페이지 버튼 -->
  <a href="/manuals/manuals_lite_kor/Chapter 3/Chapter 3-7-1-2/" class="btn btn-primary" style="display: inline-block; padding: 5px 10px; background-color: #6c757d; color: white; text-decoration: none; border-radius: 5px;">
    Next →
  </a>
</div>