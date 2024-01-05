# MayaBifrostMirrorVector
Studying the Maya Bifrost by recreating a mirror vector math using nodes
Using the mirror vector math: R = 2(N * L) * N - L

![alt text](https://github.com/AlexGaida/MayaBifrostMirrorVector/blob/main/bifrost_mirror_vector.png?raw=true)

*please note that Bifrost currently is unable to draw nurbsCurve lines, in the picture above is for visualization purposes only

```python
import ag_reflectionVectorBifrost
#...run the testcase that proves the work-ability of the Bifrost compound node
ag_reflectionVectorBifrost.create_default_test()
```
Alternatively, you can also use your own transform objects transposed in local space:

```python
import ag_reflectionVectorBifrost
ag_reflectionVectorBifrost.create_mirror_vector("locator1")
```
