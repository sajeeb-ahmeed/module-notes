# module-notes

CSS Selectors

Selectors

- ---> all elements
  div---> all div tags
  div,p ---> all divs and paragraphs
  div p ---> paragraphs inside divs
  div > p ---> all p tags, one level deep in div
  div + p ---> p tags immediately after div
  div ~ p ---> p tags preceded by div
  .classname ---> all elements with class
  #idname ---> element with ID
  div.classname ---> divs with certain classname
  div#idname ---> div with certain ID
  #idname \* ---> all elements inside #idname
  Pseudo classes
  a:link ---> link in normal state
  a:active ---> link in clicked state
  a:hover ---> link with mouse over it
  a:visited ---> visited link
  p::after{content:"you";} ---> add content after p
  p::before ---> add content before p
  input:checked ---> checked inputs
  input:disabled ---> disabled inputs
  input:enabled ---> enabled inputs
  input:focus ---> input has focus
  Attribute selectors
  a[target] ---> links with a target attribute
  a[target="_blank"] ---> links which open in new tab
  input[type="button"] ---> specified input type
