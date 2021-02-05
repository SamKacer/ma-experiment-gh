# Task 3
## Airports graph #3

<div></div>
<div class="mermaid-access">
graph LR
  Delta -- 10 hours --> Zulu
  Delta -- 2 hours --> November
  Delta -- 2 hours --> Romeo
  Delta -- 7 hours --> Uniform
  Lima -- 7 hours --> Delta
  Lima -- 9 hours --> Uniform
  Mike -- 11 hours --> Romeo
  Mike -- 6 hours --> Uniform
  November -- 9 hours --> Uniform
  Romeo -- 11 hours --> Mike
  Romeo -- 3 hours --> Delta
  Romeo -- 3 hours --> Zulu
  Uniform -- 6 hours --> Mike
  Uniform -- 6 hours --> Yankee
  Uniform -- 9 hours --> November
  Yankee -- 10 hours --> Zulu
  Yankee -- 6 hours --> November
  Yankee -- 6 hours --> Uniform
  Zulu -- 2 hours --> Romeo
  Zulu -- 6 hours --> Yankee
</div>

---

[continue to next prompt](./task4prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    