#5.�{���X�϶�

@(104-1.�����{���]�p)[bootstrap]

###��l�d�Ҧp�U:

```html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>�N�X</title>
<link href="../bootstrap/css/bootstrap.css" rel="stylesheet">


<!--[if lt IE 9]>
      <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
</head>

<body>
<div class="container">
  <h1 class="page-header">�{���X<small> &lt;code&gt; �P &lt;pre&gt; ���Ҫ��ϥ�</small></h1>
  
  <p>��<h1>���ҲK�[�@��.page-header�A�i�H�����e�K�[�X�A����Z�A�åB�b�U����ܤ@���Ǧ⪺��u�C</p>  
  
</div>

<!--
<div class="container">
  <div class="row">
    <div class="span8"> ... </div>
    <div class="span4"> ... </div>
  </div>
</div>
-->

  
  <script src="../bootstrap/js/jquery-1.7.2.min.js"></script> 
  <script src="../bootstrap/js/bootstrap.js"></script>
</p> 

</body>
</html>
```

###�S��Ÿ��ഫ

�b�U���o�q�d�Ҥ�,�ڭ̷Q�N`<h1>`�����e��ܥX��,�ѩ�o�r�ꤤ�t���Phtml��ñ�ۦP���Ÿ�,�]���|��ܤ��X��

```html
<p>��<h1>���ҲK�[�@��.page-header�A�i�H�����e�K�[�X�A����Z�A�åB�b�U����ܤ@���Ǧ⪺��u�C</p>  
```

�]���ڭ̥����N�o�����Ÿ������ഫ,�o�٤���:html encode,�H�U�C��O�`�Ϊ��ഫ�r��

�r�� |�ഫ�X     |�r�� |�ഫ�X     
----|----------|-----|-----
`<` | `&lt;`   |`�ť�`| `&nbsp;`
`>` | `&gt;`   |`"`  | `&quot;`
`&` | `&amp;`  |     |

�]��,�ഫ�᪺���G�p�U:
```html
<p>��&lt;h1&gt;���ҲK�[�@��.page-header�A�i�H�����e�K�[�X�A����Z�A�åB�b�U����ܤ@���Ǧ⪺��u�C</p>  
```

###�{���X���q`<code>`
�Y�ڭ̭n�A�j��`<h1>`�O�{���X���q,�i�H�[�J`<code>`��ñ

```html
<p>��<code>&lt;h1&gt;</code>���ҲK�[�@��<code>.page-header</code>�A�i�H�����e�K�[�X�A����Z�A�åB�b�U����ܤ@���Ǧ⪺��u�C</p>  
```

###��q��X`<pre>`
�ѩ�bhtml�̷|������ťդδ��浥�ƦC,�p�G�Q�n���㪺��X�@�q���e�ëO�d��ƦC,�Y�i�H��`<pre>` (�`�N,�Y�ϥ�`<pre>`�䤺�e�٬O�n����X)

```html
<pre>
&lt;div class=&quot;container&quot;&gt;
  &lt;div class=&quot;row&quot;&gt;
    &lt;div class=&quot;span8&quot;&gt; ... &lt;/div&gt;
    &lt;div class=&quot;span4&quot;&gt; ... &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>
```
�Y�O�n�j�յ{���X�˦�,�i�H�t�X`<code>`

```html
<pre><code>
&lt;div class=&quot;container&quot;&gt;
  &lt;div class=&quot;row&quot;&gt;
    &lt;div class=&quot;span8&quot;&gt; ... &lt;/div&gt;
    &lt;div class=&quot;span4&quot;&gt; ... &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>
```

###�[�j���Ƶ{���X�϶�(�Dbootstrap���\��)

google���ѤF�@�M�{���w,�٤���[Javascript code prettifier](https://github.com/google/code-prettify), �u�n�N�o�M�{���w�ޤJ,�Y�i���{���X�϶�����[! �[�J�{���w���覡�p�U:

```html
<script src="https://cdn.rawgit.com/google/code-prettify/master/loader/run_prettify.js"></script>
```

�P��,�b`<pre>`���[�J`prettyprint`class,�Y�i�[�H����! �t�~,�٥i�H�A�[�J`linenums`�Ϩ���ܦ渹!

```html
<pre class="prettyprint linenums">
&lt;div class=&quot;container&quot;&gt;
  &lt;div class=&quot;row&quot;&gt;
    &lt;div class=&quot;span8&quot;&gt; ... &lt;/div&gt;
    &lt;div class=&quot;span4&quot;&gt; ... &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>
```