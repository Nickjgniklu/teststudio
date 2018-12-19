---
title: Test Properties (Standalone)
page_title: Test Properties (Standalone)
description: "Test Studio is an innovative and easy-to-use automated web, WPF and load testing solution. Test Studio tests support essential technologies like ASP.NET AJAX, Silverlight, PHP and MVC. HTML5, Testing framework, functional testing, performance testing, load testing, exploratory testing, manual testing."
previous_url: /user-guide/modifying-tests/test-properties.aspx, /user-guide/modifying-tests/test-properties
position: 1
---
# Test Properties (Standalone)

Test Properties reflect the attributes of anything you select in the Project tab, and in some cases allows you to change these properties. For example, if you click a test node in the Project Files Pane, the Name and Path of the test will display as read-only, but other properties like Description, Owner, and Priority allow you to enter values directly.

Go the **Project Tab**, click on a test and the pane to the right will instantly show the details for this very test. Clicking All Test Properties button will show you all test properties or by pressing F4.

![Test Properties][1]

**Attributes**

- Description - description of this test.
- Name* - the name of this test.
- Owner - this test's owner.
- Path* - the test file path relative to the project.
- Priority - this test's priority (default is 0).
- UniqueId - the test case unique identifier generated by Test Studio. 


**Data**

- DataEnabled - whether data driven testing is enabled (if test is bound to a source).
- DataRange - defines a data range to execute within the data source set on a data driven test. Range is 1 based. Format: 'StartRow:EndRow' [i.e. '3:5'] or 'SingleRow' or ':3' (first three) or '3:' (three to end).
- DataType* - the data source type associated with this test.
- DefaultToGrid - when the BuiltInGrid is created in addition to an external data source, if set will default to the BuiltInGrid, else the external source.
- HasBuiltInGrid* - whether a BuiltInGrid is attached to this test.
- InheritParentDataSource - gets or sets whether this data-bound test will inherit the data source from its parent data-bound test.
- IsDataDriven* - whether the test is data driven.
- Source* - the data source bound to this test.


**Execution**


- BrowserType - sets the browser the test executes on. Overrides the Settings.DefaultBrowser.
- DisableDialogMonitoring - whether to disable dialog handling.
- ReuseAppWindow - useful in data-driven execution to define the number of iterations to reuse the application window. By default ('0') keeps the same application open during the entire test run.
- SilverlightEnabled - whether to enable Silverlight automation for this test case.
- StopTestListOnFailure - gets or sets whether to stop test list execution if this test fails.
- WebKitExecutionDelay - explicit commands delay in milliseconds for the WebKit browsers (Safari & Chrome).

**Misc**

- CustomProperty - three user defined values.
- HasCodeBehind* - whether this test has code/script associated with it.
- IsManual - switch between manual and automated to designate whether to execute the test with the manual or automated test runner.
- QcFilePath - the file path for this test on the QC server if it is connected to one.
- QcId - the ID provided to this test by the QC server if it is connected to one.
- QcVersionStamp - the version of the QC server if it is connected to one.

> *Indicates field is read-only.

<br/>

> Name, Path, Owner, Priority, and CustomProperty can be used as filtering criteria for Rules in <a href="/getting-started/test-execution/test-lists-standalone#dynamic-test-list" target="_blank">Dynamic Test Lists</a>.

[1]: /img/features/test-maintenance/test-properties-standalone/fig1.png