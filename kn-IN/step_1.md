## ಪರಿಚಯ

ನಿಮ್ಮ ಸ್ನೇಹಿತರೊಂದಿಗೆ ನೀವು ಎಷ್ಟು ಹೊಂದಾಣಿಕೆಯಾಗಿದ್ದೀರಿ ಎಂದು ಹೇಳಲು ನಿಮ್ಮ micro:bit ಅನ್ನು ನೀವು ಕೋಡ್ ಮಾಡಲು ಹೊರಟಿದ್ದೀರಿ.

**ಸೂಚನೆಗಳು**: ನೀವು ಇದನ್ನು ಆನ್‌ಲೈನ್‌ ಓದುತ್ತಿದ್ದರೆ, ನಿಮ್ಮ ಸ್ನೇಹದ ರೇಟಿಂಗ್ ಅನ್ನು ಕಂಡುಹಿಡಿಯಲು ಸ್ನೇಹಿತರೊಂದಿಗೆ ಕೆಳಗಿನ micro:bit ನಲ್ಲಿ **A+B** ಒತ್ತಿರಿ.

<div class="trinket" style="width:400px;margin: 0 auto;">
<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_iLDhcVa0K2Fd" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-scripts allow-same-origin" frameborder="0"></iframe></div>
</div>

### ಕ್ಲಬ್ ಮುಖಂಡರಿಗೆ ಹೆಚ್ಚುವರಿ ಮಾಹಿತಿ

ನೀವು ಈ ಪ್ರಾಜೆಕ್ಟನ್ನು ಮುದ್ರಿಸಬೇಕಾದರೆ, ದಯವಿಟ್ಟು [ಮುದ್ರಕ-ಸ್ನೇಹಿ ಆವೃತ್ತಿಯನ್ನು ಬಳಸಿ](https://projects.raspberrypi.org/en/projects/rate-your-mates/print).

## \--- collapse \---

## title: ಕ್ಲಬ್ ಮುಖಂಡರ ಟಿಪ್ಪಣಿಗಳು

## ಪರಿಚಯ:

ಈ ಪ್ರಾಜೆಕ್ಟಲ್ಲಿ, ಮಕ್ಕಳು ಹೊಂದಾಣಿಕೆಯ ಪ್ರೋಗ್ರಾಂ ಮಾಡುವ ಮೂಲಕ variables ಮತ್ತು random number ಗಳನ್ನು ಹೇಗೆ ಬಳಸಬೇಕೆಂದು ಕಲಿಯುತ್ತಾರೆ. ಇಬ್ಬರು ಬಳಕೆದಾರರು micro:bit ನಲ್ಲಿ ಒಂದು ಗುಂಡಿಯನ್ನು ಒತ್ತುತ್ತಾರೆ, ನಂತರ ಅದು ಅವರ ಶೇಕಡಾವಾರು ಹೊಂದಾಣಿಕೆಯ ತಿಳಿಸುತ್ತದೆ.

## ಸಂಪನ್ಮೂಲಗಳು

ಈ ಪ್ರಾಜೆಕ್ಟಗೆ [MakeCode (PXT)](http://jumpto.cc/mb-new) microbit editor ಅನ್ನು ಉಪಯೋಗಿಸಿ.

ಈ ಪ್ರಾಜೆಕ್ಟ್ ನ ಪೂರ್ಣಗೊಂಡ ಆವೃತ್ತಿಯನ್ನು ನೀವು [makecode.microbit.org/#pub:57756-45098-79806-84952](https://makecode.microbit.org/#pub:57756-45098-79806-84952) ನಲ್ಲಿ ಕಾಣಬಹುದು. ಮತ್ತು ಈ ಪ್ರಾಜೆಕ್ಟ್ ಗಾಗಿ 'ಪ್ರಾಜೆಕ್ಟ್ ಮೆಟೀರಿಯಲ್ಸ್ ಡೌನ್‌ಲೋಡ್' ಲಿಂಕ್ ಅನ್ನು ಕ್ಲಿಕ್ ಮಾಡುವುದರ ಮೂಲಕ ಕಂಪೈಲ್ ಮಾಡಿದ .hex ಫೈಲ್ ಅನ್ನು ಡೌನ್‌ಲೋಡ್ ಮಾಡಬಹುದು, ಇದರಲ್ಲಿ ಇವು ಸೇರಿವೆ:

* microbit-Rate-Your-Mates.hex

## ಕಲಿಕೆಯ ಉದ್ದೇಶಗಳು

* `>` ಮತ್ತು `<` ಸಂಬಂಧಿತ ನಿರ್ವಾಹಕಗಳು;
* ಪುನರಾವರ್ತನೆ (` for` ಲೂಪ್).

ಈ ಪ್ರಾಜೆಕ್ಟ್ [Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum) ಎಳೆಗಳಿಂದ ಕೆಳಗಿನ ಅಂಶಗಳನ್ನು ಒಳಗೊಂಡಿದೆ:

* [ಸರಳ ಪ್ರೊಗ್ರಾಂಗಳನ್ನು ರಚಿಸಲು ಮೂಲ ಪ್ರೋಗ್ರಾಮಿಂಗ್ ರಚನೆಗಳನ್ನು ಬಳಸಿ.](https://www.raspberrypi.org/curriculum/programming/creator)

## ಸವಾಲುಗಳು

* "ಕಡಿಮೆ ರೇಟಿಂಗ್" - `if` ಸ್ಟೆಟ್ಮೆಂಟ್ ಮತ್ತು `<` ಸಂಬಂಧಿತ ಆಪರೇಟರ್ ರೇಟಿಂಗ್ 25 ಕ್ಕಿಂತ ಕಡಿಮೆ ಇದ್ದರೆ ಅಡ್ಡ ಅಥವಾ ದುಃಖದ ಮುಖವನ್ನು ತೋರಿಸಲು.
* "ಇನ್ನಷ್ಟು ಅನಿಮೇಷನ್‌ಗಳು" - `for` loop ಬಳಸಿ ಹೆಚ್ಚಿನ ಅನಿಮೇಷನ್ಗಳನ್ನು ರಚಿಸಿ.

\--- /collapse \---

## \--- collapse \---

## ಶೀರ್ಷಿಕೆ: ಪ್ರಾಜೆಕ್ಟ್ ವಸ್ತುಗಳು

## ಕ್ಲಬ್ ಮುಖಂಡರ ಸಂಪನ್ಮೂಲಗಳು

* [ಆನ್‌ಲೈನ್ ಪೂರ್ಣಗೊಂಡ ಪ್ರಾಜೆಕ್ಟ್](https://makecode.microbit.org/#pub:57756-45098-79806-84952)
* [.hex ಪ್ರಾಜೆಕ್ಟ್ ಫೈಲ್ಲ್ ಅನ್ನು ನಿಮ್ಮ micro:bit ‌ಗೆ ವರ್ಗಾಯಿಸಲು](resources/microbit-Rate-Your-Mates.hex)

\--- /collapse \---