# task 1

## How many outgoing flights does Tango have?

---

## Airports graph #1
<div></div>
<div class="mermaid-access">
graph LR
  Bravo -- 11 hours --> Delta
  Bravo -- 5 hours --> Mike
  Bravo -- 7 hours --> Quebec
  Charlie -- 11 hours --> Lima
  Charlie -- 9 hours --> Foxtrot
  Delta -- 1 hours --> Quebec
  Delta -- 11 hours --> Bravo
  Delta -- 3 hours --> Lima
  Delta -- 9 hours --> Romeo
  Echo -- 11 hours --> Lima
  Echo -- 11 hours --> Whiskey
  Foxtrot -- 4 hours --> Sierra
  Foxtrot -- 6 hours --> Lima
  Lima -- 11 hours --> Echo
  Lima -- 3 hours --> Delta
  Mike -- 6 hours --> Sierra
  Romeo -- 7 hours --> Lima
  Sierra -- 4 hours --> Foxtrot
  Sierra -- 6 hours --> Mike
  Tango -- 6 hours --> Mike
</div>

---

[continue to next task](./task2-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
