#8.����s��

@(104-1.�����{���]�p)[bootstrap]

###��l�d�Ҧp�U:

```html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>����</title>
<link href="../bootstrap/css/bootstrap.css" rel="stylesheet">
<!--[if lt IE 9]>
      <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
</head>

<body>
<div class="container">
  <h1 class="page-header">���� <small>���䪺�򥻼˦�</small></h1>
  
  <div style="margin-bottom:15px"> 
  	<a href="#"> �d�ݵ���</a>
  </div>
  
  <div style="margin-bottom:15px">
    <button type="submit">���b</button>
  </div>
  
  <div style="margin-bottom:15px">
    <input type="button" value="�]�m">
  </div>
  
</div>
<script src="../bootstrap/js/jquery-1.7.2.min.js"></script> 
<script src="../bootstrap/js/bootstrap.js"></script>
</body>
</html>


```

###���䪺�򥻳]�w

�b`<button>`����ñ�̥[�J`btn`class,�Y�i�o��@�Ӱ򥻪�����˦�

```html
<button class='btn'>�k���</button>
<button class='btn'>�m��</button>
<button class='btn'>�����</button>
```

�N�o�ǫ���s��,�u�n��`<div>`�]��,�å[�J`btn-group`class

```html
<div class='btn-group'>
	<button class='btn'>�k���</button>
	<button class='btn'>�m��</button>
	<button class='btn'>�����</button>
</div>
```

�N���P�s�յ��X���@�Ƥu��C
```html
<div class='btn-toolbar'>
	<div class='btn-group'>
		<button class='btn'>�k���</button>
		<button class='btn'>�m��</button>
		<button class='btn'>�����</button>
	</div>
	<div class='btn-group'>
		<button class='btn'>����</button>
		<button class='btn'>����</button>
		<button class='btn'>���u</button>
	</div>
</div>
```

###�b�u��C�̥[�J�U�Ԧ����
�o�ӥ\��i�H�b�W�z���u��C��,�[�J�@�ӤU�Ԧ������
**�`�N: �o�\�ॲ�ݤޤJ`jquery.js`��`bootstrap.js`�G�ӵ{���w��ॿ�`����**

```html
<div class="btn-toolbar">
	<div class="btn-group">
		<a class="btn dropdown-toggle" data-toggle="dropdown" href="#">�r�� <span class="caret"></span></a>	(1)
		<ul class="dropdown-menu">				(2)
			<li><a href="#">����</a></li>		(2)
			<li><a href="#">����</a></li>
			<li><a href="#">�駺</a></li>

		</ul>
	</div>
	<div class="btn-group">
		<a class="btn" href="#">�r��</a>			(3)
		<a class="btn dropdown-toggle" data-toggle="dropdown" href="#"><span class="caret"></span></a>
		<ul class="dropdown-menu">
			<li><a href="#">����</a></li>
			<li><a href="#">����</a></li>
			<li><a href="#">�駺</a></li>
		</ul>
	</div>
</div>  

```

1. �ϥ�`<a>`�өw�q�U�Կ����ܪ����D,�o�̭n�[�J`dropdown-toggle`class,�å[�J`data-toggle='dropdown'`���ݩʳ]�w! ���~,���F���o�Ӽ��D����n������,�i�H�b��r��[�J`<span>`�å[�J`caret`class,����ܤ@�ӦV�U���T����
2. �U�Կ�楲�ݥH`<ul>`��`<li>`��ñ�ӥ]�ФU�ԫ�i�諸����

3. �o�̪����k�O�N�U�Կ�檺���D�P�T�����Ÿ�,�������G�ӿW�ߪ�����,�Ȧb���U�T����������ɤ~�|���}�U�Կ��(�]���T�����̦��]�w`data-toggle`���ݩ�)