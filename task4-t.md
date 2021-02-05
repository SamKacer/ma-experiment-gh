# Task 4
## Airports graph #4

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 10 hours --> Lima
  Charlie -- 11 hours --> X-ray
  Charlie -- 2 hours --> Whiskey
  Charlie -- 8 hours --> Echo
  Echo -- 8 hours --> Charlie
  India -- 7 hours --> Whiskey
  Lima -- 10 hours --> Charlie
  Lima -- 2 hours --> Sierra
  Lima -- 6 hours --> Yankee
  Sierra -- 2 hours --> Lima
  Sierra -- 4 hours --> Yankee
  Whiskey -- 11 hours --> Yankee
  Whiskey -- 7 hours --> India
  Whiskey -- 7 hours --> X-ray
  X-ray -- 7 hours --> Yankee
  Yankee -- 11 hours --> Echo
  Yankee -- 11 hours --> Whiskey
  Yankee -- 4 hours --> Sierra
  Yankee -- 6 hours --> Lima
  Yankee -- 7 hours --> X-ray
</div>

---

[continue to next prompt](./task5prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    