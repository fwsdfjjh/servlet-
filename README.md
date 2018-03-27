servlet遇到的代码记录：
一：.jsp
(一)普通表格输入
     <tr>
         <td class="lalel">用户名：</td>
         <td class="controler"><input type="text" name="username" /></td>
     </tr>
1.前一个选项class="lable"
2.input标签内的type="text"意思是按输入框
3.input 里的name的属性值在写对应的.java文件时会用到

（二）密码的输入
     <tr>
	 <td class="label">密码：</td>
         <td class="controler"><input type="password" name="mypassword" ></td>
     </tr>
1. 与一.（一）不同的是type属性值是password

(三)选项按钮的实现
     <tr>
         <td class="label">性别：</td>
	 <td class="controler"><input type="radio" name="gender" checked="checked" value="Male">男<input type="radio" name="gender" value="Female">女</td>
     </tr>
 1.type="radio"是选项按钮的实现
 2.checked="checked" value="Male"
 
（四）日期
     <tr>
	  <td class="label">出生日期：</td>
	  <td class="controler"><input name="birthday" type="text" id="control_date" size="10"
                                maxlength="10" onclick="new Calendar().show(this);" readonly="readonly" />
	  </td>
	  </tr>



