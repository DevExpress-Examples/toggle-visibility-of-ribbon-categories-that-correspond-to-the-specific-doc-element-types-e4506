<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))
* [Program.cs](./CS/Program.cs) (VB: [Program.vb](./VB/Program.vb))
<!-- default file list end -->
# Toggle visibility of Ribbon categories that correspond to the specific doc element types


<p>This example illustrates how to display/hide the following Ribbon categories depending of the selection location:</p><p>-Table Tools<br />
-Header&Footer Tools<br />
-Picture Tools</p><p>We handle the following events for this purpose:</p><p><a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraRichEditRichEditControl_StartHeaderFooterEditingtopic"><u>RichEditControl.StartHeaderFooterEditing</u></a><br />
<a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraRichEditRichEditControl_FinishHeaderFooterEditingtopic"><u>RichEditControl.FinishHeaderFooterEditing</u></a><br />
<a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraRichEditRichEditControl_SelectionChangedtopic"><u>RichEditControl.SelectionChanged</u></a></p><p>Note that this approach is also illustrated in the "Ribbon UI" demo module, shipped along with the XtraRichEdit Suite (see <a href="http://documentation.devexpress.com/#WindowsForms/CustomDocument9611"><u>Demos in Installation</u></a>). The same approach can be implemented in WPF and SL platforms too (refer to the corresponding demo modules).</p><p><strong>See Also</strong><strong>:</strong><br />
<a href="http://documentation.devexpress.com/#WindowsForms/CustomDocument5812"><u>How to: Create a Simple Word Processor with Ribbon Menu</u></a></p>

<br/>


