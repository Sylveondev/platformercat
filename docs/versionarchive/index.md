# Version archive
Below is a list of versions released with Platformer Cat.
<script>
      (async () => {
        const response = await fetch('https://api.github.com/repos/:user/:repo/docs/versionarchive/versions');
        const data = await response.json();
        let htmlString = '<ul>';
        
        for (let file of data) {
          htmlString += `<li><a href="${file.path}">${file.name}</a></li>`;
        }

        htmlString += '</ul>';
        document.getElementsByTagName('body')[0].innerHTML = htmlString;
      })()
</script>
