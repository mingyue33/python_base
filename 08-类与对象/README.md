```
def 函数名():
	xxxx


定义一个类的方式为:

class 类名:
	xxxxx


类名:规则 大驼峰

给一个对象添加属性方法为:
对象名.新的属性名 = 值

获取这个对象的属性，2种方法：
1. 对象.属性
2. 定义一个方法，这个方法中，使用 self.属性

__init__()方法
	1. 是python自动调用的方法，调用的时间为：创建完对象之后，立马自动调用
	2. 不需要开发者调用，即 对象名.__init__()
	3. 这个方法一般情况下会完成一些默认的事情，比如添加一些属性
	4. 
		class Xxxx:
			def __init__(self, new_a, new_b):
				self.a = new_a
				self.b = new_b

		注意：new_a、new_b 是局部变量，并不是对象的属性，如果想在__init__方法中添加属性的话，需要使用类似
		self.属性名 = 值
		的格式，此时self.a = new_a表示的是给对象添加一个属性，这个属性名为a,这个属性的值为局部变量new_a里面的值








```

