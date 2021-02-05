# Task 4
## Airports graph #4

<div></div>
<div class="mermaid-access">
graph LR
  Echo -- 2 hours --> Yankee
  Echo -- 6 hours --> Foxtrot
  Foxtrot -- 10 hours --> Quebec
  Foxtrot -- 6 hours --> Echo
  Foxtrot -- 8 hours --> Hotel
  Hotel -- 11 hours --> India
  Hotel -- 2 hours --> Romeo
  Hotel -- 5 hours --> Yankee
  Hotel -- 8 hours --> Foxtrot
  India -- 11 hours --> Hotel
  India -- 6 hours --> Romeo
  India -- 8 hours --> Foxtrot
  Juliett -- 7 hours --> Romeo
  Quebec -- 10 hours --> Foxtrot
  Quebec -- 4 hours --> Hotel
  Quebec -- 5 hours --> Juliett
  Romeo -- 4 hours --> Foxtrot
  Romeo -- 6 hours --> India
  Romeo -- 7 hours --> Juliett
  Yankee -- 2 hours --> Echo
</div>

---

[continue to next prompt](./task5prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    