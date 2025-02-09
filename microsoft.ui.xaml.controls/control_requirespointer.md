---
-api-id: P:Microsoft.UI.Xaml.Controls.Control.RequiresPointer
-api-type: winrt property
---

<!-- Property syntax
public Windows.UI.Xaml.Controls.RequiresPointer RequiresPointer { get;  set; }
-->

# Microsoft.UI.Xaml.Controls.Control.RequiresPointer

## -description

Gets or sets whether a UI element supports mouse mode, which emulates pointer interaction experiences with non-pointer input devices such as a keyboard or Xbox controller.

## -xaml-syntax
```xaml
<control RequiresPointer="requiresPointerMemberName"/>
```

## -xaml-values

<dl><dt>requiresPointerMemberName</dt><dd>requiresPointerMemberNameA named constant of the RequiresPointer enumeration, such as WhenEngaged.</dd>
</dl>
## -property-value
The pointer emulation mode. The default is **Never**.

## -remarks

For non-pointer input devices, focus is moved between controls through a variety of methods, such as the Tab and arrow keys on a keyboard or the directional pad (D-pad) and thumb sticks on an Xbox controller. For some user experiences, such as maps and drawing surfaces, it is not possible or practical to use XY focus navigation. RequiresPointer enables an app to provide a more pointer-like interaction experience through a cursor that can be moved freely using the Xbox controller.

RequiresPointer is supported only when using an Xbox controller. The property is ignored otherwise.

For more info, see the [Mouse mode](/windows/uwp/input-and-devices/designing-for-tv) section of [Designing for Xbox and TV](/windows/uwp/input-and-devices/designing-for-tv).

## -examples

## -see-also
