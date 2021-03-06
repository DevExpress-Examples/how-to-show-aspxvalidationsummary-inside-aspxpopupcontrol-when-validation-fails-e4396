<!-- default file list -->
*Files to look at*:

* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
<!-- default file list end -->
# How to show ASPxValidationSummary inside ASPxPopupControl when validation fails
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e4396/)**
<!-- run online end -->


<p>This example illustrates how to show ASPxValidationSummary inside ASPxPopupControl when validation fails.<br />
- Define ASPxValidationSummary inside ASPxPopupControl;<br />
- Add the invisible ASPxGlobalEvents component onto a form;<br />
- Handle the client-side <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxGlobalEventsScriptsASPxClientGlobalEvents_ValidationCompletedtopic"><u>ASPxClientGlobalEvents.ValidationCompleted</u></a> event;<br />
- If validation fails (<a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxGlobalEventsScriptsASPxClientValidationCompletedEventArgs_isValidtopic"><u>e.isValid</u></a> is false), show the popup control via any of the client-side <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxPopupControlScriptsASPxClientPopupControlMembersTopicAll"><u>ASPxClientPopupControl.Show***</u></a> methods.</p>

<br/>


