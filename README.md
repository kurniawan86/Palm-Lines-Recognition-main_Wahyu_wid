## Palm Line Recognition

<img src="https://img.freepik.com/free-vector/human-hands-white-background_1308-75768.jpg?w=1380&t=st=1686906761~exp=1686907361~hmac=d7b1e8fe5caf7c1c7653b1ca9c900227f96d79ecdab0d2fddb9cdf40f15ce09c"/>

<center><b>Pengenalan Garis Tangan</b></center>

<br>

### Dataset

1. Download Dataset pada link berikut:
   [Google Drive](https://drive.google.com/file/d/1Fa6oUmFeWzz58tbTcM-EppA1HXC94EG_/view?usp=sharing)
2. Extract file zip
3. Pastikan didalam folder dataset ini memiliki struktur seperti berikut

```
dataset
    | test
        | ... file-file gambar testing
    | train
        | folder class 1
            | ... file-file gambar
        | folder class 2
            | ... file-file gambar
        | folder class 3
            | ... file-file gambar
        ...
    | valid
        | folder class 1
            | ... file-file gambar
        | folder class 2
            | ... file-file gambar
        | folder class 3
            | ... file-file gambar
        ...
```

<br>

### Model Trained

Arsitektur AlexNet telah di train untuk kasus dataset ini dengan banyak epoch sebanyak 20 epochs

File hasil train dapat didownload disini:
[Google Drive](https://drive.google.com/file/d/1RKAW4BYhl-RtGRpnddZSibWN5I6rjH7f/view?usp=sharing)

<br>

### Arsitektur

<img src="https://raw.githubusercontent.com/blurred-machine/Data-Science/master/Deep%20Learning%20SOTA/img/alexnet2.png"/>
<center><b>AlexNet</b></center>
