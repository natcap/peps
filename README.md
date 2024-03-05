# PEPs: Platform Enhancement Proposals

The archive of Enhancement Proposals for the Natural Capital Project's Science
& Technology Platform.

## PEP index

- **[pep-0010](https://github.com/natcap/peps/blob/main/pep-0010.md)** - Revising SDR Indicators - Complete
- **[pep-0011](https://github.com/natcap/peps/blob/main/pep-0011.md)** - Deprecate the GLOBIO model - Complete
- **[pep-0012](https://github.com/natcap/peps/blob/main/pep-0012.md)** - Supporting both D8 and MFD algorithms in InVEST routed models and tools - In Progress

## Steps for archiving Google Doc PEPs
1) Download google doc as docx
2) Use `pandoc` to convert to md (comments not preserved in this step)
3) Example usage:
  `cat "D8_MFD routing algorithms PEP.docx" | pandoc -o "D8_MFD routing algorithms PEP.md" --from=docx --to=markdown`
4) Manually edit links and images
5) At the top of the markdown PEP add a hyperlink to the original Google Doc PEP using the phrase: "This PEP has been modified from the original PEP Google Doc"
6) Commit and Push to repo
7) Update `PEP index` section in the README

NOTE: We are currently not capturing comments from the Google Docs.

## Archiving format
The markdown PEP should follow the format `pep-xxxx.md` where `xxxx` is the next numbered increment. We have left `0001-0009` to allow for old PEPs to be archived. If there are images or other documents that support a PEP they should go in a corresponding folder.
