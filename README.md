# DFPlayerMiniMultiChip - A Mini MP3 Player For Arduino

This is forked version from original DFPlayer library to support **MH2024K-xxSS** chip. 
If you use DFPlayer Mini with MH2024K series chip define ```MH_ET_LIVE``` before 
include file ```DFRobotDFPlayerMini.h```.

```c
#define MH_ET_LIVE
#include <DFRobotDFPlayerMini.h>
```

---

DFPlayer - A Mini MP3 Player For Arduino
https://www.dfrobot.com/index.php?route=product/product&product_id=1121

This example shows the all the function of library for DFPlayer.

Created 2016-12-07
By [Angelo qiao](Angelo.qiao@dfrobot.com)

GNU Lesser General Public License.
See <http://www.gnu.org/licenses/> for details.
All above must be included in any redistribution

Notice and Trouble shooting

1.Connection and Diagram can be found here
https://www.dfrobot.com/wiki/index.php/DFPlayer_Mini_SKU:DFR0299#Connection_Diagram
2.This code is tested on Arduino Uno, Leonardo, Mega boards.
