# Task 8
## Airports graph #8

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 11 hours --> Quebec
  Alfa -- 11 hours --> Tango
  Alfa -- 2 hours --> Charlie
  Charlie -- 1 hours --> Oscar
  Charlie -- 2 hours --> Alfa
  Charlie -- 2 hours --> Papa
  Charlie -- 2 hours --> Quebec
  Delta -- 2 hours --> Oscar
  Delta -- 5 hours --> Tango
  Delta -- 5 hours --> Yankee
  Oscar -- 1 hours --> Charlie
  Oscar -- 2 hours --> Delta
  Oscar -- 8 hours --> Quebec
  Papa -- 3 hours --> Tango
  Quebec -- 11 hours --> Alfa
  Quebec -- 7 hours --> Tango
  Tango -- 10 hours --> Yankee
  Tango -- 3 hours --> Papa
  Tango -- 3 hours --> Quebec
  Yankee -- 8 hours --> Quebec
</div>

---

[continue to short survey](./tlx-prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    