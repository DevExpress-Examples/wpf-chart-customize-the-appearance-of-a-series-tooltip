<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/ToolTipSeriesTemplate/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/ToolTipSeriesTemplate/MainWindow.xaml))
<!-- default file list end -->
# How to customize the appearance of a series tooltip


<p>This example demonstrates how to change the appearance  of a series tooltip via its template.</p><p>To do this, you need to create a <strong>System.Windows.DataTemplate</strong> object that specifies the appearance of series tooltips and assign it to the <a href="http://help.devexpress.com/#WPF/DevExpressXpfChartsSeries_ToolTipSeriesTemplatetopic"><u>Series.ToolTipSeriesTemplate</u></a> property. In this example,  this has been done for the first series.</p><p>Note that before the tooltip customization, you need to set the <a href="http://help.devexpress.com/#WPF/DevExpressXpfChartsChartControl_ToolTipEnabledtopic"><u>ChartControl.ToolTipEnabled</u></a> and  <a href="http://help.devexpress.com/#WPF/DevExpressXpfChartsToolTipOptions_ShowForSeriestopic"><u>ToolTipOptions.ShowForSeries</u></a> properties to <strong>true</strong><strong> </strong>to show the  tooltip for a series. <br />
It is also necessary to specify a display name for each series displayed on the tooltip via the <a href="http://help.devexpress.com/#WPF/DevExpressXpfChartsSeries_DisplayNametopic"><u>Series.DisplayName</u></a> property. </p><br />


<br/>


