###### jQuery的强大之处在于它的轻量级，强大的选择器，出色的DOM操作的封装，可靠的事件处理机制，完善的ajax，并且不污染顶级变量，出色的浏览器兼容性.它最大的优点是链式操作，丰富的插件支持。下面开始我们的知识点的讲解，从浅入深，详细讲解。
- jQuery和DOM对象的转换
- jQuery提供了两种方法将一个jQuery对象转换成DOM对象，即[index]和get(index)。DOM对象转换成jQuery，只需要将$()把DOM对象包装起来，就可以得到一个jQuery对象了。
- jQuery的链式操作过长，对于代码的可读性产生很大的影响。建议：对于同一个对象不超过3个操作的，可以写成一行。如$("li").show().unbind("click")。对于同一个对象的较多的操作，建议每行写一个操作。程序块严格采用缩进风格，保证代码清晰易读，风格一致。
- 因为jQuery存在链式操作，有时候很复杂的问题用一行代码就可以轻松解决，所以必要的注释很重要。有意义的注释，能培养良好的编码习惯和风格，提高开发效率。
- jQuery默认使用$作为自身的快捷方式。在于其他库相撞时，可以调用jQuery.noConflict（）将变量的控制权限交给其他JavaScript库。
- 选择器是jQuery的根基。jQuery中的选择器完全继承了CSS的风格，利用jQuery选择器，可以非常方便的找出特定的DOM元素，然后为他们添加相应的行为。所以学会使用jQuery的选择器是使用它的基础。jQuery的行为规则都必须在获取到元素后才能生效。
- jQuery选择器的写法与CSS选择器的写法十分相似，只不过两者的作用效果不同。CSS的选择器找到元素后是添加样式，而jQuery选择器是找到元素后添加行为。
- 使用jQuery检查某个元素在网页上是否存在时，应该根据获取到元素的长度来判断。






