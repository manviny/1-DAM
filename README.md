# 1-DAM

## Lenguajes de marcas

```html
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<style type="text/css">
		#caja1{
			width: 60px;
			height: 60px;
			background-color: #FCC;
			position: relative;  /*deja espacio en blanco en su sitio*/
			position: absolute;  /*NO deja espacio en su ueco, se posiciona con el ancestro mas cercano que este posicionado*/
			position: fixed;  /*relativo al viewport*/
			left: 100px;
			top:50px;
		}
		#caja2{
			width: 60px;
			height: 60px;
			background-color: #CFC;
		}
		#caja3{
			width: 60px;
			height: 60px;
			background-color: #CCF;
		}
	</style>
</head>
<body>

	<div id="caja1">box 1</div>
	<div id="caja2">box 2</div>
	<div id="caja3">box 3</div>

</body>
</html>
```
