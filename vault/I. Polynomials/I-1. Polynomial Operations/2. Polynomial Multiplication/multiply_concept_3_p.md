---
pageNum: "09-P"
---
# ✍️ 실전 연습: 고등 인수분해 핵심 공식


## [문제 01] 난이도: ⭐ (세 항의 제곱)
:::problem
다음 다항식을 인수분해하시오.
$$ x^2 + y^2 + 4z^2 + 2xy + 4yz + 4zx $$
:::

<details style="margin: 1.5rem 0; padding: 1.5rem; background: #fdfaf7; border: 1px solid #ebd9c5; border-radius: 12px; cursor: pointer;">
  <summary style="font-weight: bold; color: #a48f76; font-size: 1.1rem; display: flex; align-items: center; min-height: 1.5rem;">✅ 정답 및 단계별 풀이 보기</summary>
  <div style="cursor: default; line-height: 2.2;">
:::step 1 각 항의 제곱 관계 확인
각 항이 어떤 문자의 제곱인지 파악합니다.
* $x^2, y^2, (2z)^2$ 의 형태입니다.
:::

:::step 2 두 항씩 곱한 결과 검증
$2ab, 2bc, 2ca$ 에 해당하는 항들이 일치하는지 확인합니다.
* $2 \times x \times y = 2xy$
* $2 \times y \times 2z = 4yz$
* $2 \times 2z \times x = 4zx$ (모두 일치!)
:::
<div style="margin-top: 1.5rem; padding: 1.2rem; background: #fff; border-radius: 10px; border: 1px solid #ebd9c5; border-left: 5px solid #a48f76; font-weight: bold; font-size: 1.15rem; text-align: center;">최종 정답: $(x + y + 2z)^2$</div>
  </div>
</details>

---

## [문제 02] 난이도: ⭐⭐ (세제곱의 차)
:::problem
다음 다항식을 인수분해하시오.
$$ a^3 - 27 $$
:::

<details style="margin: 1.5rem 0; padding: 1.5rem; background: #fdfaf7; border: 1px solid #ebd9c5; border-radius: 12px; cursor: pointer;">
  <summary style="font-weight: bold; color: #a48f76; font-size: 1.1rem; display: flex; align-items: center; min-height: 1.5rem;">✅ 정답 및 단계별 풀이 보기</summary>
  <div style="cursor: default; line-height: 2.2;">
:::step 1 세제곱 형태 파악
두 항이 각각 무엇의 세제곱인지 확인합니다.
* $a^3$ 과 $3^3$ 의 차 형태입니다.
:::

:::step 2 세제곱 차 공식 적용
$x^3 - y^3 = (x-y)(x^2 + xy + y^2)$ 공식을 사용합니다.
* $a^3 - 3^3 = (a-3)(a^2 + 3a + 9)$
:::
<div style="margin-top: 1.5rem; padding: 1.2rem; background: #fff; border-radius: 10px; border: 1px solid #ebd9c5; border-left: 5px solid #a48f76; font-weight: bold; font-size: 1.15rem; text-align: center;">최종 정답: $(a - 3)(a^2 + 3a + 9)$</div>
  </div>
</details>

---

## [문제 03] 난이도: ⭐⭐⭐ (삼차 완전제곱)
:::problem
다음 다항식을 인수분해하시오.
$$ x^3 + 6x^2y + 12xy^2 + 8y^3 $$
:::

<details style="margin: 1.5rem 0; padding: 1.5rem; background: #fdfaf7; border: 1px solid #ebd9c5; border-radius: 12px; cursor: pointer;">
  <summary style="font-weight: bold; color: #a48f76; font-size: 1.1rem; display: flex; align-items: center; min-height: 1.5rem;">✅ 정답 및 단계별 풀이 보기</summary>
  <div style="cursor: default; line-height: 2.2;">
:::step 1 양 끝 항의 세제곱 파악
세제곱 공식 $(a+b)^3$ 형태인지 의심하고 끝 항을 봅니다.
* $x^3$ 과 $(2y)^3$ 입니다.
:::

:::step 2 중간 항 검증
$3a^2b$ 와 $3ab^2$ 가 맞는지 확인합니다.
* $3 \times x^2 \times 2y = 6x^2y$
* $3 \times x \times (2y)^2 = 12xy^2$ (일치!)
:::
<div style="margin-top: 1.5rem; padding: 1.2rem; background: #fff; border-radius: 10px; border: 1px solid #ebd9c5; border-left: 5px solid #a48f76; font-weight: bold; font-size: 1.15rem; text-align: center;">최종 정답: $(x + 2y)^3$</div>
  </div>
</details>
