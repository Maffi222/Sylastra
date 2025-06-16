
<script>
  const password = "SimonLimon2";
  const entered = prompt("Enter password to view this character sheet:");
  if (entered !== password) {
    document.body.innerHTML = "<h2>Access denied.</h2>";
    throw new Error("Wrong password");
  }
</script>

# Alice's Character Sheet

... your character info here ...
