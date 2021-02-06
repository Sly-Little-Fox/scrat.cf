# Scrat.cf

Hello! If you came here, it means you followed broken **scrat.cf** link or just typed **scrat.cf**. Don't be afraid of clicking **scrat.cf** links, they will always redirect you to Scratch project (if they are not broken).

To create one, just type **https://scrat.cf#projectid**

<script>
  if (isNaN(Number(location.hash.slice(1))) || location.hash.slice(1).length !== 9) {} else {
    location.href = `//scratch.mit.edu/projects/${location.hash.slice(1)}`;
  }
</script>
