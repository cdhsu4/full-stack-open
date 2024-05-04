```mermaid
  sequenceDiagram;
    browser-->server: PUSH new Form data entry to server array, do NOT fetch again via e.preventdefault
    server-->browser: RETURN new total form data inventory
```

```mermaid
  graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

/* 
https://fullstackopen.com/en/part0/fundamentals_of_web_apps

https://github.com/mermaid-js/mermaid/blob/develop/README.md
https://mermaid.js.org/syntax/flowchart.html
*/
