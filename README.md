# UnityUI

https://learn.unity.com/project/creative-core-ui?uv=2020.3

## Text
- Right click in Hierarchy - UI - Text-TextMeshPro
- Change object name - Text (TMP) > Custom text
- you can find good font in fonts.google.com
- window > TextMeshPro > Font Asset Creator > Set Source Font File > Generate Font Atlas >Set Custom TMP_Font_Asset in TextMeshPro - Text (UI) component (in text object)
- Set Aspect ratio 16:9, 16:9 is the standard widescreen ratio, so it’s the safest option.

## Button
- Hierarchy > UI > Button - TextMeshPro
- HotKey : ViewTool(Q), Move(W), Rotate(E), Scale(R), Rect(T), Transform(Y)
- After selecting an object, you can fix the distance between the anchor and the button position by adjusting the anchor.

## Canvas
- Canvas Scaler
    - Constant Pixel Size
    - Scale With Screen Size (v)
    - Constant Physical Size

## Button Event
- Inspector > Button > On Click > Drag Object to the empty Object Fields
- Use the function dropdowns, GameObject.SecActive