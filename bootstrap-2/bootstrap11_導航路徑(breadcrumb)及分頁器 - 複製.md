#11.�ɯ���|(breadcrumb)�Τ�����

@(104-1.�����{���]�p)[bootstrap]

###��l�d�Ҧp�U:

```html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>�ɯ���|�P������</title>
<link href="../bootstrap/css/bootstrap.css" rel="stylesheet">

<!--[if lt IE 9]>
      <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
</head>

<body>
<div class="container">
  <h1 class="page-header">�ɯ���|�P������</h1>
</div>
<script src="../bootstrap/js/jquery-1.7.2.min.js"></script> 
<script src="../bootstrap/js/bootstrap.js"></script>
</body>
</html>
```

###�ɯ���|���]�w

�ɯ���|���@�άO�Ψ���ܥثe���������W�U�h�۹��m. �ɯ���|�]�٤���"�ѥ]�h"


```html
<div class="container">		
	<h1 class="page-header">�ɯ���|�P������</h1>
	<ul class="breadcrumb">		(1)
		<li><a href="#">����</a><span class="divider">/</span></li>	(2)	
		<li class="active">���~�C��</li>
	</ul>
</div>

```

1. �P�ɦ�����P���O,�o�̧��`breadcrumb`class
2. �o�̪�`<span>`�O�@�Ӥ��j�Ÿ�

---

###���������]�w

�������@��O�Φb���ƶW�L�@����,�i�H���ѨϥΪ̤�������w����ƭ��W

```html
<div class="container">		
	<h1 class="page-header">�ɯ���|�P������</h1>
	<ul class="breadcrumb">		
		<li><a href="#">����</a><span class="divider">/</span></li>	
		<li class="active">���~�C��</li>
	</ul>
	<div class="pagination">	(1)
		<ul>
			<li><a href="#">1</a></li>
			<li class="active"><a href="#">2</a></li>
			<li><a href="#">3</a></li>
			<li><a href="#">4</a></li>
			<li><a href="#">5</a></li>
		</ul>
    </div>
</div>
```

1. �o�̥u�n�ϥ�`pagination`class�N��F���N`<li>`���س]�����������ĪG. ���~,�o���٥i�H�A�[�J`pagination-centered`��`pagination-right`�ӳ]�w���������m���ƦC�άO�a�k�ƦC!

---

####²�櫬��������
���������]�p,�٦��t�@�ر`�Ϊ�²�櫬������,���u��"�e�@��"��"��@��"�G�ӫ���

```html
<ul class="pager">
	<li class="previous"><a href="#">�e�@��</a></li>
	<li class="next"><a href="#">��@��</a></li>
</ul>
```
