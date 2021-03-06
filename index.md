
<!-- DOCTYPE html -->
<html>
<head>
<title>website</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<style type="text/css">
/* GitHub stylesheet for MarkdownPad (http://markdownpad.com) */
/* Author: Nicolas Hery - http://nicolashery.com */
/* Version: b13fe65ca28d2e568c6ed5d7f06581183df8f2ff */
/* Source: https://github.com/nicolahery/markdownpad-github */

/* RESET
=============================================================================*/

html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, menu, nav, output, ruby, section, summary, time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
}

/* BODY
=============================================================================*/

body {
  font-family: Helvetica, arial, freesans, clean, sans-serif;
  font-size: 14px;
  line-height: 1.6;
  color: #333;
  background-color: #fff;
  padding: 20px;
  max-width: 960px;
  margin: 0 auto;
}

body>*:first-child {
  margin-top: 0 !important;
}

body>*:last-child {
  margin-bottom: 0 !important;
}

/* BLOCKS
=============================================================================*/

p, blockquote, ul, ol, dl, table, pre {
  margin: 15px 0;
}

/* HEADERS
=============================================================================*/

h1, h2, h3, h4, h5, h6 {
  margin: 20px 0 10px;
  padding: 0;
  font-weight: bold;
  -webkit-font-smoothing: antialiased;
}

h1 tt, h1 code, h2 tt, h2 code, h3 tt, h3 code, h4 tt, h4 code, h5 tt, h5 code, h6 tt, h6 code {
  font-size: inherit;
}

h1 {
  font-size: 28px;
  color: #000;
}

h2 {
  font-size: 24px;
  border-bottom: 1px solid #ccc;
  color: #000;
}
<!-- this is the one for paper titles -->

h3 {
  font-size: 10px;
}

h4 {
  font-size: 16px;
}

h5 {
  font-size: 14px;
}

h6 {
  color: #777;
  font-size: 14px;
}

body>h2:first-child, body>h1:first-child, body>h1:first-child+h2, body>h3:first-child, body>h4:first-child, body>h5:first-child, body>h6:first-child {
  margin-top: 0;
  padding-top: 0;
}

a:first-child h1, a:first-child h2, a:first-child h3, a:first-child h4, a:first-child h5, a:first-child h6 {
  margin-top: 0;
  padding-top: 0;
}

h1+p, h2+p, h3+p, h4+p, h5+p, h6+p {
  margin-top: 10px;
}

/* LINKS
=============================================================================*/

