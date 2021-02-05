# Task 6
## Airports graph #6

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 7 hours --> Alfa
  Charlie -- 7 hours --> Zulu
  Hotel -- 10 hours --> Kilo
  Hotel -- 6 hours --> Whiskey
  Hotel -- 7 hours --> Alfa
  Kilo -- 1 hours --> Zulu
  Kilo -- 10 hours --> Alfa
  Kilo -- 2 hours --> Hotel
  Kilo -- 6 hours --> Whiskey
  Kilo -- 8 hours --> Quebec
  Mike -- 1 hours --> Whiskey
  Mike -- 7 hours --> Alfa
  Mike -- 9 hours --> Zulu
  Quebec -- 11 hours --> Charlie
  Quebec -- 9 hours --> Whiskey
  Whiskey -- 1 hours --> Mike
  Whiskey -- 9 hours --> Quebec
  Zulu -- 6 hours --> Whiskey
  Zulu -- 7 hours --> Charlie
  Zulu -- 9 hours --> Mike
</div>

---

[continue to next prompt](./task7prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    