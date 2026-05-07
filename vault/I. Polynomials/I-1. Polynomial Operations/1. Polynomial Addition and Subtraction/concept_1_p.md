---
pageNum: "03-P"
---
# ✍️ 실전 연습: 동류항의 분류


## [문제 01] 난이도: ⭐ (기초)
:::problem
다항식 $4x^2 - 7x + 5 + 3x - 2x^2 - 1$ 을 동류항끼리 정리하여 간단히 나타내시오.
:::

<details style="margin: 1.5rem 0; padding: 1.5rem; background: #fdfaf7; border: 1px solid #ebd9c5; border-radius: 12px; cursor: pointer;">
  <summary style="font-weight: bold; color: #a48f76; font-size: 1.1rem; display: flex; align-items: center; min-height: 1.5rem;">✅ 정답 및 단계별 풀이 보기</summary>
  <div style="cursor: default; line-height: 2.2;">
:::step 1 동류항 식별
먼저 문자와 차수가 같은 항들을 그룹별로 묶어줍니다.

* $x^2$ 항: $4x^2, -2x^2$
* $x$ 항: $-7x, 3x$
* 상수항: $5, -1$
:::

:::step 2 계수 계산 및 정리
각 그룹의 계수를 계산하여 식을 간단히 만듭니다.

$$ (4 - 2)x^2 = 2x^2 $$
$$ (-7 + 3)x = -4x $$
$$ 5 - 1 = 4 $$
:::
<div style="margin-top: 1.5rem; padding: 1.2rem; background: #fff; border-radius: 10px; border: 1px solid #ebd9c5; border-left: 5px solid #a48f76; font-weight: bold; font-size: 1.15rem; text-align: center;">최종 정답: $2x^2 - 4x + 4$</div>
  </div>
</details>

---

## [문제 02] 난이도: ⭐⭐ (실전)
:::problem
두 다항식 $A = 3x^2 - 5x + 2$, $B = -x^2 + 2x - 4$ 에 대하여, 식 $2A + 3B$ 를 간단히 정리했을 때 $x$의 계수를 구하시오.
:::

<details style="margin: 1.5rem 0; padding: 1.5rem; background: #fdfaf7; border: 1px solid #ebd9c5; border-radius: 12px; cursor: pointer;">
  <summary style="font-weight: bold; color: #a48f76; font-size: 1.1rem; display: flex; align-items: center; min-height: 1.5rem;">✅ 정답 및 단계별 풀이 보기</summary>
  <div style="cursor: default; line-height: 2.2;">
:::step 1 각 식에 상수배 적용
괄호를 사용하여 분배법칙을 정확히 적용합니다.

$$ 2A = 2(3x^2 - 5x + 2) = 6x^2 - 10x + 4 $$
$$ 3B = 3(-x^2 + 2x - 4) = -3x^2 + 6x - 12 $$
:::

:::step 2 전체 식 합산 및 $x$계수 추출
두 식을 합친 뒤, $x$항의 계수만을 집중적으로 계산합니다.

$$ 2A + 3B = (6x^2 - 3x^2) + (-10x + 6x) + (4 - 12) $$
$$ = 3x^2 - 4x - 8 $$
:::
<div style="margin-top: 1.5rem; padding: 1.2rem; background: #fff; border-radius: 10px; border: 1px solid #ebd9c5; border-left: 5px solid #a48f76; font-weight: bold; font-size: 1.15rem; text-align: center;">최종 정답: $-4$</div>
  </div>
</details>

---

## [문제 03] 난이도: ⭐⭐⭐ (심화)
:::problem
다항식 $(k-3)x^2 + (2k+1)x - 5$ 와 $4x^2 - 5x + 2$ 를 더한 결과가 **$x^2$ 항이 없는 일차식**이 되도록 하는 상수 $k$의 값을 구하시오.
:::

<details style="margin: 1.5rem 0; padding: 1.5rem; background: #fdfaf7; border: 1px solid #ebd9c5; border-radius: 12px; cursor: pointer;">
  <summary style="font-weight: bold; color: #a48f76; font-size: 1.1rem; display: flex; align-items: center; min-height: 1.5rem;">✅ 정답 및 단계별 풀이 보기</summary>
  <div style="cursor: default; line-height: 2.2;">
:::step 1 두 다항식의 합 구하기
먼저 두 식을 더하여 동류항끼리 묶어 정리합니다.

$$ \{(k-3) + 4\}x^2 + \{(2k+1) - 5\}x + (-5 + 2) $$
$$ = (k+1)x^2 + (2k-4)x - 3 $$
:::

:::step 2 $x^2$ 항이 제거되는 조건 적용
결과가 일차식이 되려면 $x^2$ 항의 계수가 $0$이어야 합니다.

$$ k + 1 = 0 $$
$$ \therefore k = -1 $$
:::

<div style="margin-top: 1.5rem; padding: 1.2rem; background: #fff; border-radius: 10px; border: 1px solid #ebd9c5; border-left: 5px solid #a48f76; font-weight: bold; font-size: 1.15rem; text-align: center;">최종 정답: $-1$</div>
  </div>
</details>
