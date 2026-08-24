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

전체 규칙은 [SKILL.md](SKILL.md)와 [런타임 어댑터](references/xxd-panel-050-prompt.en.md)를 참조하세요. 원문의 미학을 보존하지만 역사적인 3:4 화면은 숨은 기본값이 아닙니다.

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

## 원본 프롬프트가 유일한 미적 기준입니다

`references/050-source.md`는 이 프로젝트의 유일한 창작·미적 기준입니다. Skill은 원문을 요약하거나 확장하지 않으며 공통 색상 계획, 미적 동기, 제목, 마이크로카피를 추가하지 않습니다. 색, 재료, 구성, 여백, 문구, 타이포그래피는 GPT Image 2가 원본 프롬프트의 규칙대로 수행합니다.

모드와 크기는 원본의 변환 미학을 바꾸지 않고 기존 3:4 상하 출력 컨테이너를 완전히 대체합니다. 각 결과물에는 선택된 하나의 모드 계약만 GPT Image 2에 전달하며, 네 가지 대안을 하나의 범용 템플릿에서 해석하게 하지 않습니다.

## 조합 가능한 네 가지 출력

`top-bottom`, `left-right`, `design-only`, `wallpaper-pack`을 하나 이상 선택할 수 있습니다. 여러 모드를 고르면 각 모드를 독립 프롬프트로 따로 생성합니다.

- `top-bottom`: 현실 화면은 위, 디자인 변환은 아래에 놓인 하나의 완성 캔버스입니다.
- `left-right`: 위에서 아래까지 좌우 구조를 유지하며 원본은 왼쪽, 디자인은 오른쪽에 둡니다. 문구도 이 구조 안에 통합하고 너비는 비대칭일 수 있습니다.
- `design-only`: 원본은 보이지 않는 참조이며, 보이는 모든 요소가 해당 Panel의 디자인 변환 언어를 따릅니다.
- `wallpaper-pack`: 각 기기마다 디자인 변환만으로 된 전체 화면 배경을 독립적으로 재구성합니다.

경계선, 중앙 비율, 픽셀 좌표는 측정하지 않습니다. 결정론적 합성은 사용자가 정확한 분할이나 원본 픽셀 보존을 명시한 경우에만 사용합니다.

일반 크기도 복수 선택할 수 있습니다: 자동 맞춤, 원본 비율, 1:1, 3:4, 4:3, 4:5, 5:4, 2:3, 3:2, 9:16, 16:9, 21:9, 5:7, 7:5, 사용자 비율／정확한 픽셀. 암묵적 기본 크기는 없습니다. 서로 다른 비율은 동일한 원본 프롬프트에서 각각 다시 구성합니다.

배경화면 세트는 연속형 또는 독립형입니다. 연속형은 먼저 기준 이미지 한 장을 만들고, 나머지는 원본 사진＋기준 이미지를 함께 참고해 각 기기에 맞게 재구성합니다. 한 이미지를 네 크기로 기계적으로 자르지 않습니다.

## 텍스트 모드

생성 전에 다음 중 하나를 정합니다.

1. **원본 프롬프트에 따라 모델이 텍스트 생성**: 사용자는 언어 또는 지역만 지정하고, 내용·분량·톤·타이포그래피는 GPT Image 2가 원문 규칙대로 생성합니다. 모든 문구는 현재 이미지의 내용·분위기·함의에서 나오며, 사실이나 자료처럼 보이는 정보는 사용자 제공·이미지에서 확인 가능·검증된 근거가 있어야 합니다.
2. **내 정확한 문구 사용**: 한 글자도 바꾸지 않고 전달하며 재작성, 번역, 제목 추가를 하지 않습니다. 배치는 원문을 따릅니다.
3. **텍스트 없음**: 모든 텍스트와 가짜 문자를 금지합니다.

외부 Skill은 제목이나 마이크로카피를 미리 쓰지 않습니다. 출력 언어는 인터페이스 언어와 별도로 확인하며 인물, 장면, 파일명에서 추정하지 않습니다.

