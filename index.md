# Home

Hello! Scrat.cf is a link shortener for [Scratch](https://scratch.mit.edu) projects!

To create a shortened link, just type **https://scrat.cf/projectid** or **https://scrat.cf#projectid**.

<script>
  if (!isNaN(Number(location.hash.slice(1).replace('/', '')))) {
    location.href = `https://scratch.mit.edu/projects/${location.hash.slice(1).replace('/', '')}`;
  }
</script>
