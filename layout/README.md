# 布局
## 左边固定，右边自适应
* float + margin-left / float + overflow
  * [普通示例](./left-fixed-right-fluid-1-1.html)
  * [左右等高：背景图](./left-fixed-right-fluid-1-2.html)
    - 列与列之间可以设置分隔线效果，无法实现每列四周有边框效果
  * [左右等高：padding-bottom和负margin-bottom](./left-fixed-right-fluid-1-3.html)
    - 可以设置左、上、右的边框效果，无法设置底部边框
    - [底部边框：背景图](./left-fixed-right-fluid-1-4.html)
    - [底部边框：div绝对定位](./left-fixed-right-fluid-1-5.html)
  * [左右等高：background:linear-gradient](./left-fixed-right-fluid-1-6.html)
    - 无法设置边框
* float + border-left
  * [普通示例](./left-fixed-right-fluid-2-1.html)
    - 右边的border-left的颜色必须和左边的背景色相同
    - 左右等高：外层容器的背景色为右边的颜色
  * 左右等高：padding-bottom和负margin-bottom
    - 同[float + margin-left](./left-fixed-right-fluid-1-3.html)的padding-bottom和负margin-bottom
    - 可以设置左、上、右的边框效果（右边无法设置左边框），无法设置底部边框
    - 底部边框：背景图，同[float + margin-left](./left-fixed-right-fluid-1-4.html)
    - 底部边框：div绝对定位，同[float + margin-left](./left-fixed-right-fluid-1-5.html)
* float + 负margin-right
  * [普通示例](./left-fixed-right-fluid-3-1.html)
* absolute + margin-left
  * [普通示例](./left-fixed-right-fluid-4-1.html)
* display:table
  * [普通示例](./left-fixed-right-fluid-5-1.html)
    - 左右等高，可以设置边框效果
* display: flex
  * [普通示例](./left-fixed-right-fluid-6-1.html)
    - 左右等高，可以设置边框效果
* display: grid
  * [普通示例](./left-fixed-right-fluid-7-1.html)
    - 左右等高，可以设置边框效果

## 右边固定，左边自适应
* float + margin-right
  * [普通示例](./right-fixed-left-fluid-1-1.html)
* float + border-left
  * [普通示例](./right-fixed-left-fluid-2-1.html)
* float + 负margin-right
  * [普通示例](./right-fixed-left-fluid-3-1.html)
* absolute + margin-right
  * [普通示例](./right-fixed-left-fluid-4-1.html)
* display:table
  * [普通示例](./right-fixed-left-fluid-5-1.html)
* display: flex
  * [普通示例](./right-fixed-left-fluid-6-1.html)
* display: grid
  * [普通示例](./right-fixed-left-fluid-7-1.html)

## 一列固定宽度
fixed-width-1
## 一列宽度自适应
responsive-width-1
## 两列固定宽度
fixed-width-2
## 二列宽度自适应
responsive-width-2
## 两列右列宽度自适应
fixed-responsive
## 三列浮动中间列自适应
