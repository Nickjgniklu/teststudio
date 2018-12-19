---
title: KendoUI duplicate elements
page_title: KendoUI duplicate elements
description: "Test Studio is an innovative and easy-to-use automated web, WPF and load testing solution. Test Studio tests support essential technologies like ASP.NET AJAX, Silverlight, PHP and MVC. HTML5, Testing framework, functional testing, performance testing, load testing, exploratory testing, manual testing."
position: 1
---
#KendoUI duplicate elements due to new find logic#

We have changed the element's find logic generated by the recorder (IE only, translators dependent) when recording over KendoUI widgets. This is to ensure reliable find logic for solid playback experience.

This will result in separate elements appearing in the Elements Explorer as shown below. 

![Elemets][1]

Please note that you can leave the elements as they are, without taking extra actions. If you find having multiple elements in your project you can always merge elements, having the old elements to point to the newly recorded one using the find expression builder.

The new logic includes a list of find clauses over the unique class attribute of Kendo widgets. It may also automatically build chained find expressions (for sub elements of widgets).
A new GroupIndex clause is added so that the playback can find the exact instance in the HTML in case of multiple of the same type.

Please find examples below of the same element recorded with the old find logic and the new one (see the highlighted parts).

Old find logic:

![Old find logic][2]

New Find Logic:

![New find logic][3]

Please note that you will get inconsistent experience recording in IE vs. non-IE. This is due to missing KendoUI translators in Chrome/Firefox/Safari recorder.

[1]: /img/knowledge-base/test-recording-kb/kendoui-duplicate-elements/fig1.png
[2]: /img/knowledge-base/test-recording-kb/kendoui-duplicate-elements/fig2.png
[3]: /img/knowledge-base/test-recording-kb/kendoui-duplicate-elements/fig3.png