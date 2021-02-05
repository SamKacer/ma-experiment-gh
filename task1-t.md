# Task 1
## Airports graph #1

<div></div>
<div class="mermaid-access">
graph LR
  Foxtrot -- 10 hours --> Lima
  Foxtrot -- 8 hours --> India
  Golf -- 11 hours --> Lima
  India -- 4 hours --> Echo
  India -- 4 hours --> Sierra
  India -- 5 hours --> Foxtrot
  India -- 7 hours --> Oscar
  Lima -- 1 hours --> Oscar
  Lima -- 10 hours --> Foxtrot
  Lima -- 11 hours --> Golf
  Lima -- 2 hours --> Sierra
  Lima -- 6 hours --> Echo
  Oscar -- 1 hours --> Lima
  Oscar -- 2 hours --> Golf
  Oscar -- 8 hours --> Sierra
  Oscar -- 9 hours --> Papa
  Papa -- 5 hours --> Foxtrot
  Papa -- 9 hours --> Oscar
  Sierra -- 2 hours --> Papa
  Sierra -- 4 hours --> India
</div>

---

[continue to next prompt](./task2prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    