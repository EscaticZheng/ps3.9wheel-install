# ps3.9wheel-install
Install PaddleSpeech in python3.9 on windows without anything about visual studio.
# Usage
First, you need install **paddlepaddle**.  
Then
```cmd
pip install llvmlite-0.39.1-cp39-cp39-win_amd64.whl  
pip install numpy-1.23.5-cp39-cp39-win_amd64.whl  
pip install numba-0.56.4-cp39-cp39-win_amd64.whl  
pip install scipy==1.10.0                       #the whl is bigger than 25MB, so can't upload to repository 
pip install scikit_learn-1.2.1-cp39-cp39-win_amd64.whl  
for %x in (*.whl) do pip install %x             #install all the other packages
```
Finally, install **paddlespeech**, you will find no more source code compile which needs **VISUAL STUDIO**!
