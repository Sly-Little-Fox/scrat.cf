# Home

Hello! Scrat.cf is a link shortener for [Scratch](https://scratch.mit.edu) projects!

To create a shortened link, just type **https://scrat.cf/projectid** or **https://scrat.cf#projectid**.

<script>
  if (isFinite(Number(location.hash.slice(1))) && location.hash) {
    location.href = `https://scratch.mit.edu/projects/${location.hash.slice(1)}`;
  }
</script>
