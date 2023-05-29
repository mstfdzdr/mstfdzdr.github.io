# Visual Studio Code'a Özel Tuş Kombinasyonları Atama


Jetbrains IDE'lerine alışkın olanların çok sık kullandığı tuş kombinaslarından biri SHIFT tuşuna iki kere basmaktır. Bu alışkanlığımıza Visual Studio Code'da da devam edebiliriz.

<!--more-->

Bunun için Visual Studio Code'da tuş atamalarının bulunduğu menüden özel atamalar yapmak için keybindings.json'u düzenlemek. Aşağıdaki eklemeleri yaparak isteğiniz özelleştirmeleri sağlayabilirsiniz.

SHIFT + SHIFT: VS Code Quick Open Menüsü

{{< highlight json >}}
{
    "key": "shift shift",
    "command": "workbench.action.quickOpen"
}
{{< /highlight >}}

ALT + ALT: VS Code Command Menüsü

{{< highlight json >}}
{
    "key": "alt alt",
    "command": "workbench.action.showCommands"
}
{{< /highlight >}}

CTRL + CTRL: VS Code Sidebar Gizle/Göster

{{< highlight json >}}
{
    "key": "ctrl ctrl",
    "command": "workbench.action.toggleSidebarVisibility"
}
{{< /highlight >}}
