# Task 7
## Airports graph #7

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 10 hours --> Delta
  Alfa -- 10 hours --> November
  Alfa -- 3 hours --> Golf
  Alfa -- 5 hours --> Lima
  Alfa -- 8 hours --> Charlie
  Bravo -- 5 hours --> Lima
  Charlie -- 8 hours --> Alfa
  Delta -- 1 hours --> Charlie
  Delta -- 10 hours --> Bravo
  Delta -- 4 hours --> Alfa
  Golf -- 3 hours --> Alfa
  Golf -- 5 hours --> November
  Lima -- 5 hours --> Bravo
  Lima -- 8 hours --> Alfa
  November -- 5 hours --> Golf
  November -- 8 hours --> Alfa
  X-ray -- 1 hours --> Lima
  X-ray -- 3 hours --> Golf
  X-ray -- 5 hours --> Charlie
  X-ray -- 8 hours --> Delta
</div>

---

[continue to next prompt](./task8prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    