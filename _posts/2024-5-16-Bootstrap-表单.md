---
layout: post
author: CaoShiba
---
#示例1
<form role="form">
  <div class="form-group">
    <label for="name">名称</label>
    <input type="text" class="form-control" id="name" placeholder="请输入名称">
  </div>
  <div class="form-group">
    <label for="inputfile">文件输入</label>
    <input type="file" id="inputfile">
    <p class="help-block">这里是块级帮助文本的实例。</p>
  </div>
  <div class="checkbox">
    <label>
      <input type="checkbox">请打勾
    </label>
  </div>
  <button type="submit" class="btn btn-default">提交</button>
</form>

#示例2
<form class="form-inline" role="form">
  <div class="form-group">
    <label class="sr-only" for="name">名称</label>
    <input type="text" class="form-control" id="name" placeholder="请输入名称">
  </div>
  <div class="form-group">
    <label class="sr-only" for="inputfile">文件输入</label>
    <input type="file" id="inputfile">
  </div>
  <div class="checkbox">
    <label>
      <input type="checkbox">请打勾
    </label>
  </div>
  <button type="submit" class="btn btn-default">提交</button>
</form>

#示例3
<form class="form-horizontal" role="form">
  <div class="form-group">
    <label for="firstname" class="col-sm-2 control-label">名字</label>
    <div class="col-sm-10">
      <input type="text" class="form-control" id="firstname" placeholder="请输入名字">
    </div>
  </div>
  <div class="form-group">
    <label for="lastname" class="col-sm-2 control-label">姓</label>
    <div class="col-sm-10">
      <input type="text" class="form-control" id="lastname" placeholder="请输入姓">
    </div>
  </div>
  <div class="form-group">
    <div class="col-sm-offset-2 col-sm-10">
      <div class="checkbox">
        <label>
          <input type="checkbox">请记住我
        </label>
      </div>
    </div>
  </div>
  <div class="form-group">
    <div class="col-sm-offset-2 col-sm-10">
      <button type="submit" class="btn btn-default">登录</button>
    </div>
  </div>
</form>

#示例4
<form role="form">
  <div class="form-group">
    <label for="name">标签</label>
    <input type="text" class="form-control" placeholder="文本输入">
  </div>
 </form>

 #示例5
 <form role="form">
  <div class="form-group">
    <label for="name">文本框</label>
    <textarea class="form-control" rows="3"></textarea>
  </div>
</form>

#示例6
<label for="name">默认的复选框和单选按钮的实例</label>
<div class="checkbox">
    <label><input type="checkbox" value="">选项 1</label>
</div>
<div class="checkbox">
    <label><input type="checkbox" value="">选项 2</label>
</div>
<div class="radio">
    <label>
        <input type="radio" name="optionsRadios" id="optionsRadios1" value="option1" checked> 选项 1
    </label>
</div>
<div class="radio">
    <label>
        <input type="radio" name="optionsRadios" id="optionsRadios2" value="option2">选项 2 - 选择它将会取消选择选项 1
    </label>
</div>
<label for="name">内联的复选框和单选按钮的实例</label>
<div>
    <label class="checkbox-inline">
        <input type="checkbox" id="inlineCheckbox1" value="option1"> 选项 1
    </label>
    <label class="checkbox-inline">
        <input type="checkbox" id="inlineCheckbox2" value="option2"> 选项 2
    </label>
    <label class="checkbox-inline">
        <input type="checkbox" id="inlineCheckbox3" value="option3"> 选项 3
    </label>
    <label class="radio-inline">
        <input type="radio" name="optionsRadiosinline" id="optionsRadios3" value="option1" checked> 选项 1
    </label>
    <label class="radio-inline">
        <input type="radio" name="optionsRadiosinline" id="optionsRadios4"  value="option2"> 选项 2
    </label>
</div>

