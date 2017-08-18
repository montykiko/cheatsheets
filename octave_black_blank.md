```
@title : (ovtave kernel) plot shows black blank in jupyter
Created on 2017-08-18
@author : Jixue
```

[Reference](https://github.com/Calysto/octave_kernel/issues/82)

### system : 

win 10
### environment : 
jupyter notebook octave kernel
### problem : 
In octave, plot works fine

In jupyter, the plot is black, but axes and ticks are show.
###solving : 
This is a limitation of the print function in Octave used to create the figure.

You can try specifying an svg as **%plot -f svg** or trying another graphics backend in your Octave session.

