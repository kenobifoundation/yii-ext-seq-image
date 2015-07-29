# yii-ext-seq-image

Yii Framework Extension - An simple slideshow of images

## Requirements

Tested 1.1.8x

## Usage

```php
$this->widget('application.extensions.seqimage.SeqImage',array(
  'widthImage' => 650, 
  'heightImage' => 340,
  'slides'=>array(  
       array(
           'image'=>array('src'=>Yii::app()->request->baseUrl.'/images/test.jpg'),            
           'link'=>array('url'=>'mypage','htmlOptions'=>array())
       ),
       array(
           'image'=>array('src'=>Yii::app()->request->baseUrl.'/images/any.jpg'),            
       ),
      array(
           'image'=>array('src'=>Yii::app()->request->baseUrl.'/images/anyany.jpg'),            
       )
  )));
```
