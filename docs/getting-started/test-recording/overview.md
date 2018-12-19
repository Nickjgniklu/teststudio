---
title: Overview
page_title: Overview
description: "Test Studio is an innovative and easy-to-use automated web, WPF and load testing solution. Test Studio tests support essential technologies like ASP.NET AJAX, Silverlight, PHP and MVC. HTML5, Testing framework, functional testing, performance testing, load testing, exploratory testing, manual testing."
previous_url: /user-guide/recording-tests.aspx, /user-guide/recording-tests
position: 0
---
# Test Recording #

> Once a recording session is started **do not start another instance of the same browser** until the session is finished! 

There are two ways to initiate recording. You can either launch a new browser instance with the recording toolbar attached, or you can attach the recording toolbar to an existing browser instance (IE only or WPF application).

## **2016 R3 Version and Later** ##

## Launch New Recording Browser ##

1.&nbsp;  Click the **Record** button or press **CTRL+R**.

<table id=no-table>
	<tr>
		<td>![Test Studio][10] <br><br>**Standalone version**</td>
		<td>![VS][11] <br><br>**VS plugin**</td>
	</tr>
<table>

2.&nbsp; Type the URL you want to navigate to, select the recording browser and press Enter / Record button. You can choose a URL from your recent URLs.

**Note**: Selecting the recording browser will be skipped if you have already set a preferred browser from the <a href="/getting-started/test-execution/quick-execution" target="_blank">Web ribbon</a>.

![Choose browser][12] 

If you enable **Save my choice for the future** or you have set a preferred browser from the <a href="/getting-started/test-execution/quick-execution" target="_blank">Web ribbon</a> the Record button in <a href="http://www.telerik.com/teststudio" target="_blank">Test Studio</a> Standalone will display the icon for the default browser. 

![Choose preferred browser][13]

3.&nbsp; A recording step is added to the Steps pane and the recorder is attached to the browser.

![Attached recorder][14]

## Attach to Existing Instance (IE only) ##

Click the drop-down arrow on the **Record** button to see a list of available IE browser instances or WPF applications. Select one to attach the recorder to that instance.

![Attache to existing instance][15]

## **2016 R2 Version and Lower** ##

## Launch New Recording Browser ##

1.&nbsp; Click the __Record__ button or press __CTRL+R__.
	
<table id=no-table>
	<tr>
		<td>![Test Studio][1] <br><br>**Standalone version**</td>
		<td>![VS][2] <br><br>**VS plugin**</td>
	</tr>
<table>

2.&nbsp; Choose the recording browser.

![Choose browser][3]

Note: As of the 2014.4.1211 version Safari cannot be used for test recording.

If you enable __Save my choice for the future__, the Record button in <a href="http://www.telerik.com/teststudio" target="_blank">Test Studio</a> Standalone will display the icon for the default browser.

![Choose browser][4]

You can select a different recording browser later from the __Record__ button drop-down.

<table id="no-table">
	<tr>
		<td>![Test Studio][5] <br><br>**Standalone version**</td>
		<td>![VS][6] <br><br>**VS plugin**</td>
	</tr>
<table>

3.&nbsp; Enter a URL and press Enter/Start Recording button. A recording step is added to the Steps pane and the recorder is attached to the browser.

![Start recording][7]

![Attaching the recorder][8]

## Attach to Existing Instance ##

Click the drop-down arrow on the __Record__ button to see a list of available browser instances or WPF applications. Select one to attach the recorder to that instance.

![Attaching the recorder][9]

> You cannot connect to an existing Silverlight Out-of-Browser application for Out-of-Browser tests.

To end recording, simply close the IE window or WPF application that has the recording toolbar attached

4.&nbsp; **Compare Mode** determines which mode to use when adding a page node to the Elements Explorer. Compare Mode can be checked against the page's Title or one of multiple settings that look at various parts of a URL. Please see <a href="/features/project-settings/recording-options#elements-page-compare-mode" target="_blank">this article</a> for more information.

![CompareMode][13]

## See also ##

* <a href="/features/project-settings/browsers" target="_blank">Calibrate Browsers</a>

[1]: /img/getting-started/test-recording/overview/fig1.png
[2]: /img/getting-started/test-recording/overview/fig2.png
[3]: /img/getting-started/test-recording/overview/fig3.png
[4]: /img/getting-started/test-recording/overview/fig4.png
[5]: /img/getting-started/test-recording/overview/fig5.png
[6]: /img/getting-started/test-recording/overview/fig6.png
[7]: /img/getting-started/test-recording/overview/fig7.png
[8]: /img/getting-started/test-recording/overview/fig8.png
[9]: /img/getting-started/test-recording/overview/fig9.png
[13]: /img/getting-started/test-execution/quick-execution/fig13.png
[10]: /img/getting-started/test-recording/overview/fig10.png
[11]: /img/getting-started/test-recording/overview/fig11.png
[12]: /img/getting-started/test-recording/overview/fig12.png
[13]: /img/getting-started/test-recording/overview/fig13.png
[14]: /img/getting-started/test-recording/overview/fig14.png
[15]: /img/getting-started/test-recording/overview/fig15.png