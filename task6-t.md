# Task 6
## Airports graph #6

<div></div>
<div class="mermaid-access">
graph LR
  Hotel -- 4 hours --> India
  Hotel -- 8 hours --> Tango
  India -- 3 hours --> Tango
  India -- 4 hours --> Hotel
  Juliett -- 8 hours --> Tango
  Oscar -- 3 hours --> Uniform
  Oscar -- 4 hours --> Foxtrot
  Oscar -- 5 hours --> Tango
  Tango -- 11 hours --> X-ray
  Tango -- 2 hours --> Juliett
  Tango -- 3 hours --> Foxtrot
  Tango -- 3 hours --> India
  Tango -- 3 hours --> Uniform
  Tango -- 5 hours --> Oscar
  Tango -- 8 hours --> Hotel
  Uniform -- 2 hours --> Foxtrot
  Uniform -- 3 hours --> Tango
  X-ray -- 11 hours --> Foxtrot
  X-ray -- 2 hours --> Juliett
  X-ray -- 2 hours --> Tango
</div>

---

[continue to next prompt](./task7prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    