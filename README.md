# uscode-guide
A guide to using https://github.com/publicdocs/uscode

Use of this project is subject to the [NOTICE](NOTICE).

## Basic How-To
Each component of a title all the way down to a section has its own Markdown file, which is similar to plain text, but with some formatting.

To see how a title has changed over time, compare it across two different release points.  Each release point that alters a title non-trivially has its own Git commit, and another, single, Git commit for a release point combines all the changes to titles that had trivial modifications.

When an XML file is corrupt or cannot be parsed, we skip the entire title for that release point.  If an XML file requires a minor correction to be valid, our software (see below) will make the correction and continue processing the title.  See the title's README.md file to see if there were any major issues in generating the title.

The conversion from the format used by the original government data to this project is __not__ perfect, so you should not use the project for official purposes or legal research.
