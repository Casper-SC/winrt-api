---
-api-id: T:Windows.UI.Xaml.Shapes.Rectangle
-api-type: winrt class
---

<!-- Class syntax.
public class Rectangle : Windows.UI.Xaml.Shapes.Shape, Windows.UI.Xaml.Shapes.IRectangle
-->

# Windows.UI.Xaml.Shapes.Rectangle

## -description
Draws a rectangle with a given [Height](../windows.ui.xaml/frameworkelement_height.md) and [Width](../windows.ui.xaml/frameworkelement_width.md) specified in device-independent pixel (DIP).

## -xaml-syntax
```xaml
<Rectangle .../>
```


## -remarks
You can set the [Fill](shape_fill.md) property to give the shape a background fill, like a solid color, gradient, or image. You can set the [Stroke](shape_stroke.md) and other related stroke properties to specify the look of the shape's outline.

## -examples
This example shows how to create a [Rectangle](rectangle.md) in XAML and set some of its common properties as attribute values.

```xaml
<Canvas>  
  <Rectangle Width="100" Height="100" Fill="Blue" Stroke="Red" 
   Canvas.Top="20" Canvas.Left="20" StrokeThickness="3" />
</Canvas>
```



## -see-also
[Shape](shape.md), [XAML vector-based drawing sample](https://go.microsoft.com/fwlink/p/?linkid=226866), [Draw shapes](https://msdn.microsoft.com/library/54cc0bd4-1961-44d7-ab40-6e8b58e42d65)
