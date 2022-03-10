# nsf-proposal:latex-samples
This is an open source repository for collaboration on samples to use in the Research.gov Proposal Preparation system.  These samples are not policy endorsed documents and are not official templates.  These samples are not tested or supported by the NSF Research.gov development team.  These LaTeX samples were created by a volunteer group of program officers.  Output PDF files were tested on the Research.gov demo site and uploads successfully. Samples were last tested November 2021. All data entered is dummy data. 

For all other help with proposal submission, not related to LaTeX, please visit https://www.research.gov/research-web/content/aboutpsm
Feedback can be given syee@nsf.gov. Please preface title with LaTeX Github

Tips:  
<li>Check the PDF Version of your resulting PDF. PDF version should be 1.5 or higher. </li>
<li>If a PDF produces warnings or errors, experiment with different PDF producers.</li>
<li>Line spacing warnings are prevalent with Arial 10. Increase line spacing or experiment with another PAPPG approved 10 sized font. Remember warnings do not prohibit submission.  </li>
<li>URLS are not permitted in project descriptions. Some PDF conversions will automatically add clickable links to plain text that resemble a link. An example of a package that adds links is the hyperref package. Additional processing may be required to strip out the links from the PDF.</li>
<li>Avoid using a non-standard .cls (class) file which can lead to headers not being recognized or found by the Research.gov compliance tools.  Other options include deleting and retyping the headers in the PDF directly using an Adobe Acrobat PDF editor. 
  </li>

  
<P><P>--------------------
  <P>
<P><B>nsf-sample-1.tex </b>This is a simple project description sample that includes displayed equations, inline equations, graphic insertion, tables, footnotes, and cross-references. this is designed for pdflatex (as opposed to the traditional latex | dvips | ps2pdf chain), and does not use AMS packages. 
<P>
  <B>nsf-sample-1.pdf </B>This is the corresponding PDF for nsf-sample-1.tex
<P>--------------------
  <P>
<B>nsf-sample-2.tex </b> This is a project description sample that uses the AMSLaTeX package. Includes mathematical and physics elements.
  <P>
  <B>nsf-sample-2.pdf </B>This is the corresponding PDF for nsf-sample-2.tex
<P>--------------------
  <P>
<B>nsf-sample-3.tex </b>  This is a sample project description that does not include the AMSLaTeX package. Includes mathematical and physics elements.
    <P>
  <B>nsf-sample-3.pdf </B>This is the corresponding PDF for nsf-sample-3.tex
