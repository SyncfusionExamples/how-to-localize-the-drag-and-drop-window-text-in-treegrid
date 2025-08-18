# How to localize the drag and drop window text in treegrid?

This example illustrates how to localize the drag and drop window text in [WPF TreeGrid](https://www.syncfusion.com/wpf-controls/treegrid) and [UWP TreeGrid](https://www.syncfusion.com/uwp-ui-controls/treegrid).

To localize the TreeGrid, drag and drop window based on CurrentUICulture using resource files, follow the below steps.

1. Create new folder and named as `Resources` in your application. 

2. Add the default resource file of treegrid into `Resources` folder.

3. Right-click on the `Resources` folder, select Add and then NewItem.

4. In Add New Item wizard, select the Resource File option and name the filename as Syncfusion.SfGrid.WPF.<Culture_Name>.resx for WPF and Syncfusion.SfGrid.UWP.Resources.<Culture_Name>.resw for UWP. For example, you have to give name as `Syncfusion.SfGrid.WPF.de.resx` / `Syncfusion.SfGrid.UWP.Resources.de.resw` for German culture.

5. The culture name that indicates the name of language and country.

6. Add the Name/Value pair in Resource Designer of `Syncfusion.SfGrid.WPF.de.resx` / `Syncfusion.SfGrid.UWP.Resources.de.resw` file and change its corresponding value to corresponding culture.