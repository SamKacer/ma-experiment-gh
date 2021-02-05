# Task 7
## Airports graph #7

<div></div>
<div class="mermaid-access">
graph LR
  Delta -- 5 hours --> Uniform
  Foxtrot -- 11 hours --> Yankee
  Foxtrot -- 5 hours --> Uniform
  Golf -- 1 hours --> Kilo
  Golf -- 11 hours --> Yankee
  Golf -- 3 hours --> Uniform
  Kilo -- 1 hours --> Golf
  Kilo -- 6 hours --> Delta
  November -- 11 hours --> Foxtrot
  Tango -- 1 hours --> Kilo
  Tango -- 11 hours --> Delta
  Uniform -- 4 hours --> Golf
  Uniform -- 4 hours --> Yankee
  Uniform -- 5 hours --> Delta
  Uniform -- 5 hours --> Foxtrot
  Yankee -- 11 hours --> Foxtrot
  Yankee -- 11 hours --> Golf
  Yankee -- 4 hours --> Uniform
  Yankee -- 5 hours --> Delta
  Yankee -- 7 hours --> Kilo
</div>

---

[continue to next prompt](./task8prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    