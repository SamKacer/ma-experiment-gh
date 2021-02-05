# Task 1
## Airports graph #1

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 6 hours --> Foxtrot
  Alfa -- 9 hours --> India
  Bravo -- 2 hours --> Victor
  Bravo -- 7 hours --> India
  Echo -- 5 hours --> Tango
  Echo -- 7 hours --> Kilo
  Foxtrot -- 11 hours --> Kilo
  Foxtrot -- 11 hours --> Victor
  Foxtrot -- 4 hours --> Tango
  Foxtrot -- 6 hours --> Alfa
  India -- 1 hours --> Kilo
  India -- 7 hours --> Bravo
  Kilo -- 1 hours --> Tango
  Kilo -- 7 hours --> Echo
  Tango -- 1 hours --> Kilo
  Tango -- 10 hours --> Alfa
  Tango -- 4 hours --> Foxtrot
  Tango -- 9 hours --> India
  Victor -- 10 hours --> Kilo
  Victor -- 2 hours --> Bravo
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
    