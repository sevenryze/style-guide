# Table of Content

- [Table of Content](#table-of-content)
- [Convention](#convention)
- [Rules](#rules)
    - [Form](#form)

# Convention

1.  We will use code quality checker to ensure these rules soon or later.

# Rules

## Form

[`react`参考](https://reactjs.org/docs/forms.html)
[`MDN`参考](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Your_first_HTML_form)

1.  在`react`中, 使用`HtmlFor`代替`<label>`中的`for`属性.
2.  使用`<button type="submit">`代替`<input type="submit">`. 因为`input`只接受文本内容, 而`button`可以接受任何形式的内容. 这对创建富有表现力的提交按钮非常有帮助.
3.  在`react`中, `<textarea>`使用`value`属性来代替 childrens 做为内容.
4.  使用`<label for="">`代替嵌套`<input>`到`<label>`之中的方法. 因为这种形式对有障碍者友好, 可以帮助他们读出内容关系.
