# DocuSign_eSign::EmailAddress

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**anchor_case_sensitive** | **String** | When set to **true**, the anchor string does not consider case when matching strings in the document. The default value is **true**. | [optional] 
**anchor_horizontal_alignment** | **String** | Specifies the alignment of anchor tabs with anchor strings. Possible values are **left** or **right**. The default value is **left**. | [optional] 
**anchor_ignore_if_not_present** | **String** | When set to **true**, this tab is ignored if anchorString is not found in the document. | [optional] 
**anchor_match_whole_word** | **String** | When set to **true**, the anchor string in this tab matches whole words only (strings embedded in other strings are ignored.) The default value is **true**. | [optional] 
**anchor_string** | **String** | Anchor text information for a radio button. | [optional] 
**anchor_units** | **String** | Specifies units of the X and Y offset. Units could be pixels, millimeters, centimeters, or inches. | [optional] 
**anchor_x_offset** | **String** | Specifies the X axis location of the tab, in achorUnits, relative to the anchorString. | [optional] 
**anchor_y_offset** | **String** | Specifies the Y axis location of the tab, in achorUnits, relative to the anchorString. | [optional] 
**bold** | **String** | When set to **true**, the information in the tab is bold. | [optional] 
**conditional_parent_label** | **String** | For conditional fields this is the TabLabel of the parent tab that controls this tab&#39;s visibility. | [optional] 
**conditional_parent_value** | **String** | For conditional fields, this is the value of the parent tab that controls the tab&#39;s visibility.  If the parent tab is a Checkbox, Radio button, Optional Signature, or Optional Initial use \&quot;on\&quot; as the value to show that the parent tab is active.  | [optional] 
**custom_tab_id** | **String** | The DocuSign generated custom tab ID for the custom tab to be applied. This can only be used when adding new tabs for a recipient. When used, the new tab inherits all the custom tab properties. | [optional] 
**document_id** | **String** | Specifies the document ID number that the tab is placed on. This must refer to an existing Document&#39;s ID attribute. | [optional] 
**error_details** | [**ErrorDetails**](ErrorDetails.md) |  | [optional] 
**font** | **String** | The font to be used for the tab value. Supported Fonts: Arial, Arial, ArialNarrow, Calibri, CourierNew, Garamond, Georgia, Helvetica,   LucidaConsole, Tahoma, TimesNewRoman, Trebuchet, Verdana, MSGothic, MSMincho, Default. | [optional] 
**font_color** | **String** | The font color used for the information in the tab.  Possible values are: Black, BrightBlue, BrightRed, DarkGreen, DarkRed, Gold, Green, NavyBlue, Purple, or White. | [optional] 
**font_size** | **String** | The font size used for the information in the tab.  Possible values are: Size7, Size8, Size9, Size10, Size11, Size12, Size14, Size16, Size18, Size20, Size22, Size24, Size26, Size28, Size36, Size48, or Size72. | [optional] 
**italic** | **String** | When set to **true**, the information in the tab is italic. | [optional] 
**merge_field** | [**MergeField**](MergeField.md) |  | [optional] 
**name** | **String** |  | [optional] 
**page_number** | **String** | Specifies the page number on which the tab is located. | [optional] 
**recipient_id** | **String** | Unique for the recipient. It is used by the tab element to indicate which recipient is to sign the Document. | [optional] 
**status** | **String** | Indicates the envelope status. Valid values are:  * sent - The envelope is sent to the recipients.  * created - The envelope is saved as a draft and can be modified and sent later. | [optional] 
**tab_id** | **String** | The unique identifier for the tab. The tabid can be retrieved with the [ML:GET call].      | [optional] 
**tab_label** | **String** | The label string associated with the tab. | [optional] 
**tab_order** | **String** |  | [optional] 
**template_locked** | **String** | When set to **true**, the sender cannot change any attributes of the recipient. Used only when working with template recipients.  | [optional] 
**template_required** | **String** | When set to **true**, the sender may not remove the recipient. Used only when working with template recipients. | [optional] 
**underline** | **String** | When set to **true**, the information in the tab is underlined. | [optional] 
**x_position** | **String** | This indicates the horizontal offset of the object on the page. DocuSign uses 72 DPI when determining position. | [optional] 
**y_position** | **String** | This indicates the vertical offset of the object on the page. DocuSign uses 72 DPI when determining position. | [optional] 


