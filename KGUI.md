## Indexing
__Item__:
[`ItemNull`](#LuaItemNull)
[`ItemText`](#LuaItemText)

# <h1 id="LuaItemNull">ItemNull</h1>
----------
[`SetVisible`](#LuaItemNull_SetVisible)
[`Show`](#LuaItemNull_Show)
[`Hide`](#LuaItemNull_Hide)
[`PtInItem`](#LuaItemNull_PtInItem)
[`SetRelX`](#LuaItemNull_SetRelX)
[`SetRelY`](#LuaItemNull_SetRelY)
[`GetRelX`](#LuaItemNull_GetRelX)
[`GetRelY`](#LuaItemNull_GetRelY)
[`SetAbsX`](#LuaItemNull_SetAbsX)
[`SetAbsY`](#LuaItemNull_SetAbsY)
[`GetAbsX`](#LuaItemNull_GetAbsX)
[`GetAbsY`](#LuaItemNull_GetAbsY)
[`SetW`](#LuaItemNull_SetW)
[`SetH`](#LuaItemNull_SetH)
[`GetW`](#LuaItemNull_GetW)
[`GetH`](#LuaItemNull_GetH)
[`SetRelPos`](#LuaItemNull_SetRelPos)
[`GetRelPos`](#LuaItemNull_GetRelPos)
[`SetAbsPos`](#LuaItemNull_SetAbsPos)
[`GetAbsPos`](#LuaItemNull_GetAbsPos)
[`SetSize`](#LuaItemNull_SetSize)
[`GetSize`](#LuaItemNull_GetSize)
[`SetPosType`](#LuaItemNull_SetPosType)
[`GetPosType`](#LuaItemNull_GetPosType)
[`IsVisible`](#LuaItemNull_IsVisible)
[`GetName`](#LuaItemNull_GetName)
[`SetName`](#LuaItemNull_SetName)
[`SetTip`](#LuaItemNull_SetTip)
[`GetTip`](#LuaItemNull_GetTip)
[`SetUserData`](#LuaItemNull_SetUserData)
[`GetUserData`](#LuaItemNull_GetUserData)
[`RegisterEvent`](#LuaItemNull_RegisterEvent)
[`ClearEvent`](#LuaItemNull_ClearEvent)
[`EnableScale`](#LuaItemNull_EnableScale)
[`Scale`](#LuaItemNull_Scale)
[`LockShowAndHide`](#LuaItemNull_LockShowAndHide)
[`SetAlpha`](#LuaItemNull_SetAlpha)
[`GetAlpha`](#LuaItemNull_GetAlpha)
[`GetParent`](#LuaItemNull_GetParent)
[`GetRoot`](#LuaItemNull_GetRoot)
[`GetType`](#LuaItemNull_GetType)
[`GetIndex`](#LuaItemNull_GetIndex)
[`SetIndex`](#LuaItemNull_SetIndex)
[`ExchangeIndex`](#LuaItemNull_ExchangeIndex)
[`GetTreePath`](#LuaItemNull_GetTreePath)
[`SetAreaTestFile`](#LuaItemNull_SetAreaTestFile)
[`SetIntPos`](#LuaItemNull_SetIntPos)
[`IsIntPos`](#LuaItemNull_IsIntPos)
[`IsLink`](#LuaItemNull_IsLink)
[`GetLinkInfo`](#LuaItemNull_GetLinkInfo)
[`SetLinkInfo`](#LuaItemNull_SetLinkInfo)
[`GetAniParamID`](#LuaItemNull_GetAniParamID)
[`IsValid`](#LuaItemNull_IsValid)
[`__eq`](#LuaItemNull_Equal)
[`GetBaseType`](#LuaItemNull_GetBaseType)

* <h4 id="LuaItemNull_SetVisible">SetVisible</h4>
Set Item Visibility.

 > (`void`) ItemNull:SetVisible(`bool` bVisible)

 ````lua
 ItemNull:SetVisible(false)
 ````

* <h4 id="LuaItemNull_Show">Show</h4>
Show Item, same as [`:SetVisible(true)`](#LuaItemNull_SetVisible).

 > (`void`) ItemNull:Show()

 ````lua
 ItemNull:Show()
 ````

* <h4 id="LuaItemNull_Hide">Hide</h4>
Hide Item, same as [`:SetVisible(false)`](#LuaItemNull_SetVisible).

 > (`void`) ItemNull:Hide()

 ````lua
 ItemNull:Hide()
 ````

* <h4 id="LuaItemNull_PtInItem">PtInItem</h4>
Judge if a given screen position is in this Item. Always use with `Cursor.GetPos()`.
 > (`bool` bIsInItem) ItemNull:PtInItem(`number` nX, `number` nY)
 
 ````lua
 local bIsInItem = ItemNull:PtInItem(600, 800)
 local bIsInItem = ItemNull:PtInItem(Cursor.GetPos())
 ````

* <h4 id="LuaItemNull_SetRelX">SetRelX</h4>
Set Item's relative X (to its parent).

 > (`void`) ItemNull:SetRelX(`number` nX)

 ````lua
 ItemNull:SetRelX(10)
 ````

* <h4 id="LuaItemNull_SetRelY">SetRelY</h4>
Set Item's relative Y (to its parent).

 > (`void`) ItemNull:SetRelY(`number` nY)

 ````lua
 ItemNull:SetRelY(10)
 ````

* <h4 id="LuaItemNull_GetRelX">GetRelX</h4>
Get Item's relative X (to its parent).

 > (`number` nX) ItemNull:GetRelX()

 ````lua
 local nX = ItemNull:GetRelX()
 ````

* <h4 id="LuaItemNull_GetRelY">GetRelY</h4>
Get Item's relative Y (to its parent).

 > (`number` nY) ItemNull:GetRelY()

 ````lua
 local nY = ItemNull:GetRelY()
 ````

* <h4 id="LuaItemNull_SetAbsX">SetAbsX</h4>
Set Item's absolute X (to the screen).

 > (`void`) ItemNull:SetAbsX(`number` nX)

 ````lua
 ItemNull:SetAbsX(10)
 ````

* <h4 id="LuaItemNull_SetAbsY">SetAbsY</h4>
Set Item's absolute Y (to the screen).

 > (`void`) ItemNull:SetAbsY(`number` nY)

 ````lua
 ItemNull:SetAbsY(10)
 ````

* <h4 id="LuaItemNull_GetAbsX">GetAbsX</h4>
Get Item's absolute X (to the screen).

 > (`number` nX) ItemNull:GetAbsX()

 ````lua
 local nX = ItemNull:GetAbsX()
 ````

* <h4 id="LuaItemNull_GetAbsY">GetAbsY</h4>
Get Item's absolute Y (to the screen).

 > (`number` nY) ItemNull:GetAbsY()

 ````lua
 local nY = ItemNull:GetAbsY()
 ````

* <h4 id="LuaItemNull_SetW">SetW</h4>
Set Item's width.

 > (`void`) ItemNull:SetW(`number` nW)

 ````lua
 ItemNull:SetW(100)
 ````

* <h4 id="LuaItemNull_SetH">SetH</h4>
Set Item's height.

 > (`void`) ItemNull:SetH(`number` nW)

 ````lua
 ItemNull:SetH(100)
 ````

* <h4 id="LuaItemNull_GetW">GetW</h4>
Get Item's width.

 > (`number` nW) ItemNull:GetW()

 ````lua
 local nW = ItemNull:GetW()
 ````

* <h4 id="LuaItemNull_GetH">GetH</h4>
Get Item's height.

 > (`number` nH) ItemNull:GetH()

 ````lua
 local nH = ItemNull:GetH()
 ````

* <h4 id="LuaItemNull_SetRelPos">SetRelPos</h4>
Set Item's relative position. The union of [`:SetRelX`](#LuaItemNull_SetRelX) and [`:SetRelY`](#LuaItemNull_SetRelY).

 > (`void`) ItemNull:SetRelPos(`number` nX, `number` nY)

 ````lua
 ItemNull:SetRelPos(100, 200)
 ````

* <h4 id="LuaItemNull_GetRelPos">GetRelPos</h4>
Get Item's relative position. The union of [`:GetRelX`](#LuaItemNull_GetRelX) and [`:GetRelY`](#LuaItemNull_GetRelY).

 > (`number` nX, `number` nY) ItemNull:GetRelPos()

 ````lua
 local nX, nY = ItemNull:GetRelPos()
 ````

* <h4 id="LuaItemNull_SetAbsPos">SetAbsPos</h4>
Set Item's relative position. The union of [`:SetAbsX`](#LuaItemNull_SetAbsX) and [`:SetAbsY`](#LuaItemNull_SetAbsY).

 > (`void`) ItemNull:SetAbsPos(`number` nX, `number` nY)

 ````lua
 ItemNull:SetAbsPos(500, 300)
 ````

* <h4 id="LuaItemNull_GetAbsPos">GetAbsPos</h4>
Get Item's relative position. The union of [`:GetAbsX`](#LuaItemNull_GetAbsX) and [`:GetAbsY`](#LuaItemNull_GetAbsY).

 > (`number` nX, `number` nY) ItemNull:GetAbsPos()

 ````lua
 local nX, nY = ItemNull:GetAbsPos()
 ````

* <h4 id="LuaItemNull_SetSize">SetSize</h4>
Set Item's size. The union of [`:SetW`](#LuaItemNull_SetW) and [`:SetH`](#LuaItemNull_SetH).

 > (`void`) ItemNull:SetSize(`number` nW, `number` nH)

 ````lua
 ItemNull:SetSize(600, 800)
 ````

* <h4 id="LuaItemNull_GetSize">GetSize</h4>
Get Item's size. The union of [`:GetW`](#LuaItemNull_GetW) and [`:GetH`](#LuaItemNull_GetH).

 > (`number` nW, `number` nH) ItemNull:GetSize()

 ````lua
 local nW, nH = ItemNull:GetSize()
 ````

* <h4 id="LuaItemNull_SetPosType">SetPosType</h4>
Set Item's position type. See the enum of [`ITEM_POSITION`](#ITEM_POSITION).

 > (`void`) ItemNull:SetPosType()

 ````lua
 ItemNull:SetPosType(ITEM_POSITION.RIGHT_BOTTOM)
 ````

* <h4 id="LuaItemNull_GetPosType">GetPosType</h4>
Get Item's position type. See the enum of [`ITEM_POSITION`](#ITEM_POSITION).

 > (`enum` nPosType) ItemNull:GetPosType()

 ````lua
 local nPosType = ItemNull:GetPosType()
 ````

* <h4 id="LuaItemNull_IsVisible">IsVisible</h4>
Get Item's visibility.

 > (`bool` bVisible) ItemNull:IsVisible()

 ````lua
 local bVisible = ItemNull:IsVisible()
 ````

* <h4 id="LuaItemNull_GetName">GetName</h4>
Get Item's name.

 > (`string` szName) ItemNull:GetName()

 ````lua
 local szName = ItemNull:GetName()
 ````

* <h4 id="LuaItemNull_SetName">SetName</h4>
Set Item's name.

 > (`void`) ItemNull:SetName(`string` szName)

 ````lua
 ItemNull:SetName("Item_001")
 ````

* <h4 id="LuaItemNull_SetTip">SetTip</h4>
Set Item's tip. When mouse enter it, the tip will be shown.

 > (`void`) ItemNull:SetTip(`string` szTip)

 ````lua
 ItemNull:SetTip('<text>text="this is a tip"</text>')
 ````

* <h4 id="LuaItemNull_GetTip">GetTip</h4>
Get Item's tip.

 > (`string` szTip) ItemNull:GetTip()

 ````lua
 local szTip = ItemNull:GetTip()
 ````

* <h4 id="LuaItemNull_SetUserData">SetUserData</h4>
Set a number to the Item.

 > (`void`) ItemNull:SetUserData(`number` nData)

 ````lua
 ItemNull:SetUserData(27)
 ````

* <h4 id="LuaItemNull_GetUserData">GetUserData</h4>
Get Item's userdata.

 > (`number` nData) ItemNull:GetUserData()

 ````lua
 local nData = ItemNull:GetUserData()
 ````

* <h4 id="LuaItemNull_RegisterEvent">RegisterEvent</h4>
Register an ui event so that this item is able to response the specified ui event such as mouse click event.

 > (`void`) ItemNull:RegisterEvent(`number` nUIEvent)

 ````lua
 ItemNull:RegisterEvent(256)
 ````

* <h4 id="LuaItemNull_ClearEvent">ClearEvent</h4>
Clear all ui event on this Item.

 > (`void`) ItemNull:ClearEvent()

 ````lua
 ItemNull:ClearEvent()
 ````

* <h4 id="LuaItemNull_EnableScale">EnableScale</h4>
Set if this Item can be scaled.

 > (`void`) ItemNull:EnableScale(`bool` bEnableScale)

 ````lua
 ItemNull:EnableScale(true)
 ````

* <h4 id="LuaItemNull_Scale">Scale</h4>
Scale an Item. Please noticed that it's children will also be scaled. And remember to save the scale to some place because there is no api to get current scale level. The working principle of this api is just traverse all its children and itself and make their width and height multiplied with the given scale value.

 > (`void`) ItemNull:Scale(`number` fScaleX, `number` fScaleY)

 ````lua
 ItemNull:Scale(0.7, 0.9)
 ````

* <h4 id="LuaItemNull_LockShowAndHide">LockShowAndHide</h4>
Set if this Item's default visibility is invisible.

 > (`void`) ItemNull:LockShowAndHide(`bool` bEnable)

 ````lua
 ItemNull:LockShowAndHide(true)
 ````

* <h4 id="LuaItemNull_SetAlpha">SetAlpha</h4>
Set its alpha. The value can be set between 0 and 255.

 > (`void`) ItemNull:SetAlpha(`number` nAlpha)

 ````lua
 ItemNull:SetAlpha(255)
 ````

* <h4 id="LuaItemNull_GetAlpha">GetAlpha</h4>
Get its alpha value (0 - 255).

 > (`number` nAlpha) ItemNull:GetAlpha()

 ````lua
 local nAlpha = ItemNull:GetAlpha()
 ````

* <h4 id="LuaItemNull_GetParent">GetParent</h4>
Get its parent node. It will return `null` if it has no parent.

 > (`KGUI OBJECT` pParent) ItemNull:GetParent()

 ````lua
 local hParent = ItemNull:GetParent()
 ````

* <h4 id="LuaItemNull_GetRoot">GetRoot</h4>
Get its root parent node (the frame).

 > (`KGUI Frame` pFrame) ItemNull:GetRoot()

 ````lua
 local hFrame = ItemNull:GetRoot()
 ````

* <h4 id="LuaItemNull_GetType">GetType</h4>
Get its ui type, such as `WndWindow`, `Handle`, `Text`, etc.

 > (`string` szType) ItemNull:GetType()

 ````lua
 local szType = ItemNull:GetType()
 ````

* <h4 id="LuaItemNull_GetIndex">GetIndex</h4>
Get its index. The value will between 0 and the count of its brothers.

 > (`number` nIndex) ItemNull:GetIndex()

 ````lua
 local nIndex = ItemNull:GetIndex()
 ````

* <h4 id="LuaItemNull_SetIndex">SetIndex</h4>
Set its index. The value must between 0 and the count of its brothers.

 > (`void`) ItemNull:SetIndex(`number` nIndex)

 ````lua
 ItemNull:SetIndex(0)
 ````

* <h4 id="LuaItemNull_ExchangeIndex">ExchangeIndex</h4>
Exchange the index with one of its brothers.
> * (`void`) ItemNull:ExchangeIndex(`number` nIndex)
> * (`void`) ItemNull:ExchangeIndex(`KGUI Object` pBrotherItem)

 ````lua
 ItemNull:ExchangeIndex(0)
 ItemNull:ExchangeIndex(ItemNull:GetParent():Lookup(0))
 ````

* <h4 id="LuaItemNull_GetTreePath">GetTreePath</h4>
Get the tree path of this Item.

 > (`string` szWndTreePath, `string` szHandleTreePath) ItemNull:GetTreePath()

 ````lua
 local szWndTreePath, szHandleTreePath = ItemNull:GetTreePath()
 ````

<!-- * <h4 id="LuaItemNull_SetAreaTestFile">SetAreaTestFile</h4> -->

<!-- * <h4 id="LuaItemNull_SetIntPos">SetIntPos</h4> -->

<!-- * <h4 id="LuaItemNull_IsIntPos">IsIntPos</h4> -->

<!-- * <h4 id="LuaItemNull_IsLink">IsLink</h4> -->

<!-- * <h4 id="LuaItemNull_GetLinkInfo">GetLinkInfo</h4> -->

<!-- * <h4 id="LuaItemNull_SetLinkInfo">SetLinkInfo</h4> -->

<!-- * <h4 id="LuaItemNull_GetAniParamID">GetAniParamID</h4> -->

* <h4 id="LuaItemNull_IsValid">IsValid</h4>
Check if this Item is still vaild. Once the Item get destroyed, this api will return `false`.

 > (`bool` bValid) ItemNull:IsValid()

 ````lua
 local bValid = ItemNull:IsValid()
 ````

<!-- * <h4 id="LuaItemNull_Equal">__eq</h4> -->

* <h4 id="LuaItemNull_GetBaseType">GetBaseType</h4>
Get its base type. The value can be `Item` or `Wnd`.

 > (`string` szBaseType) ItemNull:GetBaseType()

 ````lua
 local szBaseType = ItemNull:GetBaseType()
 ````

# <h1 id="LuaItemText">ItemText</h1>
----------
[`SetFontScheme`](#LuaItemText_SetFontScheme)
[`GetFontScheme`](#LuaItemText_GetFontScheme)
[`SetRange`](#LuaItemText_SetRange)
[`SetTime`](#LuaItemText_SetTime)
[`SetNumber`](#LuaItemText_SetNumber)
[`GetNumber`](#LuaItemText_GetNumber)
[`SetText`](#LuaItemText_SetText)
[`GetText`](#LuaItemText_GetText)
[`GetTextLen`](#LuaItemText_GetTextLen)
[`SetVAlign`](#LuaItemText_SetVAlign)
[`GetVAlign`](#LuaItemText_GetVAlign)
[`SetHAlign`](#LuaItemText_SetHAlign)
[`GetHAlign`](#LuaItemText_GetHAlign)
[`SetRowSpacing`](#LuaItemText_SetRowSpacing)
[`GetRowSpacing`](#LuaItemText_GetRowSpacing)
[`SetMultiLine`](#LuaItemText_SetMultiLine)
[`IsMultiLine`](#LuaItemText_IsMultiLine)
[`FormatTextForDraw`](#LuaItemText_FormatTextForDraw)
[`AutoSize`](#LuaItemText_AutoSize)
[`SetCenterEachLine`](#LuaItemText_SetCenterEachLine)
[`IsCenterEachLine`](#LuaItemText_IsCenterEachLine)
[`SetFontSpacing`](#LuaItemText_SetFontSpacing)
[`GetFontSpacing`](#LuaItemText_GetFontSpacing)
[`SetRichText`](#LuaItemText_SetRichText)
[`IsRichText`](#LuaItemText_IsRichText)
[`GetFontScale`](#LuaItemText_GetFontScale)
[`SetFontScale`](#LuaItemText_SetFontScale)
[`SetFontID`](#LuaItemText_SetFontID)
[`SetFontColor`](#LuaItemText_SetFontColor)
[`SetFontBorder`](#LuaItemText_SetFontBoder)
[`SetFontShadow`](#LuaItemText_SetFontShadow)
[`GetFontID`](#LuaItemText_GetFontID)
[`GetFontColor`](#LuaItemText_GetFontColor)
[`GetFontBoder`](#LuaItemText_GetFontBoder)
[`GetFontProjection`](#LuaItemText_GetFontProjection)
[`GetTextExtent`](#LuaItemText_GetTextExtent)
[`GetTextPosExtent`](#LuaItemText_GetTextPosExtent)

* <h4 id="LuaItemText_SetFontScheme">SetFontScheme</h4>
Set text font scheme.<br>
This api will load `pFontScheme` by `nFontID`, and then call this:<br>
[`:SetFontID(pFontScheme->nFontID)`](#LuaItemText_SetFontID)<br>
[`:SetFontColor(pFontScheme->GetFontColor())`](#LuaItemText_SetFontID)<br>
[`:SetFontBorder(pFontScheme->nBorderSize, pFontScheme->GetBoderColor())`](#LuaItemText_SetFontID)<br>
[`:SetFontShadow(pFontScheme->nShadowOffset, pFontScheme->GetShadowColor())`](#LuaItemText_SetFontShadow)<br>
[`:SetFontScale(pFontScheme->fScale)`](#LuaItemText_SetFontScale)<br>

 > (`void`) ItemText:SetFontScheme(`number` nFont)

 ````lua
 ItemText:SetFontScheme(192)
 ````


* <h4 id="LuaItemText_GetFontScheme">GetFontScheme</h4>
Get text font scheme.

 > (`number` nFont) ItemText:GetFontScheme()

 ````lua
 local nFont = ItemText:GetFontScheme()
 ````

* <h4 id="LuaItemText_SetRange">SetRange</h4>
Set text as range format. Notice that this api is the same as [`:SetText(nValue1 .. szDelimiter .. nVlaue2)`](#LuaItemText_SetText). But this api is high performanced than `:SetText` cause there is no intermediate string when concat string.
> * (`void`) ItemText:SetRange(`number` nValue, `string` szDelimiter)
> * (`void`) ItemText:SetRange(`number` nValue1, `string` szDelimiter, `number` nValue2)

 ````lua
 ItemText:SetRange(5, "%")
 ItemText:SetRange(5, "/", 100)
 ````

* <h4 id="LuaItemText_SetTime">SetTime</h4>
Set text as time format. Notice that this api is the same as [`:SetText(("%02d:%02d:%02d"):format(TimeToHMS(nTime)))`](#LuaItemText_SetText). But this api is high performanced than `:SetText` cause there is no intermediate string when concat string.

 > (`void`) ItemText:SetTime(`number` nTimeStamp)

 ````lua
 ItemText:SetTime(GetCurrentTime())
 ````

* <h4 id="LuaItemText_SetNumber">SetNumber</h4>
Set text as pure number. Notice that this api is the same as [`:SetText(tostring(nNumber))`](#LuaItemText_SetText). But this api is high performanced than `:SetText` cause there is no intermediate string when concat string.

 > (`void`) ItemText:SetNumber(`number` nNumber)

 ````lua
 ItemText:SetNumber(213928)
 ````

* <h4 id="LuaItemText_GetNumber">GetNumber</h4>
Get text as pure number. Notice that this api is the same as [`tonumber(:GetText())`](#LuaItemText_SetText). But this api is high performanced than `:SetText` cause there is no intermediate string when concat string.

 > (`number` nNumber) ItemText:GetNumber()

 ````lua
 local nNumber = ItemText:GetNumber()
 ````

* <h4 id="LuaItemText_SetText">SetText</h4>
Set display text.

 > (`void`) ItemText:SetText(`string` szText)

 ````lua
 ItemText:SetText("This is a text.")
 ````

* <h4 id="LuaItemText_GetText">GetText</h4>
Get display text.

 > (`string` szText) ItemText:GetText()

 ````lua
 local szText = ItemText:GetText()
 ````

* <h4 id="LuaItemText_GetTextLen">GetTextLen</h4>
Get the length of display text.

 > (`number` nLen) ItemText:GetTextLen()

 ````lua
 local nLen = ItemText:GetTextLen()
 ````

* <h4 id="LuaItemText_SetVAlign">SetVAlign</h4>
Set text vertical alignment. Enum: `0-top`, `1-center`, `2-bottom`. Notice that you may need to call [`:FormatTextForDraw()`](#LuaItemText_FormatTextForDraw) for apply the change and redraw text immediately.

 > (`void`) ItemText:SetVAlign(`number` nAlign)

 ````lua
 ItemText:SetVAlign(1)
 ````

* <h4 id="LuaItemText_GetVAlign">GetVAlign</h4>
Get text vertical alignment.

 > (`number` nAlign) ItemText:GetVAlign()

 ````lua
 local nAlign = ItemText:GetVAlign()
 ````

* <h4 id="LuaItemText_SetHAlign">SetHAlign</h4>
Set text horizontal alignment. Enum: `0-left`, `1-middle`, `2-right`. Notice that you may need to call [`:FormatTextForDraw()`](#LuaItemText_FormatTextForDraw) for apply the change and redraw text immediately.

 > (`void`) ItemText:SetHAlign(`number` nAlign)

 ````lua
 ItemText:SetHAlign(1)
 ````

* <h4 id="LuaItemText_GetHAlign">GetHAlign</h4>
Get text horizontal alignment.

 > (`number` nAlign) ItemText:GetHAlign()

 ````lua
 local nAlign = ItemText:GetHAlign()
 ````

* <h4 id="LuaItemText_SetRowSpacing">SetRowSpacing</h4>
Set the spacing of two rows.

 > (`void`) ItemText:SetRowSpacing(`number` nSpacing)

 ````lua
 ItemText:SetRowSpacing(3)
 ````

* <h4 id="LuaItemText_GetRowSpacing">GetRowSpacing</h4>
Get the spacing of two rows.

 > (`number` nSpacing) ItemText:GetRowSpacing()

 ````lua
 local nSpacing = ItemText:GetRowSpacing()
 ````

* <h4 id="LuaItemText_SetMultiLine">SetMultiLine</h4>
Set if this text control supports multiline display. Support multiline display means that when the width of the inner text reaches the width of the control, it will auto wrap.

 > (`void`) ItemText:SetMultiLine(`bool` bMultiline)

 ````lua
 ItemText:SetMultiLine(true)
 ````

* <h4 id="LuaItemText_IsMultiLine">IsMultiLine</h4>
Get if it supports multiline.

 > (`bool` bMultiline) ItemText:IsMultiLine()

 ````lua
 local bMultiline = ItemText:IsMultiLine()
 ````

* <h4 id="LuaItemText_FormatTextForDraw">FormatTextForDraw</h4>
Format and redraw the text. When you change the style of text (such as alignment and row spacing), you need to call this api to apply style immediately.

 > (`void`) ItemText:FormatTextForDraw()

 ````lua
 ItemText:FormatTextForDraw()
 ````

* <h4 id="LuaItemText_AutoSize">AutoSize</h4>
Auto set its width and height by its inner text.

 > (`void`) ItemText:AutoSize()

 ````lua
 ItemText:AutoSize()
 ````

* <h4 id="LuaItemText_SetCenterEachLine">SetCenterEachLine</h4>
Set whether to keep center of each line in this text while drawing.

 > (`void`) ItemText:SetCenterEachLine(`bool` bCenter)

 ````lua
 ItemText:SetCenterEachLine(true)
 ````

* <h4 id="LuaItemText_IsCenterEachLine">IsCenterEachLine</h4>
Get whether to keep center of each line in this text while drawing.

 > (`bool` bCenter) ItemText:IsCenterEachLine()

 ````lua
 local bCenter = ItemText:IsCenterEachLine()
 ````

* <h4 id="LuaItemText_SetFontSpacing">SetFontSpacing</h4>
Set the spacing between two characters.

 > (`void`) ItemText:SetFontSpacing(`number` nSpacing)

 ````lua
 ItemText:SetFontSpacing(5)
 ````

* <h4 id="LuaItemText_GetFontSpacing">GetFontSpacing</h4>
Get the spacing between two characters.

 > (`number` nSpacing) ItemText:GetFontSpacing()

 ````lua
 local nSpacing = ItemText:GetFontSpacing()
 ````

* <h4 id="LuaItemText_SetRichText">SetRichText</h4>
Set whether this Text supports rich text.

 > (`void`) ItemText:SetRichText(`bool` bRichText)

 ````lua
 ItemText:SetRichText(true)
 ````

* <h4 id="LuaItemText_IsRichText">IsRichText</h4>
Get whether this Text supports rich text.

 > (`bool` bRichText) ItemText:IsRichText()

 ````lua
 local bRichText = ItemText:IsRichText()
 ````

* <h4 id="LuaItemText_GetFontScale">GetFontScale</h4>
Get scale.

 > (`number` fScale) ItemText:GetFontScale()

 ````lua
 local fScale = ItemText:GetFontScale()
 ````

* <h4 id="LuaItemText_SetFontScale">SetFontScale</h4>
Get scale. Notice that [`:Scale`](#LuaItemNull_Scale) is unavailable on Text control because drawing font is in a different way with drawing other controls.

 > (`void`) ItemText:SetFontScale(`number` fScale)

 ````lua
 ItemText:SetFontScale(2.0)
 ````

* <h4 id="LuaItemText_SetFontID">SetFontID</h4>
Set font id.

 > (`void`) ItemText:SetFontID(`number` nFontID)

 ````lua
 ItemText:SetFontID(1)
 ````

* <h4 id="LuaItemText_SetFontColor">SetFontColor</h4>
Set font color.

 > (`void`) ItemText:SetFontColor(`number` nR, `number` nG, `number` nB)

 ````lua
 ItemText:SetFontColor(255, 255, 0)
 ````

* <h4 id="LuaItemText_SetFontBoder">SetFontBorder</h4>
Set font border.

 > (`void`) ItemText:SetFontBorder(`number` nBorderSize, `number` nR, `number` nG, `number` nB)

 ````lua
 ItemText:SetFontColor(1, 255, 255, 0)
 ````

* <h4 id="LuaItemText_SetFontShadow">SetFontShadow</h4>
Set font shadow.

 > (`void`) ItemText:SetFontShadow(`number` nShadowOffset, `number` nR, `number` nG, `number` nB)

 ````lua
 ItemText:SetFontShadow(1, 255, 255, 0)
 ````

* <h4 id="LuaItemText_GetFontID">GetFontID</h4>
Get font id.

 > (`number` nFontID) ItemText:GetFontID()

 ````lua
 local nFontID = ItemText:GetFontID()
 ````

* <h4 id="LuaItemText_GetFontColor">GetFontColor</h4>
Get font color.

 > (`number` nR, `number` nG, `number` nB) ItemText:GetFontColor()

 ````lua
 local nR, nG, nB = ItemText:GetFontColor()
 ````

* <h4 id="LuaItemText_GetFontBoder">GetFontBoder</h4>
Get font border.

 > (`number` nBorderSize, `number` nR, `number` nG, `number` nB) ItemText:GetFontBoder()

 ````lua
 local nBorderSize, nR, nG, nB = ItemText:GetFontBoder()
 ````

* <h4 id="LuaItemText_GetFontProjection">GetFontProjection</h4>
Get font shadow. (I don't know why this api is not named as `GetFontShadow`).

 > (`number` nShadowOffset, `number` nR, `number` nG, `number` nB) ItemText:GetFontProjection()

 ````lua
 local nShadowOffset, nR, nG, nB = ItemText:GetFontProjection()
 ````

* <h4 id="LuaItemText_GetTextExtent">GetTextExtent</h4>
Get the width and height of the inner text from offset 0 to `nOffset`. If `nOffset` equals with -1, the size of all text will be returned.

 > (`number` nW, `number` nH) ItemText:GetTextExtent([`number` nOffset])

 ````lua
 local nW, nH = ItemText:GetTextExtent() -- Get all text size
 local nW, nH = ItemText:GetTextExtent(3) -- Get text size from offset zero to three
 ````

* <h4 id="LuaItemText_GetTextPosExtent">GetTextPosExtent</h4>
Get the character offset of its inner text from a position offset (`nOffset`). If `nOffset` is not given, the count of all text will be returned.

 > (`number` nOffset) ItemText:GetTextPosExtent([`number` nPosX])

 ````lua
 local nCount = ItemText:GetTextPosExtent()     -- Get the count of all of the text.
 local nOffset = ItemText:GetTextPosExtent(80)  -- Get the count of the text from offset zero to offset 80 pixels.
 ````
