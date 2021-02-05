% Task 6
## Airports graph #6
<div class="mermaid-access">
graph LR
  Delta -- 5 hours --> India
  Delta -- 8 hours --> Echo
  Echo -- 7 hours --> Papa
  Echo -- 8 hours --> Delta
  India -- 11 hours --> Quebec
  India -- 4 hours --> Papa
  India -- 5 hours --> Delta
  India -- 9 hours --> X-ray
  Lima -- 9 hours --> Echo
  Mike -- 1 hours --> X-ray
  Mike -- 11 hours --> Quebec
  Mike -- 2 hours --> Lima
  Mike -- 6 hours --> Papa
  Quebec -- 1 hours --> Papa
  Quebec -- 11 hours --> Mike
  Quebec -- 8 hours --> Delta
  X-ray -- 2 hours --> Echo
  X-ray -- 3 hours --> Mike
  X-ray -- 5 hours --> Quebec
  X-ray -- 6 hours --> India
</div>

---

[continue to next prompt](./task7prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    