a {
  color: #4183C4;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* LISTS
=============================================================================*/

ul, ol {
  padding-left: 30px;
}

ul li > :first-child, 
ol li > :first-child, 
ul li ul:first-of-type, 
ol li ol:first-of-type, 
ul li ol:first-of-type, 
ol li ul:first-of-type {
  margin-top: 0px;
}

ul ul, ul ol, ol ol, ol ul {
  margin-bottom: 0;
}

dl {
  padding: 0;
}

dl dt {
  font-size: 14px;
  font-weight: bold;
  font-style: italic;
  padding: 0;
  margin: 15px 0 5px;
}

dl dt:first-child {
  padding: 0;
}

dl dt>:first-child {
  margin-top: 0px;
}

dl dt>:last-child {
  margin-bottom: 0px;
}

dl dd {
  margin: 0 0 15px;
  padding: 0 15px;
}

dl dd>:first-child {
  margin-top: 0px;
}

dl dd>:last-child {
  margin-bottom: 0px;
}

/* CODE
=============================================================================*/

pre, code, tt {
  font-size: 12px;
  font-family: Consolas, "Liberation Mono", Courier, monospace;
}

code, tt {
  margin: 0 0px;
  padding: 0px 0px;
  white-space: nowrap;
  border: 1px solid #eaeaea;
  background-color: #f8f8f8;
  border-radius: 3px;
}

pre>code {
  margin: 0;
  padding: 0;
  white-space: pre;
  border: none;
  background: transparent;
}

pre {
  background-color: #f8f8f8;
  border: 1px solid #ccc;
  font-size: 13px;
  line-height: 19px;
  overflow: auto;
  padding: 6px 10px;
  border-radius: 3px;
}

pre code, pre tt {
  background-color: transparent;
  border: none;
}

kbd {
    -moz-border-bottom-colors: none;
    -moz-border-left-colors: none;
    -moz-border-right-colors: none;
    -moz-border-top-colors: none;
    background-color: #DDDDDD;
    background-image: linear-gradient(#F1F1F1, #DDDDDD);
    background-repeat: repeat-x;
    border-color: #DDDDDD #CCCCCC #CCCCCC #DDDDDD;
    border-image: none;
    border-radius: 2px 2px 2px 2px;
    border-style: solid;
    border-width: 1px;
    font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
    line-height: 10px;
    padding: 1px 4px;
}

/* QUOTES
=============================================================================*/

blockquote {
  border-left: 4px solid #DDD;
  padding: 0 15px;
  color: #777;
}

blockquote>:first-child {
  margin-top: 0px;
}

blockquote>:last-child {
  margin-bottom: 0px;
}

/* HORIZONTAL RULES
=============================================================================*/

hr {
  clear: both;
  margin: 15px 0;
  height: 0px;
  overflow: hidden;
  border: none;
  background: transparent;
  border-bottom: 4px solid #ddd;
  padding: 0;
}

/* TABLES
=============================================================================*/

table th {
  font-weight: bold;
}

table th, table td {
  border: 1px solid #ccc;
  padding: 6px 13px;
}

table tr {
  border-top: 0px solid #ccc;
  background-color: #fff;
}

table tr:nth-child(2n) {
  background-color: #f8f8f8;
}

/* IMAGES
=============================================================================*/



img {
  max-width: 100%
}
</style>
</head>
<body>


<table cellspacing="0" cellpadding="0">
    <tr>
        <td><img src="https://dl.dropboxusercontent.com/u/9404362/website/files/DSC_0390.jpg" /></td>
<td>
<h1>Jacopo Ponticelli</h1> 
<h3>Associate Professor of Finance</h3>

Kellogg School of Management, Northwestern University <br />
Global Hub, Office 4485 <br />
2211 Campus Dr, Evanston, IL 60208 <br />
email: jacopo.ponticelli@kellogg.northwestern.edu <br />
	<a href="https://dl.dropboxusercontent.com/u/9404362/website/files/ponticelli_cv.pdf">CV</a> <a href="https://scholar.google.com/citations?user=BkrOTNgAAAAJ">GoogleScholar</a> <a href="https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=1695706">SSRN</a> 

</td>
    </tr>
</table>

<!--
<h3>Associate Professor of Finance</h3>
<p>Kellogg School of Management, Northwestern University <br />
Global Hub, Office 4485 <br />
2211 Campus Dr, Evanston, IL 60208 <br />
email: jacopo.ponticelli@kellogg.northwestern.edu <br />
-->




<h2>Publications</h2></p>



<b>Court Enforcement, Bank Loans and Firm Investment: Evidence from a Bankruptcy Reform in Brazil </b> <br />
(with Leonardo S. Alencar)<br />
<i> Quarterly Journal of Economics</i>, 131(3): 1365-1413, 2016.<br />
[<a href="https://dl.dropboxusercontent.com/u/9404362/website/files/papers/bankruptcy-qje-manuscript.pdf">Paper</a>] [<a href="https://doi.org/10.1093/qje/qjw015">doi</a>]   [<a href="https://dl.dropboxusercontent.com/u/9404362/website/files/papers/bankruptcy-qje-onlineappendix.pdf">Web Appendix</a>]
[Coverage: <a href="http://www1.folha.uol.com.br/ilustrissima/2016/12/1841866-as-amarras-para-o-crescimento-da-economia-brasileira.shtml">Folha de Sao Paulo</a>]<br />
Central Bank of Brazil - Best Working Paper Award 2017 (First Prize) <br /> </p>
<!-- <a href="https://www.bcb.gov.br/pec/wps/docs/Resultado_Premio_2017.pdf"></a>] -->


<b>Agricultural Productivity and Structural Transformation: Evidence from Brazil </b> <br />
(with <a href="http://www.cemfi.es/~bustos/">Paula Bustos</a> and Bruno Caprettini)<br />
<i> American Economic Review</i>, 106(6): 1320-1365, 2016.<br />
[<a href="https://dl.dropboxusercontent.com/u/9404362/website/files/papers/apst-aer-manuscript.pdf">Paper</a>]  [<a href="http://dx.doi.org/10.1257/aer.20131061">doi</a>]   [<a href="https://dl.dropboxusercontent.com/u/9404362/website/files/papers/apst-aer-onlineappendix.pdf">Web Appendix</a>] [<a href="https://dl.dropboxusercontent.com/u/9404362/website/files/papers/20131061_data.zip">Replication Files</a>] [Coverage: <a href="http://focus.barcelonagse.eu/agricultural-productivity-favor-industrialization/">BGSE Focus</a>]<br />
</p>







<h2>Working Papers </h2>

<b>Capital Accumulation and Structural Transformation</b> <br />
(with <a href="http://www.cemfi.es/~bustos/">Paula Bustos</a> and Gabriel Garber)<br />
[<a href="https://dx.doi.org/10.2139/ssrn.2867510">Paper</a> new version under approval of BCB] </p>


<b>Credit Allocation under Economic Stimulus: Evidence from China</b> <br />
(with <a href="">Will Cong</a>)<br />
[<a href="https://dx.doi.org/10.2139/ssrn.2862101">Paper</a> version: June 2017] </p>

<!-- Haoyu Gao and Xiaogang Yang -->
<b>Caught with the Hand in the Cookie Jar: Firm Growth and Labor Reallocation after Exposure of Corrupt Practices</b> <br />
(with <a href="">Spyros Lagaras</a> and <a href="">Margarita Tsoutsoura</a>)<br />
[<a href="https://ssrn.com/abstract=2929625">Paper</a> version: March 2017] </p>


<b>Austerity and Anarchy: Budget Cuts and Social Unrest in Europe, 1919-2008</b> <br />
(with <a href="">Joachim Voth</a>)<br />
[<a href="https://dx.doi.org/10.2139/ssrn.1899287">Paper</a> version: March 2017] </p>



</body>
</html>

