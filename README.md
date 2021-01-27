# JATS-csl

This is a modified version of https://github.com/MartinPaulEve/JATS-CSL and https://github.com/mfenner/pandoc-jats. It allows one to render citeproc references as JATS xml `<element-citation>`-style `<ref>`s; these can then be inserted in the `<back><ref-list>` of a JATS xml document. For more information, see the JATS [documentation on Tagging References](https://jats.nlm.nih.gov/publishing/tag-library/1.3d1/chapter/tag-refs.html#pub-tag-refs).

## Usage

The JATS.csl file can be used with a processor such as [citeproc-js](https://github.com/Juris-M/citeproc-js) or software implementing it, such as [Zotero](https://www.zotero.org/).

The open access journal [Internet Policy Review](https://policyreview.info) uses it as part of its reference workflow.

## Caution

Be careful with special characters – which can't be escaped in with csl. You may have to do some postprocessing on the ouput.

This is work in progress, as-is software! It is probably not suitable for every use case.
