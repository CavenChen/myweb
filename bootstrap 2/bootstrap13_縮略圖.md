#13.�Y����

@(104-1.�����{���]�p)[bootstrap]

###��l�d�Ҧp�U:

```html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>�Y����</title>
<link href="../bootstrap/css/bootstrap.css" rel="stylesheet">
<!--[if lt IE 9]>
    <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
</head>
<body>
<div class="container">
  <h1 class="page-header">�Y����</h1>
  <a href="#"><img src="http://placehold.it/260x180" alt=""></a>
  <a href="#"><img src="http://placehold.it/260x180" alt=""></a>
  <a href="#"><img src="http://placehold.it/260x180" alt=""></a>
  <a href="#"><img src="http://placehold.it/260x180" alt=""></a>
</div>
<script src="../bootstrap/js/jquery-1.7.2.min.js"></script> 
<script src="../bootstrap/js/bootstrap.js"></script>
</body>
</html>
```

###�Y�Ϫ��˦��]�w

�Y�Ϥ@��O���ѨϥΪ̬d�ݤ@�t�C�Ϥ����Y�p��,bootstrap���ѳo�˪��˦�


```html
  <h1 class="page-header">�Y����</h1>
  <ul class="thumbnails">    (1)
    <li class="span3"><a class="thumbnail" href="#"><img src="http://placehold.it/260x180" alt=""></a></li>  (2)
    <li class="span3"><a class="thumbnail" href="#"><img src="http://placehold.it/260x180" alt=""></a></li>
    <li class="span3"><a class="thumbnail" href="#"><img src="http://placehold.it/260x180" alt=""></a></li>
    <li class="span3"><a class="thumbnail" href="#"><img src="http://placehold.it/260x180" alt=""></a></li>
  <ul>
```
1. ����Y�Ϫ��ƦC,�̵M�i�H�z�L`<ul>`+`<li>`�F��,���o�̨ϥ�`thumbnails`class
2. �b�C�i�ϸ̥������@�ǳ]�w,�H�o�Ҥl�ӻ�,
  - �o���|�i��,�C�i�Ϧ�3�Ӻ���,�]���ϥ�`span3`�ӳ]�w
  - �b`<a>`��ñ�̥[�J`thumbnail`class
  
**��: [http://placehold.it](http://placehold.it)�O�@�ӥi�H���ͦU�ؤؤo�Ϥ�������,�i�ۦ�e���F��**

�H�U�O��h���P�ؤo�Ϥ����Ҥl

```html
  <h1 class="page-header">�Y����</h1>
  <ul class="thumbnails">    (1)
    <li class="span3"><a class="thumbnail" href="#"><img src="http://placehold.it/260x180" alt=""></a></li>  (2)
    <li class="span3"><a class="thumbnail" href="#"><img src="http://placehold.it/260x180" alt=""></a></li>
    <li class="span3"><a class="thumbnail" href="#"><img src="http://placehold.it/260x180" alt=""></a></li>
    <li class="span3"><a class="thumbnail" href="#"><img src="http://placehold.it/260x180" alt=""></a></li>
	<li class="span6"><a class="thumbnail" href="#"><img src="http://placehold.it/520x380" alt=""></a></li>
    <li class="span6"><a class="thumbnail" href="#"><img src="http://placehold.it/520x180" alt=""></a></li>
    <li class="span3"><a class="thumbnail" href="#"><img src="http://placehold.it/260x180" alt=""></a></li>
    <li class="span3"><a class="thumbnail" href="#"><img src="http://placehold.it/260x180" alt=""></a></li>
  <ul>
```

