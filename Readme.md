<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128569646/24.2.1%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4084)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->

# Chart for WPF - How to Customize the Appearance of a Series Tooltip

This example demonstrates how to change the appearance  of a series tooltip with its template. Create a `System.Windows.DataTemplate` object that specifies the appearance of series tooltips and assign it to the [ToolTipSeriesTemplate](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.Series.ToolTipSeriesTemplate) property. Note that before the tooltip customization, you need to set the [ChartControl.ToolTipEnabled](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.ChartControl.ToolTipEnabled) and [ToolTipOptions.ShowForSeries](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.ToolTipOptions.ShowForSeries) properties to show the tooltip for a series. 
Specify a display name for each series displayed on the tooltip with the [Series.DisplayName](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.Series.DisplayName) property. 

## Files to Review 

* [MainWindow.xaml](./CS/ToolTipSeriesTemplate/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/ToolTipSeriesTemplate/MainWindow.xaml))

## Documentation

- [Tooltip](https://docs.devexpress.com/WPF/11975/controls-and-libraries/charts-suite/chart-control/tooltip-and-crosshair-cursor/tooltip)



<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-chart-customize-the-appearance-of-a-series-tooltip&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-chart-customize-the-appearance-of-a-series-tooltip&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