## 호스트 기능에 맞춘 질문과 인라인 매개변수

같은 Skill이 호스트가 실제로 제공하는 상호작용 기능에 맞춰 동작하며 장식 기호를 클릭 가능한 UI처럼 보이게 하지 않습니다.

- **Claude Code에 `AskUserQuestion + multiSelect: true`가 있으면**: 모드와 크기는 실제 체크박스, 텍스트 방식과 배경화면 관계는 단일 선택을 사용합니다. 일반 크기는 정사각형·세로·가로 그룹으로 나누고 선택을 누적하며 사용자 크기는 자유 입력합니다.
- **Codex에 `request_user_input`만 있으면**: 텍스트 방식과 배경화면 관계처럼 상호 배타적인 항목에만 사용합니다. 모드와 크기를 단일 선택처럼 꾸미지 않고 조합 입력으로 받습니다.
- **상호작용 도구가 없으면**: 첫 번째 질문에서 모드, 두 번째 질문에서 크기＋텍스트 방식을 입력합니다. 가짜 `- [ ]`를 표시하지 않고 폼만을 위해 Plan mode 전환을 요구하지 않습니다.

두 번째 질문은 처음에 스마트 추천／원본 비율／일반 비율／사용자 지정만 보여 줍니다. 일반 비율을 선택할 때만 정사각형 `1:1`, 세로 `3:4, 4:5, 2:3, 9:16, 5:7`, 가로 `4:3, 5:4, 3:2, 16:9, 21:9, 7:5`를 펼칩니다. 여러 비율과 정확한 픽셀을 함께 지정할 수 있습니다.

모든 설정은 인라인으로도 전달할 수 있습니다.

```text
/xxd-panel-050 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text prompt --locale ja-JP
```

`--mode`, 반복 가능한 `--size`, `--text prompt|exact|none`, `--locale`, `--copy`, `--wallpaper linked|independent`, `--wallpaper-size`, `--out`을 지원합니다. 값이 모두 있으면 질문을 건너뛰고, 일부만 있으면 누락된 항목만 묻습니다.

## 이미지 모델 우선순위

GPT Image 2를 기본 최우선 모델로 사용합니다. 고충실도 원본 참조, 생성 전 완성 캔버스 확인, 이중 패널의 완성 화면 일괄 생성, 조건이 충족될 때만 사용하는 스크립트 합성이라는 기존 흐름은 그대로 유지합니다.

현재 도구 또는 설정된 경로에서 실제로 사용할 수 있고 원본 충실도, 완성 화면비, 대상 언어의 문자, 연결형 배경화면의 다중 참조 요구를 충족할 때는 Seedance 5.0 Pro, Nano Banana Pro(Gemini Image Pro), Nano Banana 2(Gemini Image Flash) 또는 다른 호환 비트맵 모델도 사용할 수 있습니다. 대체 모델은 생성 경로만 바꾸며 모드, 캔버스, 문구, 언어, 배경화면 관계와 완성 캔버스 우선 전략을 바꾸지 않습니다.

적합한 경로가 없으면 이미지 생성 도구를 활성화하거나 API Key를 제공하도록 사용자에게 요청합니다. 사용자가 제공한 인증 정보는 현재 작업에 사용할 수 있지만 답변이나 로그에 다시 표시·기록·노출하지 않습니다. 사용자가 명시적으로 요청하지 않는 한 장기 저장하거나 제공자, 계정, 결제 또는 전역 경로 설정을 변경하지 않습니다.

## 시작하기

```bash
git clone https://github.com/nevertoday/xxd-panel-050.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-050" ~/.codex/skills/xxd-panel-050
```

Claude Code 사용자는 같은 폴더를 `~/.claude/skills/xxd-panel-050`에 연결할 수 있습니다. 설치 후 세션을 다시 시작하세요.

전체 사양: [Skill](SKILL.md) · [원본 자료](references/050-source.md) · [영문 런타임 어댑터](references/xxd-panel-050-prompt.en.md) · [중문 런타임 어댑터](references/xxd-panel-050-prompt.zh-CN.md)

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
