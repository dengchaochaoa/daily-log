遇到了一个ng-class中间有“-”符号的问题
根据：
http://www.th7.cn/web/html-css/201505/101340.shtml

文中提到：
<div ng-class="variable == 1 ? 'class1' : (variable == 2 ? 'class2' : (variable ==3 ? 'class3' : 'class4'))"></div>


<label ng-class="item.ys=='text'?'item item-input':(item.ys=='select'?'item item-select':'')" ng-repeat="item in seacher" item="item">
				<span class="input-label">{{item.name}}：</span>
				<span ng-bind-html="Ttext(item)">
					{{item.ysold}}
				</span>
			</label>


angular-material

https://github.com/angular/bower-material


http://www.bootcdn.cn/angular-material/


有关极客学院的维基 中 
有关于 angular-material
http://wiki.jikexueyuan.com/project/material-design/