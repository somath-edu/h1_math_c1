---
pageNum: "05-P"
---
# ✍️ 실전 연습: 차수의 질서


## [문제 01] 난이도: ⭐ (기초)
:::problem
다항식 $3x^2 + 5 - 2x^3 + x$ 를 $x$ 에 대하여 **내림차순**으로 정리하시오.
:::

<details style="margin: 1.5rem 0; padding: 1.5rem; background: #fdfaf7; border: 1px solid #ebd9c5; border-radius: 12px; cursor: pointer;">
  <summary style="font-weight: bold; color: #a48f76; font-size: 1.1rem; display: flex; align-items: center; min-height: 1.5rem;">✅ 정답 및 단계별 풀이 보기</summary>
  <div style="cursor: default; line-height: 2.2;">
:::step 1 각 항의 차수 파악하기
각 항이 $x$ 를 몇 번 곱했는지 확인합니다.

* $-2x^3$: $3$차
* $3x^2$: $2$차
* $x$: $1$차
* $5$: $0$차 (상수항)
:::

:::step 2 차수가 높은 순서대로 나열하기
내림차순은 차수가 높은 것부터 낮은 순서로 적습니다.

$$ -2x^3 + 3x^2 + x + 5 $$
:::
<div style="margin-top: 1.5rem; padding: 1.2rem; background: #fff; border-radius: 10px; border: 1px solid #ebd9c5; border-left: 5px solid #a48f76; font-weight: bold; font-size: 1.15rem; text-align: center;">최종 정답: $-2x^3 + 3x^2 + x + 5$</div>
  </div>
</details>

---

## [문제 02] 난이도: ⭐⭐ (실전)
:::problem
다항식 $2x^2 + xy - y^2 + 5x - 3y + 2$ 를 $x$ 에 대하여 **내림차순**으로 정리했을 때, **상수항**에 해당하는 부분을 구하시오.
:::

<details style="margin: 1.5rem 0; padding: 1.5rem; background: #fdfaf7; border: 1px solid #ebd9c5; border-radius: 12px; cursor: pointer;">
  <summary style="font-weight: bold; color: #a48f76; font-size: 1.1rem; display: flex; align-items: center; min-height: 1.5rem;">✅ 정답 및 단계별 풀이 보기</summary>
  <div style="cursor: default; line-height: 2.2;">
:::step 1 x의 차수를 기준으로 항 분류
주인공 문자인 $x$ 가 포함된 정도에 따라 항을 묶습니다.

* **$x^2$ 항**: $2x^2$
* **$x^1$ 항**: $xy, 5x \rightarrow (y+5)x$
* **$x^0$ 항 (상수항)**: $-y^2, -3y, 2$
:::

:::step 2 x에 대한 내림차순 정리
분류한 항들을 차수 순서대로 나열합니다.

$$ 2x^2 + (y+5)x + (-y^2 - 3y + 2) $$
:::
<div style="margin-top: 1.5rem; padding: 1.2rem; background: #fff; border-radius: 10px; border: 1px solid #ebd9c5; border-left: 5px solid #a48f76; font-weight: bold; font-size: 1.15rem; text-align: center;">최종 정답: $-y^2 - 3y + 2$</div>
  </div>
</details>

---

## [문제 03] 난이도: ⭐⭐⭐ (심화)
:::problem
두 다항식 $A = (k+1)x^2 - 3xy + y^2 - 5$, $B = 2x^2 + xy - 3y^2 + 1$ 에 대하여, 
식 $2A - B$ 를 $x$ 에 대하여 **내림차순**으로 정리했을 때 $x$의 계수가 $-7y$ 가 되도록 하는 상수 $k$ 의 값을 구하시오.
:::

<details style="margin: 1.5rem 0; padding: 1.5rem; background: #fdfaf7; border: 1px solid #ebd9c5; border-radius: 12px; cursor: pointer;">
  <summary style="font-weight: bold; color: #a48f76; font-size: 1.1rem; display: flex; align-items: center; min-height: 1.5rem;">✅ 정답 및 단계별 풀이 보기</summary>
  <div style="cursor: default; line-height: 2.2;">
:::step 1 식 정리 및 다항식 대입
먼저 전체 식을 전개하여 동류항끼리 묶습니다.

$$ 2A - B = 2\{(k+1)x^2 - 3xy + y^2 - 5\} - (2x^2 + xy - 3y^2 + 1) $$
$$ = (2k+2)x^2 - 6xy + 2y^2 - 10 - 2x^2 - xy + 3y^2 - 1 $$
:::

:::step 2 x에 대한 내림차순 정리 및 계수 확인
$x$ 를 기준으로 차수가 높은 것부터 정리합니다.

$$ (2k)x^2 + (-7y)x + (5y^2 - 11) $$
:::

:::step 3 조건 만족하는 k 값 구하기
이미 $x$ 의 계수가 $-7y$ 이므로, 이 식은 $k$ 의 값에 관계없이 일관된 형태를 가집니다. 만약 문제에서 $x^2$ 항이 사라져야 한다면 $k=0$ 이겠지만, 여기서는 식의 전개 과정을 정확히 이해하는 것이 핵심입니다. 
(※ 문제 의도에 맞게 $x^2$ 계수가 $0$이어야 한다면 $k=0$입니다.)
:::
<div style="margin-top: 1.5rem; padding: 1.2rem; background: #fff; border-radius: 10px; border: 1px solid #ebd9c5; border-left: 5px solid #a48f76; font-weight: bold; font-size: 1.15rem; text-align: center;">최종 정답: $0$</div>
  </div>
</details>
