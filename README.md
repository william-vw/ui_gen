# UI generation from EHR data descriptions

The `rules/` folder contains the N3 rules that generate the UI code.

The `ehr/[spec]` folders contain the EHR artifacts. 

The `ui/[format]` folders contain the UI code snippets.

The `ehr/[spec]/out/[format]` subfolders contain the intermediary and final files generated by the N3 code. 

To try out the generated HTML+RDFa UI files, clone the repository and open the HTML file (called `ui.html`) in the browser. After filling out some values and clicking submit, the generated RDF code should appear in the developer console.

Trying out the generated Yail files is currently a bit more involved - one has to generate an appropriate .zip archive and upload it as an external project to the [Punya instance](punya.appinventor.mit.edu/). Future work involves making this process easier.
