---
title: Styling
page_title: Styling
position: 7
slug: list-picker-styling
---

# Styling

List Picker for Xamarin provides the followind Style properties for customizing its look:

* **SelectedItemStyle**(**):
* **SelectionHighlightStyle**(**):
* **SelectorSettings**(*Telerik.XamarinForms.Input.PickerPopupSelectorSettings*):

Using the SelectorSettings property of the RadPickerBase class, you could style the dialog(popup) through the following properties:

* **PopupViewStyle**(of type *Style* with target type is **telerikInput:PickerPopupContentView**):
* **HeaderStyle**(of type *Style* with target type is **telerikInput:PickerPopupHeaderView**):
* **HeaderLabelStyle**(of type *Style* with target type is **Label**):
* **FooterStyle**(of type *Style* with target type is **telerikInput:PickerPopupFooterView**):
* **AcceptButtonStyle**(of type *Style* with target type is **Button**):
* **CancelButtonStyle**(of type *Style* with target type is **Button**):

The SelectorSetting also provides the following properties for popup customization:

* **PopupOutsideBackgroundColor**(*Xamarin.Forms.Color*): Defines the color outside of the popup.
* **HeaderLabelText**(*string*): Specifies the text visualized in the popup header.
* **AcceptButtonText**(*string*): Defines the text visualized for the accept button. By default the text is *OK*.
* **CancelButtonText**(*string*): Defines the text visualized for the cancel button. By default the text is *Cancel*. 

>important A sample Styling example can be found in the ListPicker/Features folder of the [SDK Samples Browser application]({%slug developer-focused-examples%}).

## See Also

- [Looping]({%slug list-picker-looping%})
- [Templates]({%slug list-picker-templates%})