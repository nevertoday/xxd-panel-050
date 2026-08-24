<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 050 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 050

### 한 장의 사진을 그 장소만의 에어리 블루 여행 비주얼로

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-D5898C?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-6FA4B7?style=flat-square)](#)

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <strong>한국어</strong> · <a href="README.ar.md">العربية</a>

</div>

> 맞춤형 여행 장면 · 에어리 블루 · 미니멀 플랫 벡터 · 에디토리얼 여백 · 한 이미지, 한 정체성

원본에서 가장 알아보기 쉬운 주체와 서사 관계를 그 사진만을 위한 고급 여행 비주얼로 바꿉니다. 하나의 초점, 근거 있는 환경 단서 2–4개, 고요한 여백과 가벼운 블루 팔레트로 구성하며 도시 이름만 바꾸는 범용 템플릿을 거부합니다.

## 미학적 논리

```text
주체·자세·서사 관계 고정 → 고유 단서 3개 보존 → 주 시각 초점 하나 선택 → 원본에서 환경 증거 2–4개 추출 → 템플릿이 아니라 주체에 맞춰 재구성 → 에어리 블루 플랫 벡터로 통일 → 고요한 여백 유지 → 제목과 태그라인을 장면의 정체성으로 통합
```

무관한 사진으로 바꿔도 인식성, 환경 단서, 공간 질서, 색 관계와 문구가 실질적으로 변하지 않는다면 이 Panel의 결과가 아닙니다.

## 시각적 원칙

- 원본 고유 단서를 최소 3개 보존하고 주체를 범용 아이콘으로 축소하지 않습니다.
- 초점은 하나, 보조 환경 단서는 원본에 근거한 2–4개만 둡니다. 사람이 필요하면 3–6명의 작은 인물로 자연스럽게 통합합니다.
- 장면 유형은 원본이 결정합니다. 무관한 랜드마크, 도시명 템플릿, 엽서 공식을 사용하지 않습니다.
- 일본 문구, 부티크 스티커 일러스트, 현대 여행 브랜딩의 감각으로 단순한 기하, 부드러운 윤곽, 통일된 선 굵기, 평면 색, 절제된 디테일과 넉넉한 여백을 사용합니다.
- 파우더·안개·하늘·공기감 있는 쿨 블루를 중심으로 아이보리, 크림, 옅은 베이지, 부드러운 회녹색, 건축 중성색을 균형 있게 배치합니다. 뮤트 블러시는 아주 작은 포인트만 허용합니다.
- 사실주의, 플라스틱 CG, 그라데이션, 질감, 무거운 그림자, 복잡한 배경, 랜드마크 콜라주, 반복 레이아웃을 거부합니다.

전체 규칙은 [SKILL.md](SKILL.md)와 [생성 프롬프트](references/xxd-panel-050-prompt.en.md)를 참조하세요. 원문의 미학을 보존하지만 역사적인 3:4 화면은 숨은 기본값이 아닙니다.

## 예시 · X에서

> [샤오샤오둥（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091461184516227185) · 2026년 8월 23일<br>
> GPT2 × 벡터 일러스트 × 여행 × 미니멀 × 미학 프롬프트 × VOL.050

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091461184516227185"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 050 예시 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091461184516227185"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 050 예시 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091461184516227185"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 050 예시 3"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091461184516227185">원문 게시물과 전체 프롬프트 보기 →</a></p>

이 예시는 050의 미학적 의도를 보여 줄 뿐이며, 예시의 주제, 구성, 색상, 문구, 이전 캔버스 비율은 생성 참고나 현재 기본값이 되지 않습니다.

## 조합 가능한 네 가지 출력

`1`, `1+3`, `1,2,4`, `전체`로 하나 또는 여러 모드를 선택할 수 있으며 `전체`는 원본당 독립 PNG 7개를 만듭니다. 모드 선택 뒤, 생성 전에 완성 이미지 전체의 화면비를 반드시 확인합니다: 원래 프롬프트의 `3:4`, 명시적인 원본 비율, 일반 비율, 사용자 지정 비율／정확한 픽셀입니다. 원본 크기를 묵시적으로 적용하지 않습니다.

| 모드 | 화면비 규칙 | 결과물 |
| --- | --- | --- |
| `top-bottom` | 사용자가 확인한 전체 캔버스 | 완성 캔버스를 한 번에 생성: 위에 고충실도 원본, 아래에 050 디자인, 약 50/50 |
| `left-right` | 사용자가 확인한 전체 캔버스 | 완성 캔버스를 한 번에 생성: 왼쪽에 고충실도 원본, 오른쪽에 050 디자인, 약 50/50 |
| `design-only` | 사용자가 확인한 전체 캔버스 | 050 디자인이 전체를 채우며 원본 사진은 보이지 않음 |
| `wallpaper-pack` | 기기별 확인 | 휴대전화, iPad, 데스크톱, 어린이용 스마트워치 PNG 개별 출력 |

이중 패널 모드는 원본을 고충실도 편집／참조 입력으로 사용하고 완전한 스타일 프롬프트 한 세트로 최종 화면을 직접 생성합니다. 사진, 디자인, 색, 빛, 타이포그래피와 의미가 하나로 이어지게 하기 위해서입니다. 결정적 합성은 전체 캔버스 재시도 후에도 실패한 경우, 원본의 픽셀 완전 보존을 명시한 경우, 현재 경로가 목표 화면비를 만들 수 없는 경우, 또는 무손실 최종 픽셀 조정이 필요한 경우에만 사용합니다.

배경화면은 연결형 또는 독립형입니다. 연결형은 iPad 기준 작품 하나를 승인한 뒤 다른 기기를 원본＋같은 기준 작품에서 각각 재구성합니다. 독립형은 각 기기가 원본만 참조합니다. 어느 쪽도 다른 기기 결과를 자르거나 파생 결과를 연쇄 참조하지 않습니다.

## 문구, 래스터, 신뢰

생성 전에 자동 문구, 정확한 사용자 문구, 무문자 중 하나와 대상 언어를 확인합니다. 자동 문구는 현재 사진의 장소, 대상, 상태, 분위기, 깊은 의미 또는 숨은 관계에서 짧은 제목과 태그라인을 만들며 도시명 공식을 쓰지 않습니다. 문자는 여백과 공간 리듬에 통합되고 붙여 넣은 제목 막대가 되지 않습니다.

일반 크기는 원본에 적응하고 페어 모드는 정확히 50/50이며 모든 결과는 PNG입니다. 매 호출마다 `~/Desktop/xxd/xxd-panel-050/` 아래 새 작업을 만듭니다. 이미지 생성 경로는 민감 정보를 노출하지 않으며 SVG, HTML, Canvas, 프로그램 드로잉은 대체물이 아닙니다.

## 시작하기

```bash
git clone https://github.com/nevertoday/xxd-panel-050.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-050" ~/.codex/skills/xxd-panel-050
```

Claude Code 사용자는 같은 폴더를 `~/.claude/skills/xxd-panel-050`에 연결할 수 있습니다. 설치 후 세션을 다시 시작하세요.

전체 사양: [Skill](SKILL.md) · [원본 자료](references/050-source.md) · [영문 프롬프트](references/xxd-panel-050-prompt.en.md) · [중문 프롬프트](references/xxd-panel-050-prompt.zh-CN.md)

## XXD와 지원

XXD는 Xiaoxiaodong 브랜드명의 약칭이며 [@xiaoxiaodong01](https://x.com/xiaoxiaodong01)이 제작·관리합니다. 심층 상담은 CNY 299/시간이며 Skills 사용자 교류 그룹은 CNY 99 일회 결제입니다. Knowledge Planet＋회원 프롬프트 라이브러리는 연 CNY 699 한 번의 결제로 두 혜택을 모두 엽니다. [Knowledge Planet](https://wx.zsxq.com/group/15554814142882) 가입 후 WeChat으로 Xiaoxiaodong에게 연락해 [프롬프트 라이브러리](https://vip.xiaoxiaodong.ai/) 교환 코드를 받고, 프롬프트 라이브러리에서 셀프서비스 개통 후에는 WeChat으로 연락해 Knowledge Planet 초대를 받으세요. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>장소 이름을 바꾸는 것이 아니라, 이 사진만의 여행 정체성을 만듭니다.</strong></div>

---

<div align="center">

## ☕ 오픈 소스 프로젝트 후원

후원은 자율이며 프로젝트 접근 권한을 바꾸지 않습니다.

<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
