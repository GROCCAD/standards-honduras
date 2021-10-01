# standards-honduras
Data repository for the controlled vocabularies and curriculum standards for Honduras.



Jurisdiction info
-----------------
The Honduras educational standards (Estándares Educativos Nacionales) are published
by the Secretaría de Educación de Honduras and can be downloaded as PDF documents from the following sites:

- https://www.se.gob.hn/prebasica_descargas/
- https://www.se.gob.hn/basica_descargas/
- http://www.educatrachos.hn/ (use [targeted google search query](https://www.google.com/search?q=site%3Aeducatrachos.hn+Esta%CC%81ndares+filetype%3Apdf&oq=site%3Aeducatrachos.hn+Esta%CC%81ndares+filetype%3Apdf) to find PDFs)
- https://observatorio.upnfm.edu.hn/observatorio/calidad/documentos-calidad-educativa/



Contents
--------
- [`sourcedocuments/`](./sourcedocuments): contains all the standards documents from Honduras freely available online in PDF format
- [`sourcedata/`](./sourcedata): machine-readable source documents (spreadsheets)
  - A sample of digitized standards for one `componente` can be viewed online
    [here](https://docs.google.com/spreadsheets/d/12-cHUPIAy9az2Q8e1JP7vIDY2WgzB0F6AEIv_gVXHR0/edit#gid=0)
- [`terms/`](./terms): controlled vocabularies used in the digitized standards:
  - [`CurriculumElements.yml`](./terms/CurriculumElements.yml): terms describing
    the different "types" of elements within the curriculum standards
  - [`Areas.yml`](./terms/Areas.yml): terms for the academic subjects in Honduras
  - [`Grados.yml`](./terms/Grados.yml): grade levels in Honduras
- [`standards/`](./standards): curriculum standards ROCdata


Digitization notes
------------------
- Manual data entry required but `pdftotext` helps to get started
- Not clear if we have the latest:
  "Estándares Educativos Nacionales (2015)" and
  "Texto Excolar CREE (2018)"


License
-------
All documents in this repo are under copyright © República de Honduras Secretaría de Educación.
The digital representations of terms and standards data in this repository are
for illustrative purposes part of the [ROC data project](https://rocdata.global/)
and should not be considered endorsed or approved by the Secretaría de Educación in any way.
