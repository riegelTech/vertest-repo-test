# this is a file containing some common XSS

<img src="https://vertest.riegel.tech/fonts/flags/fr.svg" onload="alert('XSS from an image tag');" />

<script type="javascript">Alert('this is a pure JS XSS !'); </script>
<style>
  body {
    display: none !important;
  }
</style>

<iframe width="100%" height="100%" src="https://vertest.riegel.tech"></iframe>
