### Osram-Bulb-Infrared
Infrared addresses and the data values of the Osram RGB Lightbulb Remote.

<img src="https://i.imgur.com/BEoPMv9.jpg" width=300>

---

#### **Colors**
> The combinations start from top-right to left. <br>
> **The address is always '0x0000'**

| C1 | C2 | C3  | C4 |
| ------------- | ------------- | ------------- | ------------- |
|   -   |   -   |   -   |    -   |
| 0x08  | 0x09  | 0x0a  | 0x03  |
| 0x0c  | 0x0d  | 0x0e  |   -   |
| 0x10  | 0x11  | 0x12  |   -   |
| 0x14  | 0x15  | 0x16  |   -   |
| 0x18  | 0x19  | 0x1a  |   -   |


#### **Controls**
> The combinations start from top-right to left. <br>
> **The address is always '0x0000'**

| C1 | C2 | C3  | C4 |
| ------------- | ------------- | ------------- | ------------- |
| 0x00  | 0x02  |  0x06 |  0x07  |
|   -   |   -   |   -   |    -   |
|   -   |   -   |   -   |  0x0f  |
|   -   |   -   |   -   |  0x13  |
|   -   |   -   |   -   |  0x17  |
|   -   |   -   |   -   |  0x1b  |


#### **Whole**
> The combinations start from top-right to left. <br>
> **The address is always '0x0000'**

| C1 | C2 | C3  | C4 |
| ------------- | ------------- | ------------- | ------------- |
| 0x00  | 0x02  |  0x06 |  0x07  |
|   0x08   |   0x09   |   0x0a   |    0x03   |
|   0x0c   | 0x0d   |   0x0e   |  0x0f  |
|   0x10   |   0x11   |   0x12   |  0x13  |
|   0x14   |   0x15   |   0x16   |  0x17  |
|   0x18   |   0x19   |   0x1a   |  0x1b  |

---

###### _Note: The NEC protocol should be use if you're planning on IR transmitting._ <br>
###### _Note: Transmitting could be easily accomplished using [this](https://github.com/peterhinch/micropython_ir) library on micropython._

---
