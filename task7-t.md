# Task 7
## Airports graph #7

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 2 hours --> Delta
  Delta -- 2 hours --> Charlie
  Delta -- 4 hours --> Foxtrot
  Delta -- 8 hours --> Lima
  Foxtrot -- 4 hours --> Delta
  Kilo -- 2 hours --> Lima
  Kilo -- 7 hours --> Charlie
  Kilo -- 8 hours --> Oscar
  Lima -- 2 hours --> Kilo
  Lima -- 5 hours --> November
  Lima -- 5 hours --> Oscar
  Lima -- 8 hours --> Delta
  November -- 5 hours --> Lima
  November -- 7 hours --> Foxtrot
  Oscar -- 5 hours --> Lima
  Oscar -- 8 hours --> Kilo
  Oscar -- 8 hours --> November
  Quebec -- 1 hours --> Foxtrot
  Quebec -- 11 hours --> November
  Quebec -- 2 hours --> Kilo
</div>

---

[continue to next prompt](./task8prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    