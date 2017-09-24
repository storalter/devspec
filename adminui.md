###tab标签
```
<div class="tab">
    <ul class="fn-clear">
        <li class="current">
            <a href="#">Tab标题1</a>
        </li>
        <li>
            <a href="#">Tab标题2</a>
        </li>
        <li>
            <a href="#">Tab标题3</a>
        </li>
    </ul>
</div>
```
###下拉框
```
<div class="select">
    <div class="select-value">
        <span data-value="1">选择／修改</span>
        <em>
            <i></i>
        </em>
    </div>
    <div class="select-list fn-hide">
        <ul>
            <li><a data-value="1" href="#">大众1</a></li>
            <li><a data-value="2" href="#">大众2</a></li>
            <li><a data-value="3" href="#">大众3</a></li>
            <li><a data-value="4" href="#">大众4</a></li>
            <li><a data-value="5" href="#">大众5</a></li>
        </ul>
    </div>
</div>
//js初始化
<script src="js/common.js"></script>
<script>
    //初始化下拉框
    $(".select").select();
</script>
```
###复选框
```
<label class="checkbox"><i></i><span>未选中</span></label>
<label class="checkbox checked"><i></i><span>选中</span></label>
<label class="checkbox disabled"><i></i><span>禁用</span></label>
<label class="checkbox checked disabled"><i></i><span>禁用</span></label>
如果是一组复选框，外面套一层<div class="group">给彼此增加间距
```
###单选框
```
<label class="radio" data-group="xx" data-value="1"><i></i><span>未选中</span></label>
<label data-group="xx" class="radio checked" data-value="2"><i></i><span>选中</span></label>
<label class="radio disabled" data-group="xx" data-value="1"><i></i><span>禁用</span></label>
<label data-group="xx" class="radio checked disabled" data-value="2"><i></i><span>禁用</span></label>
如果是一组单选框，外面套一层<div class="group">给彼此增加间距
```
###按钮
```
<a href="#" class="btn btn-blue">蓝色按钮</a>
<a href="#" class="btn btn-red">红色按钮</a>
<a href="#" class="btn btn-red btn-big">页面底部的大按钮</a>
```
###主标题
```
<h2 class="title">字体最大的标题字</h2>
```
### 子标题
```
<h3 class="subtitle">副标题字体字号</h3>
```
###表单结构和文本框
```
<div class="form">
    <dl>
        <dt>选择厂商
        </dt>
        <dd>
            <input type="text" placeholder="水印" /><span class="error">＊商品来源：对于经销商发布的商品，新增一个商品来源，开放平台。不给经销商展示，系统写死。</span>
        </dd>
    </dl>
    <dl>
        <dt>覆盖城市
        </dt>
        <dd>
            <input class="error" type="text" value="＊输入框错误提示" /><span class="error">＊商品来源：对于经销商发布的商品，新增一个商品来源，开放平台。不给经销商展示，系统写死。</span>
        </dd>
    </dl>
    <dl>
        <dt>公司紧急<br />
            联系人手机
        </dt>
        <dd>
            <input type="text" value="禁用" disabled="disabled" />
        </dd>
    </dl>
</div>
```

