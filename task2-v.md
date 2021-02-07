# task 2

## How many incoming flights does Yankee have?

---

## Airports graph #2
<div></div>
<div class="mermaid-access">
graph LR
  Delta -- 6 hours --> Zulu
  Delta -- 7 hours --> Kilo
  Golf -- 5 hours --> Quebec
  Golf -- 6 hours --> Kilo
  Kilo -- 6 hours --> Golf
  Kilo -- 7 hours --> Quebec
  Kilo -- 8 hours --> Delta
  November -- 10 hours --> Uniform
  November -- 3 hours --> Quebec
  November -- 4 hours --> Yankee
  Quebec -- 3 hours --> November
  Quebec -- 5 hours --> Golf
  Quebec -- 6 hours --> Yankee
  Quebec -- 7 hours --> Kilo
  Quebec -- 8 hours --> Zulu
  Uniform -- 10 hours --> November
  Uniform -- 5 hours --> Yankee
  Yankee -- 5 hours --> Uniform
  Yankee -- 6 hours --> Quebec
  Zulu -- 8 hours --> Quebec
</div>

---

[continue to next task](./task3-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
