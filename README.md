# PEPs: Platform Enhancement Proposals

The archive of Enhancement Proposals for the Natural Capital Project's Science
& Technology Platform.

## Steps for archiving Google Doc PEPs
1) Download google doc as docx
2) Use `pandoc` to convert to md (comments not preserved in this step)
3) Example usage:
  `cat "D8_MFD routing algorithms PEP.docx" | pandoc -o "D8_MFD routing algorithms PEP.md" --from=docx --to=markdown`
4) Manually edit links and images
5) At the top of the markdown PEP add a hyperlink to the original Google Doc PEP using the phrase: "This PEP has been modified from the original PEP Google Doc"
6) Commit and Push to repo

NOTE: We are currently not capturing comments from the Google Docs.

## Archiving format
The markdown PEP should follow the format `pep-xxxx.md` where `xxxx` is the next numbered increment. We have left `0001-0009` to allow for old PEPs to be archived. If there are images or other documents that support a PEP they should go in a corresponding folder.
