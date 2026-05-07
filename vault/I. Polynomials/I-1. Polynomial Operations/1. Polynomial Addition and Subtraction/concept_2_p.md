---
pageNum: "04-P"
---
# ✍️ 실전 연습: 연산의 법칙


## [문제 01] 난이도: ⭐ (기초)
:::problem
두 다항식 $A = x^2 - 2x + 3$, $B = 2x^2 + x - 1$ 에 대하여, 
식 $(A + 2B) - (B - A)$ 를 간단히 정리하시오.
:::

<details style="margin: 1.5rem 0; padding: 1.5rem; background: #fdfaf7; border: 1px solid #ebd9c5; border-radius: 12px; cursor: pointer;">
  <summary style="font-weight: bold; color: #a48f76; font-size: 1.1rem; display: flex; align-items: center; min-height: 1.5rem;">✅ 정답 및 단계별 풀이 보기</summary>
  <div style="cursor: default; line-height: 2.2;">
:::step 1 주어진 식 단순화하기
다항식을 바로 대입하지 않고, 문자 $A, B$ 상태에서 먼저 정리합니다.

$$ (A + 2B) - B + A = 2A + B $$
:::

:::step 2 다항식 대입 및 계산
정리된 식 $2A + B$ 에 각 다항식을 대입하여 계산합니다.

$$ 2(x^2 - 2x + 3) + (2x^2 + x - 1) $$
$$ = 2x^2 - 4x + 6 + 2x^2 + x - 1 $$
:::
<div style="margin-top: 1.5rem; padding: 1.2rem; background: #fff; border-radius: 10px; border: 1px solid #ebd9c5; border-left: 5px solid #a48f76; font-weight: bold; font-size: 1.15rem; text-align: center;">최종 정답: $4x^2 - 3x + 5$</div>
  </div>
</details>

---

## [문제 02] 난이도: ⭐⭐ (실전)
:::problem
세 다항식 $A, B, C$ 에 대하여 $A - B = 2x^2 - 3x + 4$, $B + C = x^2 + 5x - 2$ 일 때, 
식 $A + C$ 를 구하시오.
:::

<details style="margin: 1.5rem 0; padding: 1.5rem; background: #fdfaf7; border: 1px solid #ebd9c5; border-radius: 12px; cursor: pointer;">
  <summary style="font-weight: bold; color: #a48f76; font-size: 1.1rem; display: flex; align-items: center; min-height: 1.5rem;">✅ 정답 및 단계별 풀이 보기</summary>
  <div style="cursor: default; line-height: 2.2;">
:::step 1 식의 결합 원리 활용
구하고자 하는 $A+C$ 를 만들기 위해 주어진 두 식을 어떻게 연산할지 결정합니다.

$$ (A - B) + (B + C) = A - B + B + C = A + C $$
:::

:::step 2 다항식의 덧셈 실행
주어진 두 결과식을 그대로 더해줍니다.

$$ (2x^2 - 3x + 4) + (x^2 + 5x - 2) $$
$$ = (2+1)x^2 + (-3+5)x + (4-2) $$
:::
<div style="margin-top: 1.5rem; padding: 1.2rem; background: #fff; border-radius: 10px; border: 1px solid #ebd9c5; border-left: 5px solid #a48f76; font-weight: bold; font-size: 1.15rem; text-align: center;">최종 정답: $3x^2 + 2x + 2$</div>
  </div>
</details>

---

## [문제 03] 난이도: ⭐⭐⭐ (심화)
:::problem
어떤 다항식 $X$ 에 $2x^2 - x + 3$ 을 더해야 할 것을 잘못하여 뺐더니, 
그 결과가 $x^2 + 4x - 5$ 가 되었다. 이때, **바르게 계산한 결과**를 구하시오.
:::

<details style="margin: 1.5rem 0; padding: 1.5rem; background: #fdfaf7; border: 1px solid #ebd9c5; border-radius: 12px; cursor: pointer;">
  <summary style="font-weight: bold; color: #a48f76; font-size: 1.1rem; display: flex; align-items: center; min-height: 1.5rem;">✅ 정답 및 단계별 풀이 보기</summary>
  <div style="cursor: default; line-height: 2.2;">
:::step 1 어떤 다항식 $X$ 구하기
잘못된 계산식을 세워 $X$ 의 정체를 알아냅니다.

$$ X - (2x^2 - x + 3) = x^2 + 4x - 5 $$
$$ X = (x^2 + 4x - 5) + (2x^2 - x + 3) = 3x^2 + 3x - 2 $$
:::

:::step 2 바른 계산 실행하기
찾아낸 $X$ 에 원래 더하려고 했던 식을 더해줍니다.

$$ (3x^2 + 3x - 2) + (2x^2 - x + 3) $$
$$ = 5x^2 + 2x + 1 $$
:::
<div style="margin-top: 1.5rem; padding: 1.2rem; background: #fff; border-radius: 10px; border: 1px solid #ebd9c5; border-left: 5px solid #a48f76; font-weight: bold; font-size: 1.15rem; text-align: center;">최종 정답: $5x^2 + 2x + 1$</div>
  </div>
</details>
