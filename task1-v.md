# Task 1
## Airports graph #1

<div></div>
<div class="mermaid-access">
graph LR
  Bravo -- 10 hours --> Lima
  Bravo -- 10 hours --> Quebec
  Charlie -- 6 hours --> Quebec
  Charlie -- 7 hours --> Echo
  Echo -- 1 hours --> Sierra
  Echo -- 11 hours --> Foxtrot
  Echo -- 11 hours --> Lima
  Echo -- 3 hours --> Bravo
  Echo -- 3 hours --> Tango
  Foxtrot -- 1 hours --> Tango
  Foxtrot -- 7 hours --> Echo
  Lima -- 11 hours --> Bravo
  Lima -- 11 hours --> Echo
  Lima -- 2 hours --> Tango
  Quebec -- 10 hours --> Bravo
  Quebec -- 6 hours --> Charlie
  Sierra -- 1 hours --> Echo
  Tango -- 1 hours --> Foxtrot
  Tango -- 2 hours --> Lima
  Tango -- 3 hours --> Echo
</div>

---

[continue to next prompt](./task2prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    