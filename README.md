Bot for [wplace.live](https://wplace.live).  
Bot also works on [pixelplanet.fun](https://pixelplanet.fun) and [pixmap.fun](https://pixmap.fun).  

> [!WARNING]  
> The bot was originally created for other pixel games. Adaptation for wplace is still raw and may work unstable!

**Installation**  
1. [Download Tampermonkey](https://www.tampermonkey.net)
2. [Install bot](https://touchedbydarkness.github.io/stuff/ppf_bot_2/initer.user.js)

**Usage**  
 * Choose image.  
 * The colors of the image will be automatically converted if you don't care about it, but it REALLY better to use some converter or quantizer.  
 * Press key "N" to set the start coordinates.  
 * Press key "B" to start/stop or press button in bot interface.  
 * If a captcha appears, the bot will notify you with notification and sound.  
 * After solving captcha run bot to continue.  

**Strategies**  
 * *human*  
    Uses logs from one of the canvases to form a pattern.
 * *near*  
    Next pixel is always closest to last placed.
 * *random*  
    Just random.
 * *4 linear strategies*  
    Paints from top to bottom or in another direction, depends on strategy.
 * *2 circle strategies*  
    Circle expanding from the center to the edges or vice versa.
 * *4 chess strategies*  
    The drawing pattern resembles a chessboard.
 * *and many other strategies*  
    Really many, about 30-40.

**Notes**  
  * Interface has several translations. In addition to English, the languages include Spanish, Russian, Arabic and Azerbaijani.
  * There is a tab for screenshots of the game canvas with custom coordinates. No size restrictions, in theory. (for wplace enable debug in "other" tab to open coordinates window and use last coord pair to fill fields)
  * Another tab for saving interesting points on the canvas. (didnt adapted for wplace yet)
  * And optional custom theme for some canvases by me. (didnt adapted for wplace yet)

**[My discord server](https://discord.gg/VyfVmD2nhZ)**  
 There you can tell about bugs, suggestions, translate interface to new language or find test version with new but unstable features.  
**[You can also help me with your donation](https://boosty.to/touchedbydarkness)**
