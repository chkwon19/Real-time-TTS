## Real-time TTS

- 실시간 합성 가능한 버전
- 딥러닝 기반 종단간(end-to-end) TTS 시스템은 다음 두 가지 과정으로 구성
    - 텍스트에서 스펙트로그램을 생성하는 Text2Mel 과정 
        - FastPitch, FastSpeech2, FastSpeech 등  
    - 스펙트로그램에서 음성신호를 합성하는 보코더 
        - WaveGlow, Multiband_MelGAN 등  