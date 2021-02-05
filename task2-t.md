# Task 2
## Airports graph #2

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 11 hours --> Uniform
  Charlie -- 6 hours --> Golf
  Golf -- 4 hours --> Uniform
  Golf -- 6 hours --> Charlie
  Golf -- 6 hours --> Romeo
  Golf -- 8 hours --> Oscar
  Lima -- 1 hours --> Romeo
  Oscar -- 10 hours --> Charlie
  Oscar -- 5 hours --> Papa
  Papa -- 4 hours --> Quebec
  Papa -- 5 hours --> Oscar
  Quebec -- 1 hours --> Uniform
  Quebec -- 2 hours --> Golf
  Quebec -- 4 hours --> Papa
  Romeo -- 1 hours --> Lima
  Romeo -- 6 hours --> Quebec
  Uniform -- 1 hours --> Quebec
  Uniform -- 11 hours --> Charlie
  Uniform -- 3 hours --> Papa
  Uniform -- 9 hours --> Oscar
</div>

---

[continue to next prompt](./task3prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    