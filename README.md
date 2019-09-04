# DVC-in-use-example
Run inference.py script to test **resnext101_32x4d** model:
```
python3 inference.py
```
Default image for classification is <tt>data/cat.jpg</tt>. To specify the image use <tt>--path_img</tt> key: 
```
python3 inference.py --path_img data/croco.jpg              
```
Run unit tests (described in <tt>utest_inference.py</tt>) to test classifier results in the following way:
```
python3 -m unittest test.utest_inference -v
```
