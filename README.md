# 3채널 NS-SAR 탐색기

400 MS/s, BW 50 MHz, OSR 4 조건의 3채널 time-interleaved noise-shaping SAR ADC 행동 모델입니다.
CDAC 샘플링 C와 hold cap C_H를 바꾸면서 출력 FFT, TI spur, SNDR, 전력 추정이 어떻게 바뀌는지 브라우저에서 바로 시뮬레이션합니다.

- 구조: 채널당 12-bit 변환(Filtering 1 ns / Sampling 1 ns / Conversion 5.5 ns), shared FIA, 채널별 hold cap 3개를 리셋 없이 누적
- 잡음·매칭·전력 계수는 모두 가정값이며 공정(PDK) 예측이 아닙니다.
- 설치 없이 `index.html` 하나로 동작합니다.
