#10.����

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
  <h1 class="page-header">����</h1>
  

</div>
<script src="../bootstrap/js/jquery-1.7.2.min.js"></script> 
<script src="../bootstrap/js/bootstrap.js"></script>
</body>
</html>
```

###���Ҫ��]�w

���Ҫ��]�w�P�ɯ誺�]�w�۷�����,�]�O�z�L`<ul>`+`<li>`�ӳ]�w���ؤ��e
```html
<div class="container">		
	<h1 class="page-header">����</h1>
	<ul class="nav nav-tabs">		(1)
		<li class="active"><a href="#">Wordpress</a></li>		
		<li><a href="#">Drupal</a></li>
		<li><a href="#">Joomla</a></li>
	</ul>
</div>

```

1. �P�ɦ�����P���O,�o�̧��`nav-tabs`class

---

���ҹw�]�O��V�ƦC,�Y�n���V�ƦC,�u�n�b�W�z(1)�B,�A�[�J`nav-stacked`class�Y�i

```html
<div class="container">	
	<h1 class="page-header">����</h1>
	<ul class="nav nav-tabs nav-stacked">		
		<li class="active"><a href="#">Wordpress</a></li>		
		<li><a href="#">Drupal</a></li>
		<li><a href="#">Joomla</a></li>
	</ul>
</div>
```
---

���ҥi�H���pills���˦�

```html
<div class="container">
	<h1 class="page-header">����</h1>
	<ul class="nav nav-pills">
		<li class="active"><a href="#">Wordpress</a></li>
		<li><a href="#">Drupal</a></li>
		<li><a href="#">Joomla</a></li>
	</ul>
</div>
```

####���ҹ��������e
���Ҧb�I���,�i�H������ܩҹ��������e,�H�U�O�ӧ��㪺�򥻽d��
**�`�N:�o�ӥ\��ݭn�ޤJjquery.js��boostrap.js�G�ӵ{���w**
```html
<div class="container">
	<h1 class="page-header">����</h1>
	<ul class="nav nav-tabs">
		<li class="active"><a href="tab1" data-toggle="tab">Wordpress</a></li> (3)
		<li><a href="tab2" data-toggle="tab">Drupal</a></li>
		<li><a href="tab3" data-toggle="tab">Joomla</a></li>
	</ul>
	<div class="tab-content">  (1)
		<div class="tab-pane active" id="tab1"><p>Wordpress, �u����CMS</p></div>  (2)
		<div class="tab-pane" id="tab2"><p>Drupal, �F���j�j��CMS</p></div>
		<div class="tab-pane" id="tab3"><p>Joomla, ²����Ϊ�CMS</p></div>		
	</div>
</div>
```

1. ���Ҥ��e���]��`<div>`����,�n�[��`tab-content`class
2. �C�@�ӭ��ҩҹ��������e,�n�[�J`tab-pane`class,��`id`�ݩ�,�Y���@�Τ������e,�P�ɤ]�n�A�[�J`active`class
3. �o�̪�`href`�n���w��W�z��`id`�ݩ�.���~,�٭n�A�[�J`data-toggle="tab"`���ݩʳ]�w

---

####���ܭ��Ҫ��ƦC��m(��V)
���Ұ��F�w�]��"���Ҧb�W���e�b�U"���ƪk���~,bootstrap�ٴ��ѤF�t�~�T��

- `tabbable tabs-left` ���Ҧb��
- `tabbable tabs-right` ���Ҧb�k
- `tabbable tabs-below` ���Ҧb�U,�Y�ϥγo�ؤ覡,�n�N���Ҫ�html��b���e���U

```html
<div class="container">
	<h1 class="page-header">����</h1>
	<div class="tabbable tabs-left">
		<ul class="nav nav-tabs">
			<li class="active"><a href="tab1" data-toggle="tab">Wordpress</a></li> (3)
			<li><a href="tab2" data-toggle="tab">Drupal</a></li>
			<li><a href="tab3" data-toggle="tab">Joomla</a></li>
		</ul>
		<div class="tab-content">  (1)
			<div class="tab-pane active" id="tab1"><p>Wordpress, �u����CMS</p></div>  (2)
			<div class="tab-pane" id="tab2"><p>Drupal, �F���j�j��CMS</p></div>
			<div class="tab-pane" id="tab3"><p>Joomla, ²����Ϊ�CMS</p></div>		
		</div>
	</div>
</div>
```
