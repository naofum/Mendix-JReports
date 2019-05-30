# Mendix-JReports

The **JReports** can be used to create PDF file easily using JasperReports library (https://community.jaspersoft.com/project/jasperreports-library).

This module supports:

- Create PDF/Docx/Xlsx/Pptx/CSV file


## Dependencies
* none


## Installation
* Import the module **JReports** in your project (from the Mendix AppStore or by downloading and exporting the module from this project)

- Add JFConfiguration_Overview and JRConfiguration_Overview to your navigation. You can customize it.
- Upload xxx.jasper file in the JFConfiguration page. You can create and compile .jrxml file to .jasper file by Jaspersoft Studio etc.
- Run IVK_RegisterSampleForm microflow then two sample forms will be created.
- Use or customize generatePDF java action and generate PDF file.


## Configuration
- Fonts: when you want to add another fonts, export font file as jar by Jaspersoft Studio and place into userlib directory
- Forms: sample form is included in userlib/sampleforms.jar


## License
- This module licensed under the GPL v3+ (see. https://www.gnu.org/licenses/gpl-3.0.en.html) or LGPL 3
- This module contains JasperReports library which is licensed under the LGPL (see. https://www.gnu.org/licenses/lgpl-3.0.en.html)
- This module contains iText 2.1.7 library which is licensed under the MPL/GPL
- This module contains Apache Commons library which is licensed under the Apache License 2.0
- This module contains IPA fonts which is licensed under the IPA Font License


## Developers notes
* Open the JReports.mpr in the Mendix Modeler.
* Use *Deploy for Eclipse* option (F6) and you can then import this module as an Eclipse project to the Eclipse IDE.


## Version history
- 1.0.0 release
- 0.1 first functions for JReports implemented
