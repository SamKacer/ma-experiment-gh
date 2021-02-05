# Task 7
## Airports graph #7

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 1 hours --> Uniform
  Alfa -- 10 hours --> Whiskey
  Alfa -- 2 hours --> Bravo
  Alfa -- 4 hours --> Charlie
  Bravo -- 11 hours --> Papa
  Bravo -- 2 hours --> Alfa
  Bravo -- 8 hours --> Charlie
  Charlie -- 1 hours --> Bravo
  Charlie -- 4 hours --> Alfa
  Charlie -- 5 hours --> Whiskey
  Delta -- 2 hours --> Papa
  India -- 7 hours --> Charlie
  India -- 8 hours --> Whiskey
  Papa -- 11 hours --> Uniform
  Papa -- 2 hours --> Delta
  Uniform -- 1 hours --> Alfa
  Uniform -- 11 hours --> Bravo
  Uniform -- 4 hours --> Whiskey
  Whiskey -- 4 hours --> Papa
  Whiskey -- 5 hours --> Charlie
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
    