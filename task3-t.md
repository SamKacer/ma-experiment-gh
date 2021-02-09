# task 3

## How many direct flights that take 2 hours are there?

---

## Airports graph #3
<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 1 hours --> Kilo
  Delta -- 2 hours --> Lima
  Delta -- 7 hours --> Victor
  Foxtrot -- 2 hours --> Golf
  Golf -- 2 hours --> Foxtrot
  Golf -- 3 hours --> Whiskey
  Golf -- 5 hours --> Romeo
  Golf -- 9 hours --> Papa
  Kilo -- 1 hours --> Alfa
  Kilo -- 1 hours --> Papa
  Kilo -- 1 hours --> Romeo
  Kilo -- 2 hours --> Whiskey
  Lima -- 2 hours --> Delta
  Lima -- 7 hours --> India
  Papa -- 1 hours --> Kilo
  Papa -- 10 hours --> Delta
  Papa -- 2 hours --> Whiskey
  Romeo -- 6 hours --> Foxtrot
  Sierra -- 10 hours --> Foxtrot
  Victor -- 3 hours --> Whiskey
</div>

---

[continue to next task](./task4-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
