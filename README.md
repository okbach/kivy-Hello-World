# kivy-Hello-World
 kivy مرحبا بالعام  .

اولا نقوم باستدعاء App و Label:
```python
from kivy.app import App
from kivy.uix.label import Label
```
نقوم بتعريف الكلاسة الرئيسية و توريثها الكائن App :
```python
class mainApp(App):
```
 التي ينطلق منها السكريبت  build نقوم بتعريف الدالة 
```python
 class mainApp(App):
      def build(self):
 ```
 و اخيرا نقوم بارجاع الكائن الذي سيظهر في التطبيف :
 ```python
     def build(self):
         return Label(text='Hello World ')
 ```

![screenshot](https://github.com/Dev-loper0/kivy-Hello-World/blob/master/unnamed.png)
