# Code Templates

### Goal

Boost AEM components development

<p align="center">
  <p>Touch UI templates demo<p>
  <img src="misc/demo.gif" alt="Code Templates"/>
</p>


### What is it and how to use it

*Code templates* are list of reusable and parameterized code snippets. The feature is well-known for all developers. You use it every time when you create *loops*/*conditions* in Java classes.

### Template types

 1. [Touch UI](TouchUI/documentation.md) templates

 Provide templates for Touch UI dialogs and widgets which could be used inside the dialog.

 * [AEM Files](ComponentFiles/documentation.md) templates

 Provide basic definition of the AEM component files like: `.content.xml`, `_cq_template.xml`, `_cq_editConfig.xml`.

### How to install

#### IntelliJ

1. Go to the following directory where **code templates** are stored

  * Windows: `<your home directory>\.<product name><version number>\config\templates`

  * Linux: `~/.<product name><version number>/config/templates`

  * OS: `~/Library/Preferences/<product name><version number>/templates`

2. Download the **.xml* containing templates definition file from the repository

* Restart your IDE


#### Eclipse

1. Download the **.xml* containing templates definition file from the repository

* Open your IDE

* Go to `Window > Preferences > XML > XML Files > Editor > Templates`

* Click *Import* button and select the downloaded file

### Change log

 1. Version: 1.0.0 Date: 29.09.2016


  `Touch UI` and `Component Files` provided
