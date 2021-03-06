<!-- default file list -->
*Files to look at*:

* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
<!-- default file list end -->
# ASPxGridView - How to implement select/unselect for all rows in a group row
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e1760/)**
<!-- run online end -->


<p>This example demonstrates how to implement select/unselect for all rows in a group row. This approach works with only one grouped column.</p>
<p>It's possible to implement this behavior starting with the 9.1 version. For more information, please refer to <a href="https://www.devexpress.com/Support/Center/p/S18760">Add client- and server-side methods to obtain rows belonging to a certain group</a>.</p>
<p>First, place ASPxCheckBox and ASPxLabel into the Grid.Templates.GroupRowContent template.<br> <br> Second, set the ASPxCheckBox.Checked property and the client-side ASPxCheckBox.ClientSideEvents.CheckedChanged event in the ASPxGridView.HtmlRowPrepared event handler.</p>
<p>In this example the ASPxLabel.Text is bound in the markup using Two-Way DataBinding.<br><br>MVC version: <a href="https://www.devexpress.com/Support/Center/p/T362032">T362032: GridView - How to implement select/unselect for all rows in a group row</a><br><br><strong>See also<br></strong><a href="https://www.devexpress.com/Support/Center/p/T299266">How to implement select/unselect for all rows in a group row in ASPxGridLookup</a></p>

<br/>


