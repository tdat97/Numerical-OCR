# Numerical-OCR
Number OCR

---

### Install

```
git clone https://github.com/tdat97/Numerical-OCR.git
cd Numerical-OCR
pip install -r requirments.txt
```

---

### Example

```python
from utils.ocr import OcrEngine
import matplotlib.pyplot as plt
```

```python
img = plt.imread("./temp/test_date_120cm.jpg")
plt.imshow(img)
```
![download](https://user-images.githubusercontent.com/48349693/202637615-0cc58234-8e8a-490e-8a6c-80af1ef975d1.png)

```python
ocr_engine = OcrEngine("./models/date_ocr.h5")
print(ocr_engine(img)) # '2022.11.06'
```

---

### Loss Figure

![epoch_loss](https://user-images.githubusercontent.com/48349693/202637897-38b20ea5-1caf-4969-84c0-4227a436f227.jpg)

---

### Prediction Plot

![savef_plt](https://user-images.githubusercontent.com/48349693/202638309-985a3c50-d397-4d86-b3e0-8cf83a0247fe.jpg)






