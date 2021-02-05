# Task 7
## Airports graph #7

<div></div>
<div class="mermaid-access">
graph LR
  Delta -- 1 hours --> Foxtrot
  Delta -- 8 hours --> Uniform
  Echo -- 10 hours --> Quebec
  Echo -- 4 hours --> Foxtrot
  Echo -- 5 hours --> November
  Echo -- 6 hours --> Uniform
  Foxtrot -- 11 hours --> November
  Foxtrot -- 3 hours --> Delta
  Foxtrot -- 4 hours --> Echo
  Mike -- 1 hours --> Foxtrot
  November -- 11 hours --> Foxtrot
  November -- 5 hours --> Echo
  November -- 7 hours --> Mike
  Quebec -- 10 hours --> Echo
  Tango -- 4 hours --> Delta
  Tango -- 4 hours --> Uniform
  Tango -- 5 hours --> Mike
  Uniform -- 6 hours --> Foxtrot
  Uniform -- 8 hours --> Delta
  Uniform -- 8 hours --> Quebec
</div>

---

[continue to next prompt](./task8prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    