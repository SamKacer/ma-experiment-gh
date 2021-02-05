# Task 4
## Airports graph #4

<div></div>
<div class="mermaid-access">
graph LR
  Echo -- 1 hours --> Golf
  Echo -- 11 hours --> Yankee
  Echo -- 6 hours --> X-ray
  Echo -- 8 hours --> Mike
  Golf -- 1 hours --> Echo
  Mike -- 2 hours --> Romeo
  Mike -- 4 hours --> X-ray
  Mike -- 6 hours --> Papa
  Mike -- 8 hours --> Echo
  Papa -- 5 hours --> X-ray
  Papa -- 5 hours --> Yankee
  Romeo -- 2 hours --> Mike
  Romeo -- 2 hours --> Uniform
  Romeo -- 2 hours --> Yankee
  Uniform -- 10 hours --> X-ray
  Uniform -- 2 hours --> Romeo
  X-ray -- 10 hours --> Uniform
  X-ray -- 5 hours --> Papa
  X-ray -- 6 hours --> Echo
  Yankee -- 5 hours --> Papa
</div>

---

[continue to next prompt](./task5prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    