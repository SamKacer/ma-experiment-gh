# Task 6
## Airports graph #6

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 2 hours --> Lima
  Charlie -- 2 hours --> Mike
  Foxtrot -- 5 hours --> Delta
  Foxtrot -- 7 hours --> Charlie
  Foxtrot -- 9 hours --> Tango
  Lima -- 11 hours --> Foxtrot
  Lima -- 2 hours --> Charlie
  Lima -- 2 hours --> Tango
  Lima -- 8 hours --> Romeo
  Mike -- 10 hours --> Charlie
  Mike -- 6 hours --> Delta
  Mike -- 9 hours --> Romeo
  Romeo -- 3 hours --> Delta
  Romeo -- 8 hours --> Tango
  Romeo -- 9 hours --> Mike
  Tango -- 1 hours --> Echo
  Tango -- 2 hours --> Lima
  Tango -- 3 hours --> Delta
  Tango -- 8 hours --> Romeo
  Tango -- 9 hours --> Foxtrot
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
    