## Hi there 👋

```math
\mmlToken{ms}[fontfamily="
arial;
color:%23FF0000;
background: url(\%68\%74\%74\%70\%73://example.com/image.png);
"]{}

\mmlToken{ms}[fontfamily="
arial;
background: url('data:image/png;base64,iVBORw0KGgo=');
"]{}

\mmlToken{ms}[fontfamily="
arial;
color:\u0023FF0000;
"]{Unicode Text}

\mmlToken{ms}[fontfamily="
arial;
color:&\#x23FF0000;
"]{Entity Encoded Text}

\mmlToken{ms}[fontfamily="
Arial;
COLOR:red;
"]{Case Test}

\mmlToken{ms}[fontfamily="
[type='text'] {
  color: red;
};
"]{Selector Test}

\mmlToken{ms}[fontfamily="
Arial;
<script>alert('XSS')</script>;
"]{Polyglot Test}

\mmlToken{ms}[fontfamily="
Arial;
<scr<script>ipt>color:red;</script>;
"]{Malformed HTML Test}
