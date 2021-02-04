<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Scrat.cf</title>
  <script>
    if (!isNaN(Number(location.hash.slice(1))) || location.hash.slice(1).length == 9) {
      location.href = `//scratch.mit.edu/projects/${location.hash.slice(1)}`;
    }
  </script>
</head>

</html>
