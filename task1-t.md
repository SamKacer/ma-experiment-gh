# Task 1
## Airports graph #1

<div></div>
<div class="mermaid-access">
graph LR
  Delta -- 10 hours --> Oscar
  Delta -- 8 hours --> Yankee
  Lima -- 2 hours --> Romeo
  Lima -- 4 hours --> Zulu
  Lima -- 5 hours --> Oscar
  Oscar -- 10 hours --> Delta
  Oscar -- 3 hours --> Victor
  Oscar -- 5 hours --> Lima
  Romeo -- 10 hours --> Zulu
  Romeo -- 11 hours --> Yankee
  Romeo -- 2 hours --> Lima
  Romeo -- 3 hours --> Victor
  Victor -- 3 hours --> Oscar
  Whiskey -- 3 hours --> Delta
  Yankee -- 2 hours --> Whiskey
  Yankee -- 5 hours --> Victor
  Yankee -- 8 hours --> Delta
  Zulu -- 10 hours --> Romeo
  Zulu -- 11 hours --> Whiskey
  Zulu -- 4 hours --> Lima
</div>

---

[continue to next prompt](./task2prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    