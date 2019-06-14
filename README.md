# TeachingTipBug

**Describe the bug**
<!-- Please enter a short, clear description of the bug -->
`TeachingTip` do not show when creating in .cs code.

**Steps to reproduce the bug**
<!-- Please provide any required setup and steps to reproduce the behavior -->
Steps to reproduce the behavior:
`<Button x:Name="SaveButton" Content="Save" Tapped="Button_Tapped"/>`

```
        private void Button_Tapped(object sender, Windows.UI.Xaml.Input.TappedRoutedEventArgs e)
        {
            MUXC.TeachingTip tip = new MUXC.TeachingTip();
            tip.Title = "Error";
            tip.Subtitle = "It seems you are not connected to the Internet :(";
            tip.CloseButtonContent = "OK";
            tip.IsLightDismissEnabled = true;
            tip.IsOpen = true;
        }
```

**Version Info**
<!-- Please enter your WinUI NuGet package version, OS version(s), and form factor(s) -->

NuGet package version: 
Microsoft.UI.Xaml 2.1.190606001

<!-- Which Windows versions did you see the issue on? Leave blank if you didn't try that version. -->
| Windows 10 version                  | Saw the problem? |
| :--------------------------------- | :-------------------- |
| Insider Build (xxxxx)              | <!-- Yes/No? -->   |
| May 2019 Update (18362)            |  Yes   |
| October 2018 Update (17763)        | <!-- Yes/No? -->   |
| April 2018 Update (17134)          | <!-- Yes/No? -->   |
| Fall Creators Update (16299)       | <!-- Yes/No? -->   |
| Creators Update (15063)            | <!-- Yes/No? -->   |
| Anniversary Update (14393)         | <!-- Yes/No? -->   |

<!-- Which device form factors did you see the issue on? Leave blank if you didn't try that device. -->
| Device form factor | Saw the problem? |
| :-------------------- | :------------------- |
| Desktop                 |  Yes   |
| Mobile                   | <!-- Yes/No? -->   |
| Xbox                      | <!-- Yes/No? -->   |
| Surface Hub          | <!-- Yes/No? -->    |
| IoT                         | <!-- Yes/No? -->    |

