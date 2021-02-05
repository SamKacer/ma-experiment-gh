% Task 1
## Airports graph #1
<div class="mermaid-access">
graph LR
  Bravo -- 1 hours --> Charlie
  Bravo -- 6 hours --> Romeo
  Charlie -- 1 hours --> Bravo
  Delta -- 1 hours --> Romeo
  Delta -- 11 hours --> Mike
  Foxtrot -- 2 hours --> Delta
  Foxtrot -- 8 hours --> Quebec
  Juliett -- 4 hours --> Romeo
  Juliett -- 9 hours --> Bravo
  Mike -- 11 hours --> Charlie
  Mike -- 11 hours --> Delta
  Mike -- 3 hours --> Romeo
  Quebec -- 1 hours --> Romeo
  Quebec -- 8 hours --> Foxtrot
  Romeo -- 1 hours --> Quebec
  Romeo -- 3 hours --> Mike
  Romeo -- 4 hours --> Juliett
  Romeo -- 5 hours --> Foxtrot
  Romeo -- 6 hours --> Bravo
  Romeo -- 7 hours --> Delta
</div>

---

[continue to next prompt](./task2prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    