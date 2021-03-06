<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/WindowsApplication1/Form1.cs) (VB: [Form1.vb](./VB/WindowsApplication1/Form1.vb))
<!-- default file list end -->
# How to customize the GridView's column filter dropdown to provide a custom list of filters


<p>Basically, the filter dropdown shows all unique values of its column (in List and CheckedList <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraGridColumnsFilterPopupModeEnumtopic">mode</a>). Suppose that you have a DateTime column, and want to show all dates, belonging to a certain year. In this instance, the GridView should be filtered by a date range rather than by a particular date.<br />
To accomplish this task, the <a href="https://docs.devexpress.com/WindowsForms/DevExpress.XtraGrid.Views.Base.ColumnView.ShowFilterPopupListBox">ColumnView.ShowFilterPopupListBox event</a> is handled in this example, and custom items, containing required filter expressions, are passed to the filter ComboBox.</p><p><strong>See Also:</strong><br />
<a href="http://documentation.devexpress.com/#WindowsForms/CustomDocument994">Filter Dropdown List</a></p>

<br/>