###页面顶部的提示
```
<div class="infomation">
    商家信息已于 2016年03月07日 11:11 进行修改，目前的状态为：<span class="fn-white">待审核。</span>
</div>
```
###列表，包含了列表标题，筛选区和分页
```
 <div class="grid">
    <div class="grid-header">
        副标题字体字号
    </div>
    <div class="grid-condition">
        <div class="grid-condition-content fn-clear">
            <dl>
                <dt>文字信息：
                </dt>
                <dd>
                    <div class="select" style="width: 150px;">
                        <div class="select-value">
                            <span data-value="1">下拉菜单</span>
                            <em>
                                <i></i>
                            </em>
                        </div>
                        <div class="select-list fn-hide">
                            <ul>
                                <li><a data-value="1" href="#">大众1</a></li>
                                <li><a data-value="2" href="#">大众2</a></li>
                                <li><a data-value="3" href="#">大众3</a></li>
                                <li><a data-value="4" href="#">大众4</a></li>
                                <li><a data-value="5" href="#">大众5</a></li>
                            </ul>
                        </div>
                    </div>
                </dd>
            </dl>
            <dl>
                <dt>文字信息：
                </dt>
                <dd>
                    <div class="select" style="width: 150px;">
                        <div class="select-value">
                            <span data-value="1">下拉菜单</span>
                            <em>
                                <i></i>
                            </em>
                        </div>
                        <div class="select-list fn-hide">
                            <ul>
                                <li><a data-value="1" href="#">大众1</a></li>
                                <li><a data-value="2" href="#">大众2</a></li>
                                <li><a data-value="3" href="#">大众3</a></li>
                                <li><a data-value="4" href="#">大众4</a></li>
                                <li><a data-value="5" href="#">大众5</a></li>
                            </ul>
                        </div>
                    </div>
                </dd>
            </dl>
            <dl>
                <dt>文字信息：
                </dt>
                <dd>
                    <input type="text" style="width: 150px;" />
                </dd>
                <dt>文字信息：
                </dt>
                <dd>
                    <div class="select" style="width: 150px;">
                        <div class="select-value">
                            <span data-value="1">下拉菜单</span>
                            <em>
                                <i></i>
                            </em>
                        </div>
                        <div class="select-list fn-hide">
                            <ul>
                                <li><a data-value="1" href="#">大众1</a></li>
                                <li><a data-value="2" href="#">大众2</a></li>
                                <li><a data-value="3" href="#">大众3</a></li>
                                <li><a data-value="4" href="#">大众4</a></li>
                                <li><a data-value="5" href="#">大众5</a></li>
                            </ul>
                        </div>
                    </div>
                </dd>
            </dl>

            <dl>
                <dt>文字信息：
                </dt>
                <dd>
                    <input type="text" style="width: 150px;" /><span class="form-seperator">至</span><input type="text" style="width: 150px;" />
                </dd>
            </dl>
            <dl>
                <dt>裸车实际降价：
                </dt>
                <dd>
                    <input type="text" style="width: 50px;" /><span class="form-unit">元</span>
                </dd>
            </dl>
            <dl>
                <dd>
                    <div class="group">
                        <label class="radio" data-group="xx" data-value="1"><i></i><span>审核通过</span></label><label data-group="xx" class="radio checked" data-value="2"><i></i><span>审核不通过</span></label>
                    </div>
                </dd>
            </dl>
        </div>

        <div class="grid-condition-btn">
            <a href="#" class="btn btn-blue">查询</a><a href="#" class="btn btn-red">重置</a>
        </div>
    </div>
    <table class="grid-table">
        <tr>
            <th style="width: 60px;">复选框
            </th>
            <th style="width: 120px;">标题
            </th>
            <th style="width: 120px;">标题
            </th>
            <th>标题
            </th>
        </tr>
        <tr>
            <td>
                <label class="checkbox"><i></i></label>
            </td>
            <td>内容
            </td>
            <td>内容
            </td>
            <td>内容
            </td>
        </tr>
        <tr>
            <td>
                <label class="checkbox"><i></i></label>
            </td>
            <td>内容
            </td>
            <td>内容
            </td>
            <td>内容
            </td>
        </tr>
    </table>
    <div class="pager">
        <a class="pager-last disabled"><i></i></a><span class="pager-pageindex"><a href="#" class="current">1</a><a href="#">2</a><span class="pager-dot">...</span><a href="#">3</a><a href="#">4</a><a href="#">5</a></span><a href="#" class="pager-next"><i></i></a><input class="pager-number" type="text" /><span class="pager-label">共 30 页</span>
    </div>
</div>

```
###栅格系统
对于多列布局，可以使用栅格系统，省得再写类。
行row，列column，列宽从column-1到column-20
```
<div class="row">
    <div class="column column-3">
        <a href="#" class="btn btn-blue">查询</a>
    </div>
    <div class="column column-3">
        <a href="#" class="btn btn-red">重置</a>
    </div>
</div>
```
###工具类
相对于普通页面，后台系统页面提供大量的工具类方便开发人员自由组合页面，而不需要前端深度参与
```
.fn-red{
    color: #ff2600;
}

.fn-mb10{
    margin-bottom: 10px;
}

.fn-mb20{
    margin-bottom: 20px;
}

.fn-mb30{
    margin-bottom: 30px;
}

.fn-mr10{
    margin-right: 10px;
}

.fn-tal{
    text-align: left;
}

.fn-tac{
    text-align: center;
}

.fn-white{
    color: #fff;
}

.box{
    padding:0 20px;
}
```

###内联样式
对于文本框及列表列宽等随时变化的的样式，直接写内联样式
```
<tr>
    <th style="width: 60px;">复选框
    </th>
    <th style="width: 120px;">标题
    </th>
    <th style="width: 120px;">标题
    </th>
    <th>标题
    </th>
</tr>
```

###其它
box类会给左右2opx的边距
```
.box{
    padding:0 20px;
}
```
