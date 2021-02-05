# Task 6
## Airports graph #6

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 2 hours --> Lima
  Charlie -- 4 hours --> Mike
  Charlie -- 9 hours --> Echo
  Echo -- 2 hours --> Lima
  Echo -- 4 hours --> Tango
  Echo -- 6 hours --> Mike
  Echo -- 9 hours --> Charlie
  Foxtrot -- 10 hours --> Charlie
  Foxtrot -- 5 hours --> Delta
  Lima -- 11 hours --> Foxtrot
  Lima -- 2 hours --> Charlie
  Lima -- 2 hours --> Echo
  Mike -- 3 hours --> Tango
  Mike -- 4 hours --> Charlie
  Mike -- 6 hours --> Echo
  Mike -- 9 hours --> Romeo
  Romeo -- 4 hours --> Delta
  Romeo -- 9 hours --> Mike
  Tango -- 1 hours --> Charlie
  Tango -- 3 hours --> Mike
</div>

---

[continue to next prompt](./task7prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    