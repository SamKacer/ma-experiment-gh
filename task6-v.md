# Task 6
## Airports graph #6

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 10 hours --> X-ray
  Alfa -- 6 hours --> Tango
  Charlie -- 1 hours --> X-ray
  Charlie -- 4 hours --> Alfa
  Delta -- 1 hours --> Romeo
  Delta -- 4 hours --> Victor
  Delta -- 7 hours --> X-ray
  Delta -- 9 hours --> Golf
  Romeo -- 1 hours --> Delta
  Romeo -- 1 hours --> Victor
  Romeo -- 2 hours --> Charlie
  Tango -- 11 hours --> Romeo
  Tango -- 5 hours --> Golf
  Victor -- 1 hours --> Romeo
  Victor -- 4 hours --> Delta
  Victor -- 8 hours --> X-ray
  X-ray -- 1 hours --> Charlie
  X-ray -- 10 hours --> Alfa
  X-ray -- 7 hours --> Delta
  X-ray -- 8 hours --> Victor
</div>

---

[continue to next prompt](./task7prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    