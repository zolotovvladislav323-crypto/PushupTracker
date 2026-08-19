<!-- Логотип и навигация -->
<div align="center">
  <img src="assets/logo.svg" alt="Логотип" width="128" height="128">
  <h1>Умный Трекер Отжиманий</h1>
  <p>Веб-приложение для подсчёта отжиманий с помощью компьютерного зрения</p>
</div>

<div align="center">
  <a href="#ru"><img src="https://img.shields.io/badge/Русский-blue?style=flat-square" alt="Русский"></a>
  <a href="#en"><img src="https://img.shields.io/badge/English-blue?style=flat-square" alt="English"></a>
  <a href="#zh"><img src="https://img.shields.io/badge/中文-blue?style=flat-square" alt="中文"></a>
</div>

---

<!-- ===================== РУССКИЙ ===================== -->
<h2 id="ru">🇷🇺 Русский</h2>

**Умный Трекер Отжиманий** — это веб-приложение, использующее камеру устройства и библиотеку MediaPipe Pose для отслеживания движений тела в реальном времени. Оно позволяет автоматически считать количество отжиманий, контролировать правильность выполнения упражнения и даёт визуальную обратную связь.

Проект написан на чистом HTML/CSS/JavaScript и не требует установки дополнительного ПО — достаточно открыть страницу в браузере.

### Основные возможности
- **Автоматический подсчёт отжиманий** — приложение фиксирует каждый цикл «вниз-вверх» на основе угла в локтевом суставе.
- **Контроль техники** — отслеживается прямая спина и горизонтальное положение тела, выводятся предупреждения о неправильной позе.
- **Визуализация скелета** — наложение ключевых точек и соединений на видеопоток для наглядности.
- **Простой интерфейс** — одна кнопка «Старт»/«Стоп» и отображение текущего счёта и статуса.
- **Работает в реальном времени** — низкая задержка благодаря оптимизированным моделям MediaPipe.
- **Поддержка мобильных устройств** — адаптивный дизайн и использование фронтальной камеры.
- **Без серверной части** — все вычисления выполняются локально в браузере, данные никуда не передаются.

---

<!-- ===================== ENGLISH ===================== -->
<h2 id="en">🇬🇧 English</h2>

**Smart Push-Up Tracker** is a web application that uses your device's camera and the MediaPipe Pose library to track body movements in real time. It automatically counts push-ups, monitors exercise form, and provides visual feedback.

The project is built with plain HTML/CSS/JavaScript and requires no additional installation — just open the page in a browser.

### Key Features
- **Automatic push-up counting** — the app detects each "down-up" cycle based on the elbow angle.
- **Form control** — tracks straight back and horizontal body position, warns about incorrect posture.
- **Skeleton visualization** — overlays key points and connections on the video stream for clarity.
- **Simple interface** — a single "Start"/"Stop" button with live count and status display.
- **Real-time performance** — low latency thanks to optimized MediaPipe models.
- **Mobile-friendly** — responsive design and front-facing camera support.
- **No server side** — all computations run locally in the browser, no data is sent anywhere.

---

<!-- ===================== 中文 ===================== -->
<h2 id="zh">🇨🇳 中文</h2>

**智能俯卧撑追踪器** 是一款 Web 应用程序，使用设备摄像头和 MediaPipe Pose 库实时跟踪身体运动。它可以自动计数俯卧撑，监控运动姿势，并提供视觉反馈。

该项目使用纯 HTML/CSS/JavaScript 构建，无需额外安装 — 只需在浏览器中打开页面即可。

### 主要功能
- **自动计数俯卧撑** — 应用根据肘关节角度检测每个“下-上”循环。
- **姿势控制** — 跟踪直背和水平身体位置，提醒不正确的姿势。
- **骨架可视化** — 在视频流上叠加关键点和连接，清晰直观。
- **简单界面** — 一个“开始/停止”按钮，实时显示计数和状态。
- **实时性能** — 得益于优化的 MediaPipe 模型，延迟低。
- **适配移动设备** — 响应式设计，支持前置摄像头。
- **无需服务器** — 所有计算在浏览器本地完成，数据不会外传。

---

**↑ [Наверх / Back to top](#)**
