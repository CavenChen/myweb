#7.���

@(104-1.�����{���]�p)[bootstrap]

###��l�d�Ҧp�U:

```html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>���</title>
<link href="../bootstrap/css/bootstrap.css" rel="stylesheet">
<!--[if lt IE 9]>
      <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
</head>

<body>
<div class="container">
  <h1 class="page-header">���</h1>

         
</div>
<script src="../bootstrap/js/jquery-1.7.2.min.js"></script> 
<script src="../bootstrap/js/bootstrap.js"></script>
</body>
</html>

```

###��檺�@�ǲե�

`<input>`�i�H�Ψӳ]�w�U�ث�������J���,���O��r�榡,����,���,�h��...��
�H�U�O�@�ӥi�H��J��r��쪺�Ҥl

```html
<input type='text'>
```
[�o��](http://www.w3schools.com/html/html_form_input_types.asp)�i�H�ѦҩҦ���input type!


###�e��P���
�b��J��쪺�e���[�J�@�ӫe?�Ϋ��Ÿ�,�Ҧp�e���O`$`�Ÿ�,�᭱�O`.00`

```html
<!-- �e�� -->
<div class='input-prepend'>  <!-- ��div�[�Winput-prepend class�]�� -->
	<span class='add-on'>$</span>
	<input type='text'></input>
</div>
<!-- ��� -->
<div class='input-append'>   <!-- ��div�[�Winput-append class�]�� -->
	<input type='text'></input>
	<span class='add-on'>.00</span>
</div>

<!-- �V�X -->
<div class='input-prepend input-append'>
	<span class='add-on'>$</span>
	<input type='text'></input>
	<span class='add-on'>.00</span>
</div>

```

�]�i�H�N���a�P��J��쵲�X
```html
<div class='input-append'>   <!-- ��div�[�Winput-append class�]�� -->
	<input type='text'></input>
	<button class="btn" type="button">�d��</button>
</div>

```

###������

`input type`�]��`radio`��,�|�N�o����ܬ��@�ӳ�諸���A���,�i�H�t�X`name`�ݩʫ��w�o�ӿﶵ���W��,��`value`�ݩʪ�ܷ�襤������ҥN���Ȭ���
�Ӧb�~�h,�i�H��`<label>` ��ñ�]��,�P�ɵ��@����ܦb�e���W���ﶵ����
```html
<label class='radio'>
<input type='radio' name='gender' value='male'>�k</label>
```

`radio`���ﶵ�S��,�O�b�h�ӿﶵ����ܨ䤤�@��,�]���ڭ̥i�H�h�[�@�ǿﶵ,�䤤�ۦP`name`�ݩʭ�,�i�H�M�w�L�̬O�P�@�Ӹs��

```html
<label>�z���ʧO</label>
<label class='radio'>
<input type='radio' name='gender' value='male'>�k</label>
<label class='radio'>
<input type='radio' name='gender' value='female'>�k</label>
<label class='radio'>
<input type='radio' name='gender' value='other'>��L</label>
```

###�ƿ����

`input type`�]��`checkbox`��,�|�N�o����ܬ��@�ӽƿ諸���A���,�i�H�t�X`name`�ݩʫ��w�o�ӿﶵ���W��,��`value`�ݩʪ�ܷ�襤������ҥN���Ȭ���
�Ӧb�~�h,�i�H��`<label>` ��ñ�]��,�P�ɵ��@����ܦb�e���W���ﶵ����
```html
<label class='checkbox'>
<input type='checkbox' name='cms' value='wordpress'>WordPress</label>
```

