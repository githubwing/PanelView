# PanelView
android PanelView DashBoard 仪表盘 汽车仪表盘 气压仪表盘
=======
# ~~已废弃~~
本项目为初学view练手只做，内部大量错误，请勿在项目中使用！
存在问题如下：
1.在ondraw()方法中new 对象。
2.canvas.save() 以及canvas.rotate()更方便。
3.onDraw()内代码复杂。

![image](https://github.com/githubwing/PanelView/raw/master/perview.gif)
###How To Use
add a CirclePercentView into your XML.

```
   <com.wingsofts.panelview.PanelView
        android:id="@+id/panelView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />
    <com.wingsofts.panelview.PanelView
        android:id="@+id/panelView2"
        wing:arcColor="#EF1C63"
        android:text="当前速度"
        android:textSize="18sp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />
```
you can change percent by call method
```
setPercent();
setText();
setTextSize();
setArcColor();
setPointerColor();
setArcWidth();

```
# License

    Copyright 2016 androidwing1992

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
