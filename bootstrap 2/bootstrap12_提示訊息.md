#11.�ɯ���|(breadcrumb)�Τ�����

@(104-1.�����{���]�p)[bootstrap]

###��l�d�Ҧp�U:

```html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>���ܸ�T</title>
<link href="../bootstrap/css/bootstrap.css" rel="stylesheet">

<!--[if lt IE 9]>
      <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
</head>

<body>
<div class="container">
  <h1 class="page-header">���ܸ�T</h1>
  <h4>����</h4>
  Lorem ipsum dolor sit amet,  consectetur adipiscing elit. Nulla nibh est, sagittis sit amet consectetur a, rhoncus dignissim ligula.
</div>
<script src="../bootstrap/js/jquery-1.7.2.min.js"></script> 
<script src="../bootstrap/js/bootstrap.js"></script>
</body>
</html>

```

###���ܸ�T���]�w

���ܸ�T�@��O�H�����ت���r�Ω���,�Ӵ����ϥΪ̪`�N�ƶ�!�]�w��²��,�Ȼݥ[�W`<div>`�]��,�å[�J`alert alert-block`class�Y�����ĪG!


```html
<div class="alert alert-block">
  <h1 class="page-header">���ܸ�T</h1>
  <h4>����</h4>
  Lorem ipsum dolor sit amet,  consectetur adipiscing elit. Nulla nibh est, sagittis sit amet consectetur a, rhoncus dignissim ligula.
</div>
```

�o�̨ϥΪ�`alert-block`�u�O�䤤�@��,�٥i�H�ϥΥH�Uclass
- `alert-error`
- `alert-success`
- `alert-info`

---

###�i���������ܰT��
���ܰT���Y�n�i����,���ݥ[�J�@������������,��M,�o�\��]�O�n�ޤJjquery.js��bootstrap.js���{�w

```html
<div class="alert alert-block">
  <a href="#" class="close" data-dismiss="alert">x</a>    (1)
  <h1 class="page-header">���ܸ�T</h1>
  <h4>����</h4>
  Lorem ipsum dolor sit amet,  consectetur adipiscing elit. Nulla nibh est, sagittis sit amet consectetur a, rhoncus dignissim ligula.
</div>
```

1. ��������n�[�J`close`class��`data-dismiss="alert"`���ݩʧY�i!