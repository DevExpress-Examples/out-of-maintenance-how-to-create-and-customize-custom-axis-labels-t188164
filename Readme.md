<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128569544/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T188164)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/CustomAxisLabel/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/CustomAxisLabel/MainWindow.xaml))
<!-- default file list end -->
# How to create and customize custom axis labels


This example demonstrates how custom axis labels are created and customized in the Chart control. <br /> <br />To add a custom axis label on the chart, create a <a href="https://documentation.devexpress.com/">CustomAxisLabel</a> object and add it to the <a href="https://documentation.devexpress.com/wpf/clsDevExpressXpfChartsCustomAxisLabelCollectiontopic.aspx">CustomAxisLabelCollection</a> returned by the <a href="https://documentation.devexpress.com/">Axis2D.CustomLabels</a>  property. <br /><br />To show the custom label on the X-axis or Y-axis, specify an axis value that corresponds to the label position on an axis (using the <a href="https://documentation.devexpress.com/">CustomAxisLabel.Value </a> property) and to its content (via the <a href="https://documentation.devexpress.com/">CustomAxisLabel.Content</a> property).<br /><br />You can customize custom labels' appearance using the<strong> Foreground</strong>, <strong>FontFamily,</strong>  <strong>FontWeight</strong>, and <strong>FontStyle  </strong>properties for the <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfChartsAxisLabeltopic">AxisLabel</a> object. <br /><br />For more information about custom axis labels, see the <a href="https://documentation.devexpress.com/#WPF/CustomDocument7940">Axis Custom Label</a> topic.

<br/>


