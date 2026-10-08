# markcut-fonts

「浮水印」App（[idoluidoluidolu/markcut](https://github.com/idoluidoluidolu/markcut)）裡「點了才下載」的字型檔。

App 用**固定 commit** 的網址抓檔（jsDelivr，備援 raw.githubusercontent.com），每個檔都對 sha256。所以：

- 不要改寫這個 repo 的歷史、不要刪檔或覆蓋同名檔——舊版 App 還指著舊 commit 的網址
- 換字型或更新版本：放新檔名，App 改指新的 commit

| 檔案 | 字型 | 作者 | 這裡放的版本 |
|---|---|---|---|
| `fonts/PopGothic.ttf` | 大波浪圓體（Pop Gothic CJK TC） | The PopGothic Project Authors（Max Yao），[max32002/pop-gothic](https://github.com/max32002/pop-gothic) | Big5 子集 |
| `fonts/JasonHandwriting3.ttf` | 清松手寫體 3 | 游清松；補字 Max Yao，[max32002/JasonHandWritingFonts](https://github.com/max32002/JasonHandWritingFonts) | 作者發布的原檔，未修改 |
| `fonts/JasonHandwriting5.ttf` | 清松手寫體 5 | 游清松；補字 Max Yao，同上 | Big5 子集 |
| `fonts/Bakudai.ttf` | 莫大毛筆 | 原作青柳衡山（衡山毛筆フォント）；改作 Max Yao，[max32002/bakudaifont](https://github.com/max32002/bakudaifont) | 作者發布的原檔，未修改 |
| `fonts/FusionPixel.ttf` | 縫合像素 12px 比例 繁體 | TakWolf，[TakWolf/fusion-pixel-font](https://github.com/TakWolf/fusion-pixel-font) | Big5 子集 |

全部是 [SIL Open Font License 1.1](https://openfontlicense.org)，授權全文在 `licenses/`。

Big5 子集＝cp950 全部的字（常用 5401＋次常用 7652＋標點注音）＋ASCII＋常用標點＋直排標點，排版功能（含直排 `vert`）全部保留。
莫大毛筆與清松手寫體 3 宣告了保留字型名稱（Reserved Font Name），改過的版本不能沿用原名，所以這兩款放的是作者發布的原檔；其餘三款沒有保留字型名稱。
