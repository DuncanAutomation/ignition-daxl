
# DAXL: The Duncan Automation XL Spreadsheet Tool

## [GET THE DOCS ON THE WIKI](../ignition-daxl/wiki)

### Professional Spreadsheet Integration for Ignition by Inductive Automation

Bridging the gap between the plant floor and the front office shouldn't mean wrestling with complex Java libraries.
DAXL (Duncan Automation XL Spreadsheet Tool) is a purpose-built module for Ignition that brings robust Excel and CSV manipulation into the Jython scripting environment.

Built on the industry-standard Apache POI framework, DAXL provides a reliable, structured way to integrate spreadsheet data into your SCADA projects without the boilerplate overhead of manual library management.

### Built for the Ignition Developer

Integrating spreadsheets into a live industrial environment requires more than just a "save" button. DAXL provides the granular control needed for production-grade scripts:

Native Apache POI Support: Fully compatible with .xlsx and .xls formats. If Apache POI can build it, DAXL can handle it—from multi-sheet workbooks to specific cell formatting.
Structured Jython Toolset: DAXL adds a dedicated suite of functions to the system.dast scope, making your scripts more readable, maintainable, and easier for other integrators to follow.
Bidirectional Data Translation:
    From Spreadsheet to SCADA: Efficiently parse complex workbooks and map data directly into Ignition Datasets for use in Perspective, Vision, or SQL updates.
    From SCADA to Spreadsheet: Extract data from your tags, databases, or UI components and compile them into professional-grade spreadsheets for external stakeholders.
Environment Compatibility: Designed to function seamlessly across the Gateway, Designer, and Client scopes, ensuring your reporting and data-entry logic works exactly where you need it.

#### Workbook Tools

* system.daxl.workbook.uploadWorkbook
* system.daxl.workbook.downloadWorkbook
* system.daxl.workbook.openWorkbook
* system.daxl.workbook.saveWorkbook
* system.daxl.workbook.newWorkbook

#### Sheet Tools

* system.daxl.sheet.getSheetCount
* system.daxl.sheet.getSheetNames
* system.daxl.sheet.appendSheet
* system.daxl.sheet.insertSheet
* system.daxl.sheet.copySheet
* system.daxl.sheet.moveSheet
* system.daxl.sheet.renameSheet
* system.daxl.sheet.deleteSheet


#### Dataset Tools

* system.daxl.dataset.datasetToSheet
* system.daxl.dataset.datasetFromSheet
* system.daxl.dataset.datasetAppendFromSheet

#### Content Tools

* system.daxl.content.appendRow
* system.daxl.content.insertRow
* system.daxl.content.getCell
* system.daxl.content.setCell
* system.daxl.content.*



### Engineered for Reliability

Don't waste billable hours debugging raw Java file streams or managing external .jar files. DAXL provides a stable, supported framework that lets you focus on the logic of your application rather than the mechanics of the file format.

