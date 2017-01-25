# inertia
移动设备上任意元素在屏幕内惯性弹动

原生JavaScript编写，适用于触屏设备。

## 使用示意
①. 引入JS文件，例如

``` html
<script src="Inertia.js"></script>
```

②. 绑定

``` javascript
new Inertia(ele);
```

## 语法
``` javascript
new Inertia(ele, option);
```

其中：
<ul>
	<li><code>ele</code>表示拖移弹动的元素；</li>
	<li><code>option</code>为可选参数，包括：
		<ul>
			<li><code>edge</code>，布尔值，表示是否吸附边缘，默认为<code>true</code>，也就是吸附。</li>
		</ul>
	</li>
</ul>

## 补充说明
有时候希望元素不是紧靠边缘而是留有间隙，可以使用透明边框，或者标签嵌套使用padding等CSS属性控制。