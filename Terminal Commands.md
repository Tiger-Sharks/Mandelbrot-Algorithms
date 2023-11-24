# Terminal Execution Commands

## Python
### Windows (in Powershell)
```
Measure-Command { python .\Mandelbrot.py 16000 }
```

### macOS or Linux
```
time python Mandelbrot.py 16000 > /dev/null
```