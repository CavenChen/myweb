#9.�ɯ���

@(104-1.�����{���]�p)[bootstrap]

###��l�d�Ҧp�U:

```html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>�ɯ�</title>
<link href="../bootstrap/css/bootstrap.css" rel="stylesheet">

<!--[if lt IE 9]>
      <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
</head>
<body>
<div class="container">
  <h1 class="page-header">�ɯ�</h1>
</div>
<script src="../bootstrap/js/jquery-1.7.2.min.js"></script> 
<script src="../bootstrap/js/bootstrap.js"></script>
</body>
</html>
```

###�ɯ��檺�]�w

�ɯ���@��O�@�Ӻ������̥D�n����涵��,�|�m��b�W��,�H�U�O�@�Ӿɯ��檺�򥻳]�w

```html
<div class="navbar">				(1)
  	<div class="navbar-inner">		(1)
    	<div class="container">		(2)
			<ul class="nav">		(3)
				<li class="active"><a href="#">����</a></li>		(4)
				<li><a href="#">���ؤ@</a></li>
				<li><a href="#">���ؤG</a></li>
			</ul>
        </div>
    </div>
</div>
```

1. �]�ФG�h`<div>`,�~�h�ŧi�@�Ӿɯ���D��,�ĤG�h�ŧi�ɯ�������e
2. ���̪����إ��Τ@�h`<div>`�[`container`class�]��
3. ���ؤ��e�̵M�O�H`<ul>`+`<li>`
4. �i�H�[�J�@��`active`��class,�Ϩ䶵�ط|�[�`,��ܬO�ثe���Τ����ﶵ

---

�ɯ��椤,�i�H�]�w�h�ժ����ؤ��e

```html
<div class="navbar">				
  	<div class="navbar-inner">		
    	<div class="container">		
			<ul class="nav">		
				<li class="active"><a href="#">����</a></li>		
				<li><a href="#">���ؤ@</a></li>
				<li><a href="#">���ؤG</a></li>
			</ul>
			<ul class="nav pull-right">		(1)
				<li><a href="#">�n�J</a></li>		
				<li class='divider-vertical'></li>  (2)
				<li><a href="#">���U</a></li>
			</ul>
        </div>
    </div>
</div>
```
1. �ĤG�վɯ�ﶵ,�åB�[�J`pull-right`class�Ϩ�a�V���
2. �o�O�@���������j�u

---

�ɯ�����٥i�A�[�J�@�ǳ]�w,�p�U

```html
<div class="navbar navbar-fixed-top">	(1)
  	<div class="navbar-inner">
    	<div class="container">
        <a class="brand" href="#">Bootstrap</a>   (2)
        <ul class="nav">
        	<li class="active"><a href="#">����</a></li>
            <li><a href="#">���ؤ@</a></li>
            <li><a href="#">���ؤG</a></li>
        </ul>
        <form class="navbar-search">	(3)
        	<input type="text" class="search-query">
        </form>
        <ul class="nav pull-right">
        	<li><a href="#">�n��</a></li>
            <li class="divider-vertical"></li>
            <li><a href="#">���U</a></li>
        </ul>
        </div>
    </div>  
</div>
```

1. �p�G�n�N�ɯ���T�w�b�̤W��(���|�]�������V�U�n�ʦӮ���),�i�H�[�J`navbar-fixed-top`class
2. �Q��`brand`class�Ӫ�ܤ@�Ӻ����Х�(�~�P)
3. �Q��`<form>`��`navbar-search`class�ӥ[�J�@�Ӭd�߿�J�ت��\��


###�t�X�T���������]�p


```html
<div class="navbar">	
  	<div class="navbar-inner">
    	<div class="container">
			<a href="#" class="btn btn-navbar" data-toggle="collapse"   
			   data-target=".nav-collapse">		(1)
				<span class="icon-bar"></span>  (2)
				<span class="icon-bar"></span>
				<span class="icon-bar"></span>
			</a>
			<a class="brand" href="#">Bootstrap</a>   
			<div class="nav-collapse">			(3)
				<ul class="nav">
					<li class="active"><a href="#">����</a></li>
					<li><a href="#">���ؤ@</a></li>
					<li><a href="#">���ؤG</a></li>
				</ul>
				<form class="navbar-search">	
					<input type="text" class="search-query">
				</form>
				<ul class="nav pull-right">
					<li><a href="#">�n��</a></li>
					<li class="divider-vertical"></li>
					<li><a href="#">���U</a></li>
				</ul>
			</div>
		</div>
    </div>  
</div>
```

1. �o�q`<a>`��ñ��,�D�n�O���o�ɯ���b�e���e�׹L�p��,�i�H�X�{�@�ӤU�ԫ���,����ܾɯ��檺����,�P�ɭn�Q��`data-target`���]�w,�ѦҨ�`nav-collapse`class��`<div>`��ñ�W!(3)
2. �o�T��`<span>`���@�άO��ܤT���u
3. �o��`<div>`�ҥ]�Ъ����e,�|�b�e���ܤp�����ð_��,�æb�ɯ����(1)���U��,��ܥX��