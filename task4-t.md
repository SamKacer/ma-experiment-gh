% Task 4
## Airports graph #4
<div class="mermaid-access">
graph LR
  Charlie -- 10 hours --> Yankee
  Charlie -- 5 hours --> Victor
  Delta -- 1 hours --> Hotel
  Echo -- 3 hours --> Foxtrot
  Echo -- 6 hours --> Yankee
  Foxtrot -- 2 hours --> Yankee
  Foxtrot -- 3 hours --> Echo
  Foxtrot -- 5 hours --> Charlie
  Foxtrot -- 9 hours --> Hotel
  Hotel -- 1 hours --> Delta
  Hotel -- 9 hours --> Foxtrot
  Quebec -- 1 hours --> Victor
  Quebec -- 7 hours --> Yankee
  Victor -- 11 hours --> Charlie
  Victor -- 11 hours --> Quebec
  Yankee -- 1 hours --> Delta
  Yankee -- 10 hours --> Charlie
  Yankee -- 2 hours --> Foxtrot
  Yankee -- 6 hours --> Echo
  Yankee -- 7 hours --> Quebec
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
    