#示例7
<form role="form">
  <div class="form-group">
    <label for="name">选择列表</label>
    <select class="form-control">
      <option>1</option>
      <option>2</option>
      <option>3</option>
      <option>4</option>
      <option>5</option>
    </select>
    <label for="name">可多选的选择列表</label>
    <select multiple class="form-control">
      <option>1</option>
      <option>2</option>
      <option>3</option>
      <option>4</option>
      <option>5</option>
    </select>
  </div>
</form>

#示例8
<form class="form-horizontal" role="form">
  <div class="form-group">
    <label class="col-sm-2 control-label">Email</label>
    <div class="col-sm-10">
      <p class="form-control-static">email@example.com</p>
    </div>
  </div>
  <div class="form-group">
    <label for="inputPassword" class="col-sm-2 control-label">密码</label>
    <div class="col-sm-10">
      <input type="password" class="form-control" id="inputPassword" placeholder="请输入密码">
    </div>
  </div>
</form>

#示例9
<form class="form-horizontal" role="form">
  <div class="form-group">
    <label class="col-sm-2 control-label">聚焦</label>
    <div class="col-sm-10">
      <input class="form-control" id="focusedInput" type="text" value="该输入框获得焦点...">
    </div>
  </div>
  <div class="form-group">
    <label for="inputPassword" class="col-sm-2 control-label">禁用</label>
    <div class="col-sm-10">
      <input class="form-control" id="disabledInput" type="text" placeholder="该输入框禁止输入..." disabled>
    </div>
  </div>
  <fieldset disabled>
    <div class="form-group">
      <label for="disabledTextInput" class="col-sm-2 control-label">禁用输入（Fieldset disabled）</label>
      <div class="col-sm-10">
        <input type="text" id="disabledTextInput" class="form-control" placeholder="禁止输入">
      </div>
    </div>
    <div class="form-group">
      <label for="disabledSelect" class="col-sm-2 control-label">禁用选择菜单（Fieldset disabled）</label>
      <div class="col-sm-10">
        <select id="disabledSelect" class="form-control">
          <option>禁止选择</option>
        </select>
      </div>
    </div>
  </fieldset>
  <div class="form-group has-success">
    <label class="col-sm-2 control-label" for="inputSuccess">输入成功</label>
    <div class="col-sm-10">
      <input type="text" class="form-control" id="inputSuccess">
    </div>
  </div>
  <div class="form-group has-warning">
    <label class="col-sm-2 control-label" for="inputWarning">输入警告</label>
    <div class="col-sm-10">
      <input type="text" class="form-control" id="inputWarning">
    </div>
  </div>
  <div class="form-group has-error">
    <label class="col-sm-2 control-label" for="inputError">输入错误</label>
    <div class="col-sm-10">
      <input type="text" class="form-control" id="inputError">
    </div>
  </div>
</form>

#示例10
<form role="form">
  <div class="form-group">
    <input class="form-control input-lg" type="text" placeholder=".input-lg">
  </div>
  <div class="form-group">
    <input class="form-control" type="text" placeholder="默认输入">
  </div>
  <div class="form-group">
    <input class="form-control input-sm" type="text" placeholder=".input-sm">
  </div>
  <div class="form-group"></div>
  <div class="form-group">
    <select class="form-control input-lg">
      <option value="">.input-lg</option>
    </select>
  </div>
  <div class="form-group">
    <select class="form-control">
      <option value="">默认选择</option>
    </select>
  </div>
  <div class="form-group">
    <select class="form-control input-sm">
      <option value="">.input-sm</option>
    </select>
  </div>
  <div class="row">
    <div class="col-lg-2">
      <input type="text" class="form-control" placeholder=".col-lg-2">
    </div>
    <div class="col-lg-3">
      <input type="text" class="form-control" placeholder=".col-lg-3">
    </div>
    <div class="col-lg-4">
      <input type="text" class="form-control" placeholder=".col-lg-4">
    </div>
  </div>
</form>

#示例11
<form role="form">
  <span>帮助文本实例</span>
  <input class="form-control" type="text" placeholder="">
  <span class="help-block">一个较长的帮助文本块，超过一行，
  需要扩展到下一行。本实例中的帮助文本总共有两行。</span>
</form>