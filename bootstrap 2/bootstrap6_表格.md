#6.���

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
<h1 class="page-header">��� <small>&lt;table&gt;</small></h1>
<h2>�w�]�����</h2>
 <table>
  <thead>
    <tr>
      <th>#</th>
      <th>�U���q</th>
      <th>�ϮѥX��</th>
      <th>�~���</th>
    </tr>
  </thead>
  <tr>
    <td>Wordpress</td>
    <td>644,880</td>
    <td>83</td>
    <td>26,900</td>
  </tr>
  <tr>
    <td>Joomla</td>
    <td>86,547</td>
    <td>64</td>
    <td>45,600</td>
  </tr>
  <tr>
    <td>Drupal</td>
    <td>22,836</td>
    <td>65</td>
    <td>37,100</td>
  </tr>
</table>

<h2>�������</h2>
 <table>
  <thead>
    <tr>
      <th>#</th>
      <th>�U���q</th>
      <th>�ϮѥX��</th>
      <th>�~���</th>
    </tr>
  </thead>
  <tr>
    <td>Wordpress</td>
    <td>644,880</td>
    <td>83</td>
    <td>26,900</td>
  </tr>
  <tr>
    <td>Joomla</td>
    <td>86,547</td>
    <td>64</td>
    <td>45,600</td>
  </tr>
  <tr>
    <td>Drupal</td>
    <td>22,836</td>
    <td>65</td>
    <td>37,100</td>
  </tr>
</table>

<h2>�a��ت����</h2>
 <table>
  <thead>
    <tr>
      <th>#</th>
      <th>�U���q</th>
      <th>�ϮѥX��</th>
      <th>�~���</th>
    </tr>
  </thead>
  <tr>
    <td>Wordpress</td>
    <td>644,880</td>
    <td>83</td>
    <td>26,900</td>
  </tr>
  <tr>
    <td>Joomla</td>
    <td>86,547</td>
    <td>64</td>
    <td>45,600</td>
  </tr>
  <tr>
    <td>Drupal</td>
    <td>22,836</td>
    <td>65</td>
    <td>37,100</td>
  </tr>
</table>

<h2>���Y���</h2>
 <table>
  <thead>
    <tr>
      <th>#</th>
      <th>�U���q</th>
      <th>�ϮѥX��</th>
      <th>�~���</th>
    </tr>
  </thead>
  <tr>
    <td>Wordpress</td>
    <td>644,880</td>
    <td>83</td>
    <td>26,900</td>
  </tr>
  <tr>
    <td>Joomla</td>
    <td>86,547</td>
    <td>64</td>
    <td>45,600</td>
  </tr>
  <tr>
    <td>Drupal</td>
    <td>22,836</td>
    <td>65</td>
    <td>37,100</td>
  </tr>
</table>
</div>
<script src="../bootstrap/js/jquery-1.7.2.min.js"></script> 
<script src="../bootstrap/js/bootstrap.js"></script>
</body>
</html>
```

###��檺�򥻵��c

�H�U�O�@�ӳ̰򥻪���浲�c

```html
 <table>	<!-- ���̥~�h���ŧi -->
  <thead>   <!-- ���Y������ -->
    <tr>	<!-- �檺�ŧi -->
      <th>...</th>   <!-- ���Y�檺���e -->
      <th>...</th>   
    </tr>
  </thead>
  <tbody>	<!-- ��������,�i�ٲ� -->
    <tr>	<!-- �檺�ŧi -->
      <td>...</td>	<!-- ���檺���e -->
      <td>...</td>
    </tr>
  </tbody>
</table>

```

###bootstrap�w���檺����

���N`<table>`�[�J`table`class,�Y�|�o��@�ӹw�]���ƹL�����

```html
<h2>�w�]�����</h2>
  <table class='table'>
  ...
```

�i�A�[�J`table-striped`,�i�Ϫ�榳�a�������ĪG

```html
<h2>�������</h2>
  <table class='table table-striped'>
  ...
```

�i�[�J`table-bordered`,�Ϫ��a���(�w�]���O�S����ت�!)

```html
<h2>�a��ت����</h2>
  <table class='table table-striped'>
  ...
```

�i�[�J`table-condensed`,�Ϫ�椺�e�ƪ���[��K,�F���Y�p��檺�ĪG!

```html
<h2>���Y���</h2>
  <table class='table table-condensed'>
```

**��:�H�W�Ҧ��ĪG�i�H�@�_�f�t�ϥ�**