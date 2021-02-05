# Task 5
## Airports graph #5

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 3 hours --> Foxtrot
  Alfa -- 5 hours --> Delta
  Delta -- 5 hours --> Alfa
  Delta -- 5 hours --> November
  Delta -- 8 hours --> Whiskey
  Echo -- 11 hours --> Foxtrot
  Echo -- 5 hours --> Lima
  Foxtrot -- 10 hours --> Whiskey
  Foxtrot -- 11 hours --> Echo
  Foxtrot -- 4 hours --> November
  Foxtrot -- 5 hours --> Alfa
  Juliett -- 4 hours --> Whiskey
  Juliett -- 8 hours --> Alfa
  Lima -- 5 hours --> Echo
  Lima -- 7 hours --> November
  November -- 4 hours --> Foxtrot
  November -- 5 hours --> Delta
  Whiskey -- 10 hours --> Foxtrot
  Whiskey -- 4 hours --> Juliett
  Whiskey -- 8 hours --> Delta
</div>

---

[continue to next prompt](./task6prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    