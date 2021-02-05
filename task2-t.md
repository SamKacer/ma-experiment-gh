# Task 2
## Airports graph #2

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 3 hours --> Mike
  Charlie -- 3 hours --> Zulu
  Charlie -- 5 hours --> Yankee
  Charlie -- 9 hours --> Papa
  Charlie -- 9 hours --> Quebec
  Mike -- 11 hours --> Papa
  Mike -- 3 hours --> Charlie
  Mike -- 4 hours --> Yankee
  Mike -- 5 hours --> Romeo
  Papa -- 11 hours --> Mike
  Papa -- 9 hours --> Charlie
  Quebec -- 9 hours --> Charlie
  Romeo -- 5 hours --> Mike
  Romeo -- 8 hours --> Zulu
  Uniform -- 9 hours --> Papa
  Yankee -- 1 hours --> Quebec
  Yankee -- 4 hours --> Papa
  Yankee -- 5 hours --> Charlie
  Zulu -- 5 hours --> Charlie
  Zulu -- 8 hours --> Romeo
</div>

---

[continue to next prompt](./task3prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    