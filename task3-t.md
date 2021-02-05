# Task 3
## Airports graph #3

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 1 hours --> Foxtrot
  Charlie -- 11 hours --> Whiskey
  Foxtrot -- 1 hours --> Charlie
  Foxtrot -- 5 hours --> Yankee
  Foxtrot -- 6 hours --> Romeo
  Foxtrot -- 9 hours --> Hotel
  Hotel -- 11 hours --> Yankee
  Hotel -- 9 hours --> Foxtrot
  Quebec -- 5 hours --> Yankee
  Romeo -- 1 hours --> Foxtrot
  Romeo -- 1 hours --> Sierra
  Sierra -- 1 hours --> Hotel
  Sierra -- 1 hours --> Romeo
  Sierra -- 11 hours --> Charlie
  Sierra -- 8 hours --> Whiskey
  Whiskey -- 11 hours --> Charlie
  Whiskey -- 7 hours --> Quebec
  Yankee -- 11 hours --> Hotel
  Yankee -- 5 hours --> Foxtrot
  Yankee -- 5 hours --> Quebec
</div>

---

[continue to next prompt](./task4prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    