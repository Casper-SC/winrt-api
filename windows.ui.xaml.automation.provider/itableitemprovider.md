---
-api-id: T:Windows.UI.Xaml.Automation.Provider.ITableItemProvider
-api-type: winrt interface
---

<!-- Interface syntax.
public interface ITableItemProvider : 
-->

# Windows.UI.Xaml.Automation.Provider.ITableItemProvider

## -description
Exposes methods and properties to support Microsoft UI Automation client access to child controls of containers that implement [ITableProvider](itableprovider.md). Implement this interface in order to support the capabilities that an automation client requests with a [GetPattern](../windows.ui.xaml.automation.peers/automationpeer_getpattern_2046576749.md) call and [PatternInterface.TableItem](../windows.ui.xaml.automation.peers/patterninterface.md).

## -remarks
This pattern has guidelines and conventions that aren't fully documented here. For more info on what this pattern is for, see [TableItem Control Pattern](https://msdn.microsoft.com/library/e00c7a58-410c-4818-8f61-57ee98527d6e).

[ITableItemProvider](itableitemprovider.md) isn't implemented by any existing Windows Runtime automation peers. The interface exists so that custom control authors can support the automation pattern in a custom control, and implement their automation support using the same Windows Runtime managed or C++ API as they use to define control logic or other automation support.

Use the [TableItemPatternIdentifiers](../windows.ui.xaml.automation/tableitempatternidentifiers.md) if you want to reference the [ITableItemProvider](itableitemprovider.md) pattern properties from control code when you call [RaisePropertyChangedEvent](../windows.ui.xaml.automation.peers/automationpeer_raisepropertychangedevent_715050195.md).

## -examples

## -see-also
[IGridItemProvider](igriditemprovider.md), [ITableProvider](itableprovider.md), [ITableItemProvider (COM interface)](https://msdn.microsoft.com/library/73cba491-1aa6-4bd7-bcd6-95b5d85c9457), [TableItem Control Pattern](https://msdn.microsoft.com/library/e00c7a58-410c-4818-8f61-57ee98527d6e), [Custom automation peers](https://msdn.microsoft.com/library/aa8da53b-fe6e-40ac-9f0a-cb09637c87b4)
