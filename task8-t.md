# task 8

## There is not a direct flight from Delta to Romeo. Find one way of getting from Delta to Romeo with connecting flights.

---

## Airports graph #8
<div></div>
<div class="mermaid-access">
graph LR
  Delta -- 1 hours --> Juliett
  Delta -- 5 hours --> Tango
  Delta -- 8 hours --> Echo
  Echo -- 11 hours --> Mike
  Echo -- 6 hours --> Tango
  Echo -- 8 hours --> Delta
  Golf -- 9 hours --> Uniform
  Juliett -- 1 hours --> Delta
  Juliett -- 2 hours --> Romeo
  Juliett -- 7 hours --> Uniform
  Mike -- 10 hours --> Juliett
  Mike -- 11 hours --> Echo
  Mike -- 4 hours --> Romeo
  Mike -- 7 hours --> Tango
  Romeo -- 4 hours --> Mike
  Tango -- 6 hours --> Echo
  Tango -- 7 hours --> Mike
  Uniform -- 3 hours --> Tango
  Uniform -- 7 hours --> Juliett
  Uniform -- 9 hours --> Golf
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
