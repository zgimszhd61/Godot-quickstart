以下是一个使用Godot引擎编写的“Hello, World!”示例。这个示例将展示如何在Godot中创建一个简单的脚本，并在控制台中打印“Hello, World!”。

### 步骤一：创建一个新的Godot项目

1. 打开Godot引擎，点击“New Project”按钮。
2. 为项目命名并选择一个保存路径，然后点击“Create & Edit”按钮。

### 步骤二：创建一个场景

1. 在场景树（Scene Tree）中，右键点击根节点并选择“Add Child Node”。
2. 在弹出的窗口中，搜索并选择“Node2D”，然后点击“Create”按钮。

### 步骤三：创建并附加脚本

1. 右键点击新创建的Node2D节点，选择“Attach Script”。
2. 在弹出的窗口中，选择GDScript作为脚本语言，保持其他选项默认，然后点击“Create”按钮。

### 步骤四：编写脚本

在新创建的脚本文件中，添加以下代码：

```gdscript
extends Node2D

func _ready():
    print("Hello, World!")
```

### 步骤五：运行项目

1. 保存场景（Ctrl+S），为场景命名并保存。
2. 点击Godot界面顶部的“Play”按钮运行项目。
3. 在Godot的输出面板中，你将看到“Hello, World!”的打印输出。

这个示例展示了如何在Godot中创建一个简单的脚本，并在控制台中打印“Hello, World!”。通过这些步骤，你可以快速上手Godot引擎并开始编写自己的脚本[5][7]。

Citations:
[1] https://www.youtube.com/watch?v=iT0Phjwcwj0
[2] https://godot-rust.github.io/gdnative-book/intro/hello-world.html
[3] https://godot-rust.github.io/book/intro/hello-world.html
[4] https://www.youtube.com/watch?v=JhpsnCBbWJo
[5] https://docs.godotengine.org/en/stable/getting_started/step_by_step/scripting_first_script.html
[6] https://docs.godotengine.org/en/stable/getting_started/first_2d_game/index.html
[7] https://docs.godotengine.org/zh-tw/4.x/getting_started/step_by_step/scripting_first_script.html
[8] https://www.gcores.com/articles/176629
