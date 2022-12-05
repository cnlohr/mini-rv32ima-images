# mini-rv32ima-images

linux-5.18.0-rv32nommu-cnl-1.zip -- https://github.com/cnlohr/mini-rv32ima/tree/e690a30ac112d5f0fdffe1ebdfb290bb21d96c4e/configs

Image.ProfileTest.zip -- Image.ProfileTest -- Minimal image with `#define MAX_ORDER 10`, but it's enough to run coremark and immediately shut down.  Great for profiling the emulator.

Image-emdoom-MAX_ORDER_14.zip -- Image-emdoom-MAX_ORDER_14 -- Image made with Kenel 5.19, mini-rv32ima commit @ 5abbfc3cb7836da3b6d9cd78f118277be20f7717.  Manually edited MAX_ORDER to be 14 in mmzone.h.  Included copy of emdoom from same day.
