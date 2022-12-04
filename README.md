# Pynput

Pynput is a in-game user input module for Pygame engine. It is minimal and highly expandable with easy 
and is easy to set up. The input boxes are customizable and is rendered as a object.

### Installation:
Use the python package installer to install pynput ( `pygame_pynput` )
```
$ pip install pygame_pynput
```

### Usage:
Directly import the input object using 
```
from pynput import Pynput

# Pynput is the input object
```

### Pynput:
Pynput takes the following parameters:
```
display: Surface,  
x_coord: int, 
y_coord: int, 
width: int, 
height: int, 
text: str = '', 
color: int | tuple[int] = 200,
border: int = 1, 
border_radius: int = 0
```

to render the `Pynput object` to the screen,
```
{ pynput_object }.draw()
```

To, activate the pynput object,
```
{ pynput_object }.click()
```

You also have to pass in the keydown events to the pynput object using,
```
{ pynput_object }.handle_input(event)
```


