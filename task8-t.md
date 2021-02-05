# Task 8
## Airports graph #8

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 6 hours --> Lima
  Charlie -- 7 hours --> Mike
  Echo -- 4 hours --> Mike
  Echo -- 6 hours --> Zulu
  Echo -- 8 hours --> India
  India -- 11 hours --> Charlie
  India -- 4 hours --> Oscar
  India -- 5 hours --> Zulu
  India -- 7 hours --> Mike
  India -- 8 hours --> Echo
  Lima -- 11 hours --> Oscar
  Lima -- 2 hours --> Uniform
  Mike -- 7 hours --> Charlie
  Mike -- 7 hours --> India
  Oscar -- 11 hours --> India
  Oscar -- 6 hours --> Lima
  Oscar -- 9 hours --> Charlie
  Uniform -- 7 hours --> Mike
  Zulu -- 11 hours --> India
  Zulu -- 5 hours --> Echo
</div>

---

[continue to short survey](./tlx-prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    