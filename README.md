# Annals of Biomedical Engineering Template

This is a LaTeX template for articles to be submitted to [Annals of Biomedical
Engineering (ABME)][abme]. The author instructions are followed as closely as
possible, but you should still read them since they contain
recommendations/requirements pertaining to things other than formatting.


## References

The command `latex makebst` was used to generate the BibTeX style file
(`abme.bst`). The `makebst` tool essentially asks a series of questions about
how you want the references formatted in order to do this. It also outputs
a "transcript" of the session (`abme.dbj`). This file can be (and was) lightly
modified to fine-tune things. It is still not perfect, but the output can be
fixed up if needed (see next paragraph).

As indicated in the template, the submission process is a single-file-only deal
(except figures...go figure), so you'll have to copy the `.bbl` file generated
during document compilation into the document source. I recommend doing this
once you're pretty sure you have included all the references you plan on using
(otherwise it's much easier to grab references from a BibTeX `.bib` file while
writing).


## Disclaimer

This is solely for the purpose of making it easier to prepare a LaTeX document
for submission to ABME. I am in no way affiliated with ABME and this is in no
way an official template. You should read the author instructions on the ABME
website and verify that the document conforms to them before submitting.


[abme]: http://www.springer.com/biomed/journal/10439
