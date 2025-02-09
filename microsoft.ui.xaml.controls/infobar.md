---
-api-id: T:Microsoft.UI.Xaml.Controls.InfoBar
-api-type: winrt class
---

# Microsoft.UI.Xaml.Controls.InfoBar

<!--
public class InfoBar : Windows.UI.Xaml.Controls.Control
-->


## -description

An `InfoBar` is an inline notification for essential app-wide messages. The `InfoBar` will take up space in a layout and will not cover up other content or float on top of it. It supports rich content (including titles, messages, icons, and buttons) and can be configured to be user-dismissable or persistent.

## -remarks

Use an `InfoBar` control when a user should be informed of, acknowledge, or take action on a changed application state. The changed state should impact app perception or experience for the user.  

### Control style and template

You can modify the default [Style](../microsoft.ui.xaml/style.md) and [ControlTemplate](controltemplate.md) to give the control a unique appearance. For information about modifying a control's style and template, see [XAML styles](/windows/apps/design/style/xaml-styles). XAML also includes resources that you can use to modify the colors of a control in different visual states without modifying the control template. Modifying these resources is preferred to setting properties such as [Background](control_background.md) and [Foreground](control_foreground.md). For more info, see the [Light-weight styling](/windows/apps/design/style/xaml-styles#lightweight-styling) section of the [XAML styles](/windows/apps/design/style/xaml-styles) article.

The resources for this control are listed in the [ThemeDictionaries](/windows/apps/design/style/xaml-theme-resources) section of the [InfoBar_themeresources.xaml](https://github.com/microsoft/microsoft-ui-xaml/blob/main/dev/InfoBar/InfoBar_themeresources.xaml) file on GitHub. The `ResourceKey` value for each `StaticResource` references a brush and color in the [Common_themeresources_any.xaml](https://github.com/microsoft/microsoft-ui-xaml/blob/main/dev/CommonStyles/Common_themeresources_any.xaml) file.

## -see-also

[InfoBar overview](/windows/apps/design/controls/infobar)

## -examples

> [!TIP]
> For more info, design guidance, and code examples, see [InfoBar](/windows/apps/design/controls/infobar).

> [!div class="nextstepaction"]
> [Open the WinUI 3 Gallery app and see the InfoBar in action](winui3gallery:/item/InfoBar).

> The **WinUI 3 Gallery** app includes interactive examples of most WinUI 3 controls, features, and functionality. Get the app from the [Microsoft Store](https://www.microsoft.com/store/productId/9P3JFPWWDZRC) or get the source code on [GitHub](https://github.com/microsoft/WinUI-Gallery).
