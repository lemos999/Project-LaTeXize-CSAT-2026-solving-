# ✒️ Project LaTeXize

An advanced AI transcription engine with visual analysis capabilities, designed for high-fidelity conversion of mathematical documents—including complex graphs and diagrams—into structured, solvable LaTeX code.

The purpose of this project is to verify that an AI can not only transcribe mathematical documents into LaTeX but also extract and textualize the logical, solvable information contained within visual elements like graphs and geometric figures.

## ✅ Verification: 2026 CSAT Mock Exam

The reliability of LaTeXize was rigorously tested by converting the entire 2026 mock College Scholastic Ability Test (CSAT) Mathematics exam (Odd Type) into LaTeX. The generated code, including the VLE tags, was then used to solve every problem.

> **Note:** Copyright for the test questions used in this verification belongs to the Korea Institute for Curriculum and Evaluation (KICE).

**The results were a 100% match with the official answer key across all sections:**
*   **Common Questions (Math I, Math II):** 100% Accuracy
*   **Calculus:** 100% Accuracy
*   **Probability and Statistics:** 100% Accuracy
*   **Geometry:** 100% Accuracy

This successful test validates the system's ability to preserve all necessary information for problem-solving.

## 📌 Core Features

*   **High-Fidelity LaTeX Conversion:** Accurately transcribes all standard text and mathematical formulas into clean LaTeX syntax.
*   **Visual Logic Extraction (VLE):** Its cornerstone feature. Instead of describing art, VLE analyzes graphs and geometric figures to extract solvable conditions (e.g., points of tangency, coordinates, boundaries of a region) and converts this visual data into a machine-readable text tag.
*   **100% Information Integrity:** A strict protocol ensures that no information—explicit in the text or implicit in the visuals—is lost during the conversion process.
*   **Standardized Output:** All output is delivered in a predictable and structured format, utilizing a mandatory code block and a dedicated `\text{[Visual Logic: ... ]}` tag for geometric information.

## 🚀 Demonstration & Full Solutions

The complete process, from the initial LaTeX conversion to the final problem-solving for all 44 questions, was conducted in a single, continuous session. You can review the entire workflow and verify the solutions via the link below.

