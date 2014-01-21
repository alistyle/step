# step

---

通用步骤条，有标准和迷你两套样式。支持二到五步。

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/step.css">

### 标准步骤条

````html
<ol class="ali-step ali-step-3">
    <li class="ali-step-start ali-step-done">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="ali-step-number">1</i>
            <span class="ali-step-text">第一步</span>
        </div>
    </li>
    <li class="ali-step-active">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="ali-step-number">2</i>
            <span class="ali-step-text">第二步</span>
        </div>
    </li>
    <li class="ali-step-end">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="iconfont ali-step-number">&#xF029;</i>
            <span class="ali-step-text">第三步第三步</span>
        </div>
    </li>
</ol>
````

### 四部

````html
<ol class="ali-step ali-step-4">
    <li class="ali-step-start ali-step-active">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="ali-step-number">1</i>
            <span class="ali-step-text">第一步</span>
        </div>
    </li>
    <li class="">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="ali-step-number">2</i>
            <span class="ali-step-text">第二步</span>
        </div>
    </li>
    <li class="">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="ali-step-number">3</i>
            <span class="ali-step-text">第三步</span>
        </div>
    </li>
    <li class="ali-step-end">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="iconfont ali-step-number">&#xF029;</i>
            <span class="ali-step-text">第四步</span>
        </div>
    </li>
</ol>
````

### 五部

````html
<ol class="ali-step ali-step-5">
    <li class="ali-step-start ali-step-done">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="ali-step-number">1</i>
            <span class="ali-step-text">第一步</span>
        </div>
    </li>
    <li class="ali-step-done">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="ali-step-number">2</i>
            <span class="ali-step-text">第二步</span>
        </div>
    </li>
    <li class="ali-step-done">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="ali-step-number">3</i>
            <span class="ali-step-text">第三步</span>
        </div>
    </li>
    <li class="ali-step-active">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="ali-step-number">4</i>
            <span class="ali-step-text">第四步</span>
        </div>
    </li>
    <li class="ali-step-end">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="iconfont ali-step-number">&#xF029;</i>
            <span class="ali-step-text">第五步</span>
        </div>
    </li>
</ol>
````

### 二部
````html
<ol class="ali-step ali-step-2">
    <li class="ali-step-start ali-step-active">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="ali-step-number">1</i>
            <span class="ali-step-text">第一步</span>
        </div>
    </li>
    <li class="ali-step-end">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="iconfont ali-step-number">&#xF029;</i>
            <span class="ali-step-text">第二步</span>
        </div>
    </li>
</ol>
````

### 蓝色步骤条
````html
<ol class="ali-step ali-step-blue ali-step-3">
    <li class="ali-step-start ali-step-done">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="ali-step-number">1</i>
            <span class="ali-step-text">第一步</span>
        </div>
    </li>
    <li class="ali-step-active">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="ali-step-number">2</i>
            <span class="ali-step-text">第二步</span>
        </div>
    </li>
    <li class="ali-step-end">
        <div class="ali-step-line">-</div>
        <div class="ali-step-icon">
            <span class="ali-step-bg"></span>
            <i class="iconfont ali-step-number">&#xF029;</i>
            <span class="ali-step-text">第三步第三步</span>
        </div>
    </li>
</ol>
````

### 迷你步骤条
````html
<ol class="ali-ministep">
    <li class="ali-ministep-item">
        <span class="ali-step-bg"></span>
        <i class="ali-ministep-number">1</i>
        <span class="ali-ministep-text">第一步</span>
    </li>
    <li class="ali-ministep-item ali-ministep-active">
        <span class="ali-step-bg"></span>
        <i class="ali-ministep-number">2</i>
        <span class="ali-ministep-text">第二步</span>
    </li>
    <li class="ali-ministep-item">
        <span class="ali-step-bg"></span>
        <i class="ali-ministep-number">3</i>
        <span class="ali-ministep-text">第三步</span>
    </li>
</ol>
````
