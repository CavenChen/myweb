#4.�C��

@(104-1.�����{���]�p)[bootstrap]

###��l�d�Ҧp�U:

```html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>�`�Ϊ� CSS</title>
<link href="../bootstrap/css/bootstrap.css" rel="stylesheet">
<!--[if lt IE 9]>
      <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
</head>

<body>
<div class="container">
  <h1 class="page-header">�C��<small> �L�ǦC��A���ǦC��A�y�z�C��</small></h1>
  <h2>�L�ǦC��</h2>
  
  Drupal
  Joomla
  Wordpress
  
  <h2>���ǦC��</h2>
 
  Drupal
  Joomla
  Wordpress
  
  <h2>�y�z�C��</h2>
  
  Drupal
  �j�j���F����CMF
  Joomla
  ²����Ϊ�CMS
  Wordpress
  �u�������e�o�G����

</div>
<script src="../bootstrap/js/jquery-1.7.2.min.js"></script> 
<script src="../bootstrap/js/bootstrap.js"></script>
</body>
</html>
```

###�C���ñ
�C���ñ���H�U�T��
1. �L�ǦC��: �C�������بS���T�w����
2. ���ǦC��
3. �y�z�C��

####�L�ǦC��: `<ul>`+`<li>`

```html
<h2>�L�ǦC��</h2>
<ul>
	<li>Drupal</li>
	<li>Joomla</li>
	<li>Wordpress</li>
<ul>
```

####���ǦC��:`<ol>`+`<li>`

```html
<h2>���ǦC��</h2>
<ol> 
  <li>Drupal</li>
  <li>Joomla</li>
  <li>Wordpress</li>
</ol>
```

####�y�z�C��:`<dl>`+`<dt>`+`<dd>`

```html
<h2>�y�z�C��</h2>
<dl> 
  <dt>Drupal</dt>
  <dd>�j�j���F����CMF</dd>
  <dt>Joomla</dt>
  <dd>²����Ϊ�CMS</dd>
  <dt>Wordpress</dt>
  <dd>�u�������e�o�G����</dd>
</dl>  
```

�p�G�Q�N`<dl>`�̪����ؤ����ƦC,�i�H�[�J`dl-horizontal`class

```html
<h2>�y�z�C��</h2>
<dl class='dl-horizontal'> 
  <dt>Drupal</dt>
  <dd>�j�j���F����CMF</dd>
  <dt>Joomla</dt>
  <dd>²����Ϊ�CMS</dd>
  <dt>Wordpress</dt>
  <dd>�u�������e�o�G����</dd>
</dl>  
```