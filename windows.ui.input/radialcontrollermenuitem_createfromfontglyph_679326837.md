---
-api-id: M:Windows.UI.Input.RadialControllerMenuItem.CreateFromFontGlyph(System.String,System.String,System.String,Windows.Foundation.Uri)
-api-type: winrt method
---

<!-- Method syntax.
public RadialControllerMenuItem RadialControllerMenuItem.CreateFromFontGlyph(String displayText, String glyph, String fontFamily, Uri fontUri)
-->

# Windows.UI.Input.RadialControllerMenuItem.CreateFromFontGlyph

## -description
Creates a custom tool (using the specified text string and font glyph) on the [RadialController](radialcontroller.md) menu.

## -parameters

### -param displayText
The text string to display for the custom tool.

### -param glyph
The font glyph to display for the custom tool.

### -param fontFamily
The font family that contains the glyph to display for the custom tool.

### -param fontUri
The Uniform Resource Identifier (URI) that identifies the location of the font used for rendering the glyph.

## -returns
The custom tool.

## -remarks
When using this method overload to reference a font glyph installed with your app's appx package, your app might display a broken image when deployed from Visual Studio. In this case, you should first create an app package (**Project->Store->CreateAppPackage**) and then deploy.

[UX guidelines](https://msdn.microsoft.com/en-us/windows/uwp/input-and-devices/windows-wheel-interactions) for the Surface Dial recommend the following:

+ **Text**
  + Names should be short to fit inside the central circle of the wheel menu
  + Names should clearly identify the primary action (a complementary action can be implied)   
  + Scroll indicates the effect of both rotation directions
  + Undo specifies a primary action, but redo (the complementary action) can be inferred and easily discovered by the user

## -see-also
- [CreateFromFontGlyph(String displayText, String glyph, String fontFamily)](radialcontrollermenuitem_createfromfontglyph_63723173.md)
- [CreateFromIcon](radialcontrollermenuitem_createfromicon.md)
- [CreateFromKnownIcon](radialcontrollermenuitem_createfromknownicon.md)
- [Surface Dial interactions](https://msdn.microsoft.com/en-us/windows/uwp/input-and-devices/windows-wheel-interactions)
- [Universal Windows Platform samples (C# and C++)](https://go.microsoft.com/fwlink/?linkid=832713)
- [Windows classic desktop sample](https://aka.ms/radialcontrollerclassicsample)


## -examples