`checkbox`���ﶵ�S��,�O�b�h�ӿﶵ����ܤ@���Φh��,�]���ڭ̥i�H�h�[�@�ǿﶵ,�䤤�ۦP`name`�ݩʭ�,�i�H�M�w�L�̬O�P�@�Ӹs��

```html
<label>�A���w��CMS</label>
<label class='checkbox'>
<input type='checkbox' name='cms' value='wordpress'>WordPress</label>
<label class='checkbox'>
<input type='checkbox' name='cms' value='durpal'>Durpal</label>
<label class='checkbox'>
<input type='checkbox' name='cms' value='joomla'>Joomla</label>
```

�p�G�Q�n�䤤���ﶵ�O�H�����覡�ƦC,�i�H�b`label`���[�J`inline`class

```html
<label>�A���w��CMS</label>
<label class='checkbox inline'>
<input type='checkbox' name='cms' value='wordpress'>WordPress</label>
<label class='checkbox inline'>
<input type='checkbox' name='cms' value='durpal'>Durpal</label>
<label class='checkbox inline'>
<input type='checkbox' name='cms' value='joomla'>Joomla</label>
```

###��ܦC��

��ܦC���\��P�e�z�����νƿ����ۦP,�u���L�b�e���W�O�H�C���覡�i��,�B�b�y�k�W�]�j���ۦP!
��ܦC��n�H`<select>`�]�Ф@��`<option>`�����ؤ��e

```html
<label for='somewhere'>�Q�h���a��</label>
<select id='somewhere'>
	<option value='Italy'>�N�j�Q</option>
	<option value='US'>����</option>
	<option value='UK'>�^��</option>
</select>
```

�Y�O�n�i�H�ƿ�,�u�n�b`<select>`�[�J`multiple='multiple'`�ݩʧY�i

```html
<label for='somewhere'>�Q�h���a��</label>
<select id='somewhere' multiple='multiple'>
	<option value='Italy'>�N�j�Q</option>
	<option value='US'>����</option>
	<option value='UK'>�^��</option>
</select>
```

**��:�o�ؽƿ說�C����֨ϥ�,�]���ϥΪ̦b�h��ɥ��ݰt�X���U`CTRL`�άO`SHIFT`��h�I��,���F���h�諸�ĪG,�ϥΤW������ı!�Y�O�S���A������,�ϥΪ̤]�����o�|���D�p��ϥ�!**


###��檺�ƪ�

��l���d�Ҧp�U
```html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>���</title>
<link href="../bootstrap/css/bootstrap.css" rel="stylesheet">
<!--[if lt IE 9]>
      <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
</head>

<body>
<div class="container">
  <h1 class="page-header">���</h1>
  
  <label for="username">�Τ�W</label>
  <input id="username" type="text">
  <p class="help-block">�п�J�z�Q�n���U���Τ�W</p>
  
  <label for="password">�K�X</label>
  <input id="password" type="password">
  <p class="help-block">�п�J�]�m���K�X</p>
  
  <button type="submit" class="btn btn-primary">�n��</button>
  </form>
</div>
<script src="../bootstrap/js/jquery-1.7.2.min.js"></script> 
<script src="../bootstrap/js/bootstrap.js"></script>
</body>
</html>

```


bootstrap�w��@�ӧ��㪺���,�Ҵ��Ѫ����Ʀp�U

```html
<form class="form-horizontal">	(1)
<fieldset>						(2)
  <legend>�Τ�n��</legend>		(3)
  <div class="control-group">	(4)
	<label class="control-label" for="username">�Τ�W</label>  (4)
	<div class="controls">		(4)
	  <input id="username" type="text">
	  <p class="help-block">�п�J�z�Q�n���U���Τ�W</p>
	</div>
  </div>
  <div class="control-group">
	<label class="control-label" for="password">�K�X</label>
	<div class="controls">
	  <input id="password" type="password">
	  <p class="help-block">�п�J�]�m���K�X</p>
	</div>
  </div>
</fieldset>
<div class="form-actions">		(5)
  <button type="submit" class="btn btn-primary">�n��</button>
</div>
</form>

```

1. �@����檺�̥~�h���ݥH`<form>`�]��, �å[�J`form-horizontal`class
2.  `<fieldset>`�i�N�����s��
3.  `<legend>`�i�]�w���s�ժ��W��
4.  �o�T�Ӧa�誺�]�w,�i�H�N`<label>`����찵����ΦP��ƦC
5.  ������䪺�����i��`<div>`�]��,�å[�J`form-actions`class,���ƨ�ĪG