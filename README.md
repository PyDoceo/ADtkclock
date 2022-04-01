**_ADtkclock_**

ADtkclock is simple and "programmable" clock used only in tkinter
project.
### How to install
Installation via pip
```commandline
pip install ADtkclock
```

### Short Documentation

***Digital Clock***
Code to make simple _**Digital Clock**_ in your tkinter window.
```python
import tkinter
from ADtkclock import DigitalClock
root = tkinter.Tk()
label = tkinter.Label(root, font=("TkTextFont", 50))
label.pack()
DigitalClock(label)
root.mainloop()
```
***Timer***
Code to make simple **_Timer_** in your tkinter window.
```python
import tkinter
from ADtkclock import Timer
root = tkinter.Tk()
label = tkinter.Label(root, font=("TkTextFont", 50))
label.pack()
Timer(label, minute=10, second=10)
root.mainloop()
```
***Stopwatch***
Code to make simple **_Timer_** in your tkinter window.
```python
import tkinter
from ADtkclock import StopWatch
root = tkinter.Tk()
label = tkinter.Label(root, font=("TkTextFont", 50))
label.pack()
stopwatch = StopWatch(label)
stopwatch.start()
root.mainloop()
```

License
MIT
