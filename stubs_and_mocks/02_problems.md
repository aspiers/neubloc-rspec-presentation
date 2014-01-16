<!SLIDE bullets full-page problems>

## Problems with stubbing/mocking? ##

* <span class="bullet">»</span> Writing tests is more time consuming
* <span class="bullet">»</span> Need to know stubbed library internal implementations
* <span class="bullet">»</span> Need to write an integration test first

<script>
$(".problems").bind("showoff:next", function (event) {
  var li_1 = $(event.target).find("ul li:first");
  if (li_1.css("text-decoration") === "none") {
        event.preventDefault();
        li_1.css({textDecoration: "line-through"})
      }
});
</script>
