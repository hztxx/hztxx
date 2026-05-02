# 👋 Hi, I'm hztxx
<!-- 嵌入式开发者签名 -->
💻 Embedded Developer | 🚀 C/STM32/FreeRTOS 实践者 | ⚡ Low-power MCU enthusiast

<!-- 嵌入式技术栈徽章 -->
<div align="center" style="letter-spacing: 2px; margin: 20px 0;">
  <!-- 核心语言 -->
  <img src="https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/-Embedded%20C-00599C?style=flat-square&logo=arm&logoColor=white" />
  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <!-- 平台与工具 -->
  <br/>
  <img src="https://img.shields.io/badge/-STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" />
  <img src="https://img.shields.io/badge/-FreeRTOS-00529B?style=flat-square&logo=freertos&logoColor=white" />
  <img src="https://img.shields.io/badge/-LVGL-FF6600?style=flat-square&logo=lvgl&logoColor=white" />
  <img src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/-VSCode-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white" />
  <img src="https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
</div>

---

```c
typedef struct {
    const char* pronouns;
    const char* langs[4];
    const char* tech[6];
    const char* state;
    const char* focus[3];
} DevInfo_t;

DevInfo_t me = {
    .pronouns = "He | Him",
    .langs = {"C", "Embedded C", "Python", "Makefile"},
    .tech = {"STM32", "FreeRTOS", "LVGL", "Git", "VSCode", "Linux"},
    .state = "Waiting for your interrupt",
    .focus = {"Lightweight C Libraries", "Embedded GUI", "Cross-platform Framework"}
};
