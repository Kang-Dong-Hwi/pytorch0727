# pytorch0727


### 1. optimizer : Adagrad  ( lr=0.00001, weight_decay=0.9 )
-----
<table>
  <tr>
        <td>training dataset</td>
        <td>validation dataset</td>
        <td></td>
        <td>training dataset</td>
        <td>validation dataset</td>
  </tr>
  
  <tr>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/confusion_matrix/train_dataset_confusion_matrix1.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/confusion_matrix/validation_dataset_confusion_matrix1.png", height=200px, width=250px>   </td>
      <td></td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/confusion_matrix/train_dataset_confusion_matrix2.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/confusion_matrix/validation_dataset_confusion_matrix2.png", height=200px, width=250px>   </td>
  </tr>
  
  <tr>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/confusion_matrix/train_dataset_confusion_matrix3.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/confusion_matrix/validation_dataset_confusion_matrix3.png", height=200px, width=250px>   </td>
      <td></td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/confusion_matrix/train_dataset_confusion_matrix4.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/confusion_matrix/validation_dataset_confusion_matrix4.png", height=200px, width=250px>   </td>
  </tr>
</table>


Adagrad를 optim로  
epoch 50, batch 50으로 실행한 결과 입니다.  

training dataset, validation dataset에서 모두 처음 예측값으로만  



<br>
<br>
<br>

### 2. xavier_uniform, kaiming_uniform
-----------
<table>
  <tr>
        <td>training dataset</td>
        <td>validation dataset</td>
        <td></td>
        <td>training dataset</td>
        <td>validation dataset</td>
  </tr>
  
  <tr>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/confusion_matrix/train_dataset_confusion_matrix11.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/confusion_matrix/validation_dataset_confusion_matrix11.png", height=200px, width=250px>   </td>
      <td></td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/confusion_matrix/train_dataset_confusion_matrix12.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/confusion_matrix/validation_dataset_confusion_matrix12.png", height=200px, width=250px>   </td>
  </tr>
  

</table>

convolution층 사이에는 xavier_uniform  
linear층 사이에는 kaiming_uniform 추가



<br>
<br>
<br>

### 3. optimizer : Adam
-----------
<table>
  <tr>  <td colspan="5"> lr=10e-3 </td> </tr>
  <tr>
        <td colspan="2">initializer X</td> <td></td>
        <td colspan="2">initializer O</td>
  </tr>
  <tr>
        <td>training dataset</td>
        <td>validation dataset</td>
        <td></td>
        <td>training dataset</td>
        <td>validation dataset</td>
  </tr>

  <tr>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive01/train_dataset_confusion_matrix201.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive02/validation_dataset_confusion_matrix201.png", height=200px, width=250px>   </td>
      <td></td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive01/train_dataset_confusion_matrix202.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive02/validation_dataset_confusion_matrix202.png", height=200px, width=250px>   </td>
  </tr>
  
  
  <tr>  <td colspan="5"> lr=10e-4 </td> </tr>
  <tr>
        <td colspan="2">initializer X</td> <td></td>
        <td colspan="2">initializer O</td>
  </tr>
  <tr>
        <td>training dataset</td>
        <td>validation dataset</td>
        <td></td>
        <td>training dataset</td>
        <td>validation dataset</td>
  </tr>
  
  <tr>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive01/train_dataset_confusion_matrix203.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive02/validation_dataset_confusion_matrix203.png", height=200px, width=250px>   </td>
      <td></td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive01/train_dataset_confusion_matrix204.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive02/validation_dataset_confusion_matrix204.png", height=200px, width=250px>   </td>
  </tr>
  
  
  
  <tr>  <td colspan="5"> lr=10e-5 </td> </tr>
  <tr>
        <td colspan="2">initializer X</td> <td></td>
        <td colspan="2">initializer O</td>
  </tr>
  <tr>
        <td>training dataset</td>
        <td>validation dataset</td>
        <td></td>
        <td>training dataset</td>
        <td>validation dataset</td>
  </tr>
  
  <tr>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive01/train_dataset_confusion_matrix205.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive02/validation_dataset_confusion_matrix205.png", height=200px, width=250px>   </td>
      <td></td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive01/train_dataset_confusion_matrix206.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive02/validation_dataset_confusion_matrix206.png", height=200px, width=250px>   </td>
  </tr>
  
  
  
  <tr>  <td colspan="5"> lr=10e-6 </td> </tr>
  <tr>
        <td colspan="2">initializer X</td> <td></td>
        <td colspan="2">initializer O</td>
  </tr>
  <tr>
        <td>training dataset</td>
        <td>validation dataset</td>
        <td></td>
        <td>training dataset</td>
        <td>validation dataset</td>
  </tr>
  
  <tr>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive01/train_dataset_confusion_matrix207.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive02/validation_dataset_confusion_matrix207.png", height=200px, width=250px>   </td>
      <td></td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive01/train_dataset_confusion_matrix208.png", height=200px, width=250px>        </td>
      <td>    <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive02/validation_dataset_confusion_matrix208.png", height=200px, width=250px>   </td>
  </tr>
  
</table>


Adam에서 변수??초기화 효과?? 가 없었습니다.  
learning rate를 다양하게 해서 돌렸을V?? 때  
2*10e-5에서 loss값이 작게 측정되었습니다.


<br>
<br>
<br>

### Adam  ( lr = 2*10e-5 )
-------------
<table>
  <tr>  <td colspan="5"> lr=2*10e-5 </td> </tr>
  <tr>
        <td colspan="2">initializer X</td> <td></td>
        <td colspan="2">initializer O</td>
  </tr>
  <tr>
        <td>training dataset</td>
        <td>validation dataset</td>
        <td>training dataset</td>
        <td>validation dataset</td>
  </tr>
  
  <tr>
      <td>   <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive01/train_dataset_confusion_matrix211.png", height=200px, width=250px>        </td>
      <td>   <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive02/validation_dataset_confusion_matrix211.png", height=200px, width=250px>   </td>
      <td>   <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive01/train_dataset_confusion_matrix210.png", height=200px, width=250px>        </td>
      <td>   <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive02/validation_dataset_confusion_matrix210.png", height=200px, width=250px>   </td>
  </tr>
  
  <tr>
      <td colspan="4"> <br><br> epoch 200 </td>
  </tr>
  
  <tr>
      <td>   <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive01/train_dataset_confusion_matrix214.png", height=200px, width=250px>        </td>
      <td>   <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/gdrive02/validation_dataset_confusion_matrix214.png", height=200px, width=250px>   </td>
      <td colspan="2">  <img src="https://github.com/Kang-Dong-Hwi/pytorch0727/blob/master/Adam%20(1).png", height=250px, width=360px>                             </td> 
  </tr>

</table>

