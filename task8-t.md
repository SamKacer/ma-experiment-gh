# task 8

## There is not a direct flight from Quebec to Yankee. Find one way of getting from Quebec to Yankee with connecting flights.

---

## Airports graph #8
<div></div>
<div class="mermaid-access">
graph LR
  Bravo -- 4 hours --> X-ray
  Bravo -- 7 hours --> Charlie
  Charlie -- 3 hours --> Papa
  Foxtrot -- 3 hours --> Yankee
  Foxtrot -- 5 hours --> Papa
  Lima -- 10 hours --> Victor
  Lima -- 2 hours --> November
  Lima -- 8 hours --> X-ray
  November -- 2 hours --> Lima
  November -- 6 hours --> Quebec
  Papa -- 3 hours --> Charlie
  Papa -- 5 hours --> Foxtrot
  Quebec -- 4 hours --> Papa
  Sierra -- 1 hours --> Yankee
  Victor -- 10 hours --> Lima
  Victor -- 5 hours --> X-ray
  Victor -- 7 hours --> Bravo
  Whiskey -- 7 hours --> Sierra
  X-ray -- 4 hours --> Bravo
  Yankee -- 3 hours --> Foxtrot
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