**[View Full Solution Session on Gemini](https://gemini.google.com/share/0c8b03244339)**

> For video breakdowns of the solutions, please contact: `lemoaxtoria@gmail.com`

## 🛠️ Core Technology

This system is built upon a clear, rule-based architecture:

1.  **Visual Logic Extraction (VLE):** The engine for interpreting visuals. It operates on four key rules to extract logic, not art:
    *   **Coordinates:** Identify specific points shown on axes.
    *   **Relationships:** Explicitly state tangency, perpendicularity, and intersections.
    *   **Regions:** Define the exact boundaries of shaded or specified areas.
    *   **Hidden Data:** Capture data present only in the figure (e.g., when text says "Refer to figure").
2.  **Three-Phase Operational Logic:** A sequential process guarantees accuracy:
    *   **Phase 1: Literal Conversion:** All text and formulas are transcribed exactly.
    *   **Phase 2: Deep Vision Scan:** All images are processed according to VLE rules.
    *   **Phase 3: Integrity Check:** The output is cross-referenced with the source to ensure 100% information preservation.
3.  **Strict Output Protocol:** A rigid format for consistency and usability, mandating a Markdown code block for the final LaTeX output.

## ⚠️ Disclaimer
The College Scholastic Ability Test (CSAT) questions cited in this project are the intellectual property of the Korea Institute for Curriculum and Evaluation (KICE). This project uses them for the sole purpose of technological demonstration and verification.

---

# ✒️ 프로젝트 LaTeXize

복잡한 그래프와 도형을 포함한 수학 문서를 구조화되고 풀이 가능한 LaTeX 코드로 고정밀 변환하도록 설계된, 시각적 분석 기능을 갖춘 고성능 AI 트랜스크립션 엔진입니다.

이 프로젝트의 목적은 AI가 수학 문서를 LaTeX로 변환하는 것을 넘어, 그래프나 도형 같은 시각 자료에 포함된 논리적이고 풀이 가능한 정보까지 추출하여 텍스트로 변환할 수 있는지 검증하는 것입니다.

## ✅ 신뢰성 검증: 2026학년도 수능 모의평가

LaTeXize의 신뢰도는 2026학년도 대학수학능력시험 수학 영역 모의평가(홀수형) 전체 문항을 LaTeX로 변환하여 엄격하게 테스트되었습니다. VLE 태그를 포함하여 생성된 코드를 기반으로 모든 문제를 풀이했습니다.

> **안내:** 본 검증에 사용된 시험 문제의 저작권은 한국교육과정평가원(KICE)에 있습니다.

**그 결과, 모든 과목에서 공식 정답과 100% 일치했습니다.**
*   **공통 과목 (수학 I, 수학 II):** 정확도 100%
*   **선택 과목 (미적분):** 정확도 100%
*   **선택 과목 (확률과 통계):** 정확도 100%
*   **선택 과목 (기하):** 정확도 100%

이 성공적인 테스트는 LaTeXize가 문제 풀이에 필요한 모든 정보를 온전히 보존하는 능력을 갖추었음을 입증합니다.

## 📌 핵심 기능

*   **고정밀 LaTeX 변환:** 모든 일반 텍스트와 수학 수식을 깔끔한 LaTeX 구문으로 정확하게 변환합니다.
*   **시각적 논리 추출 (VLE):** 핵심 기능. VLE는 시각적 요소를 단순히 묘사하는 대신, 그래프와 도형을 분석하여 문제 풀이에 필요한 조건(접점, 좌표, 영역의 경계 등)을 추출하고, 이 시각적 데이터를 기계가 읽을 수 있는 텍스트 태그로 변환합니다.
*   **100% 정보 무결성:** 텍스트에 명시된 정보는 물론 시각 자료에 암시된 정보까지, 변환 과정에서 어떤 정보도 유실되지 않도록 보장하는 엄격한 프로토콜을 따릅니다.
*   **표준화된 출력:** 모든 결과물은 예측 가능하고 구조화된 형식으로 제공되며, 최종 LaTeX 결과물은 반드시 코드 블록으로 감싸고 도형 정보는 `\text{[Visual Logic: ... ]}` 태그를 사용합니다.

## 🚀 시연 및 전체 풀이 과정

초기 LaTeX 변환부터 총 44개 문항의 최종 풀이에 이르는 전 과정이 단일 세션에서 연속적으로 진행되었습니다. 아래 링크를 통해 전체 작업 흐름을 검토하고 풀이 결과를 직접 확인할 수 있습니다.

**[Gemini에서 전체 풀이 과정 보기](https://gemini.google.com/share/0c8b03244339)**

> 문제 풀이에 대한 영상 자료가 필요하신 분은 `lemoaxtoria@gmail.com`로 문의해 주시기 바랍니다.

## 🛠️ 핵심 기술

이 시스템은 명확한 규칙 기반 아키텍처 위에 구축되어 있습니다.

1.  **시각적 논리 추출 (VLE):** 시각 자료를 해석하는 엔진. 예술이 아닌 논리를 추출하기 위해 4가지 핵심 규칙에 따라 작동합니다.
    *   **좌표:** 축에 표시된 특정 지점을 식별합니다.
    *   **관계:** 접선, 수직, 교점 등의 관계를 명시적으로 기술합니다.
    *   **영역:** 음영 처리되거나 지정된 영역의 정확한 경계를 정의합니다.
    *   **숨겨진 데이터:** "그림 참조"와 같이 텍스트에는 없고 그림에만 존재하는 데이터를 포착합니다.
2.  **3단계 운영 논리:** 정확성을 보장하는 순차적 프로세스입니다.
    *   **1단계: 문자적 변환:** 모든 텍스트와 수식을 그대로 변환합니다.
    *   **2단계: 심층 시각 스캔:** 모든 이미지를 VLE 규칙에 따라 처리합니다.
    *   **3단계: 무결성 검증:** 원본과 결과물을 교차 확인하여 100% 정보 보존을 보장합니다.
3.  **엄격한 출력 프로토콜:** 일관성과 사용성을 위한 엄격한 형식으로, 최종 LaTeX 결과물에 대해 마크다운 코드 블록 사용을 의무화합니다.

## ⚠️ 저작권 안내
본 프로젝트에서 인용된 대학수학능력시험 문항의 저작권은 한국교육과정평가원(KICE)에 있습니다. 해당 문항은 기술적 시연 및 검증의 목적으로만 사용되었습니다.

## 📜 License
MIT License
