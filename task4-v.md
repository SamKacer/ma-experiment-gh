# Task 4
## Airports graph #4

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 11 hours --> X-ray
  Charlie -- 2 hours --> Delta
  Delta -- 10 hours --> X-ray
  Delta -- 2 hours --> Charlie
  Echo -- 7 hours --> Delta
  Echo -- 7 hours --> Oscar
  Echo -- 7 hours --> X-ray
  Echo -- 8 hours --> Uniform
  Oscar -- 11 hours --> Charlie
  Oscar -- 4 hours --> Delta
  Oscar -- 5 hours --> Sierra
  Oscar -- 7 hours --> Echo
  Sierra -- 5 hours --> Oscar
  Sierra -- 5 hours --> Yankee
  X-ray -- 10 hours --> Delta
  X-ray -- 10 hours --> Sierra
  X-ray -- 7 hours --> Echo
  X-ray -- 7 hours --> Yankee
  Yankee -- 5 hours --> Sierra
  Yankee -- 7 hours --> X-ray
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
    