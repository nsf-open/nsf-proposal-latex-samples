# nsf-proposal:latex-samples
This is an open-source repository for collaboration on samples to use in the Research.gov Proposal Preparation system.  These samples are not official templates, nor have they been.  These LaTeX samples were created by a volunteer group of NSF program officers.  Output PDF files upload successfully on the Research.gov demo site. Samples were last tested March 2022. All data is dummy data. 

For all other help with proposal submission, not related to LaTeX, please visit https://www.research.gov/research-web/content/aboutpsm or the PAPPG guide https://www.nsf.gov/publications/pub_summ.jsp?ods_key=pappg
<P>
  Send feedback to syee@nsf.gov and please put LaTeX Github in your subject line.

<b>Tips:  </b>
<li>Check the PDF Version of your resulting PDF. PDF version should be 1.5 or higher. </li>

<li>If a PDF produces warnings or errors, experiment with different PDF producers.</li>
<li>Line spacing warnings are prevalent with Arial 10. Increase line spacing or experiment with another PAPPG approved 10 sized font. Remember warnings do not prohibit submission.  </li>
<P>&nbsp;<P>&nbsp;
<b>URLS are found in the Project Description</b>

<li>URLS are not permitted in project descriptions. Some PDF conversions will automatically add clickable links to plain text that resemble a link. An example of a package that adds links is the hyperref package. Additional processing may be required to strip out the links from the PDF.</li>
 <li>  Using images from another PDF source may trigger warnings or error messages.  We recommend converting pictures first to PostScript for images in vector format, then from PostScript back to PDF.  If instead the image is a bitmap, convert to PNG which is supported by the "graphicx" LaTeX package.
 </li>
<P>&nbsp;<P>&nbsp;
<b>Headers are not being recognized:</b>
<li>Recommend using \section*{} for headers. <BR>If using \subsection or \centerline avoid using hard carriage returns after the header ("\\")   </li>
<li>Remove vertical line spacing commands before a header. Using for example "\vspace{-.xxx} before the /section*{header being checked here} will cause errors</li>
  <li>Avoid using a non-standard .cls (class) file which can lead to headers not being recognized or found by the Research.gov compliance tools.  Other options include deleting and retyping the headers in the PDF directly using an Adobe Acrobat PDF editor. 
  </li>
  <li> Avoid loading font encoding packages, they can cause compliance checks to fail. Font encoding packages are mainly to tyespet non-English text and are not needed for most proposals. 
  </li>
<li>Be wary of editing, renaming, or producing files on a Mac. If you have Adobe Reader, and go into document properties, if the PDF Producer is for example "macOS Version ...Quartz PDFContext" the file cannot be read by our PDF parser. This will result in unsearchable PDFs and unrecogizable headers</li>
 <P>&nbsp;<P>&nbsp;
 <b>File is larger than 8.5x11</b>
<li>Remove unnecessary vertical line spacing commands   </li>
<li>Pages in landscape orientation. This also applies to non-LaTeX files. Landscape will be accepted as an orientation in a near release (late summer/early fall 2023)</li>
  
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
