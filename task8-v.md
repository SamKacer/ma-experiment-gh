# task 8

## There is not a direct flight from Foxtrot to Bravo. Find one way of getting from Foxtrot to Bravo with connecting flights.

---

## Airports graph #8
<div></div>
<div class="mermaid-access">
graph LR
  Bravo -- 3 hours --> Papa
  Bravo -- 7 hours --> Delta
  Delta -- 1 hours --> Mike
  Delta -- 7 hours --> Bravo
  Foxtrot -- 1 hours --> November
  Foxtrot -- 10 hours --> Oscar
  Foxtrot -- 6 hours --> Golf
  Foxtrot -- 8 hours --> Mike
  Golf -- 11 hours --> Quebec
  Golf -- 6 hours --> Foxtrot
  Kilo -- 1 hours --> Oscar
  Mike -- 1 hours --> Delta
  Mike -- 8 hours --> Foxtrot
  November -- 9 hours --> Oscar
  Oscar -- 1 hours --> Kilo
  Oscar -- 10 hours --> Foxtrot
  Papa -- 10 hours --> Sierra
  Sierra -- 10 hours --> Papa
  Yankee -- 11 hours --> Bravo
  Yankee -- 7 hours --> November
</div>

---

[continue to short survey](./tlx-prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
