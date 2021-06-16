Javascript:

```javascript
window.open(
  "https://beta.simet.nic.br/widget.html",
  'Bentley Brasil - Teste de velocidade',
  'height=300,width=800,left=0,top=0,resizable=yes,scrollbars=yes,toolbar=yes,menubar=no,location=no,directories=no, status=yes'
);
```

HTML:

```html
<li class="moduleMenu" data-menu-module-id="">
  <a href="#" onclick="
    window.open(
      'https://beta.simet.nic.br/widget.html',
      'Bentley Brasil - Teste de velocidade',
      'height=300,width=800,left=0,top=0,resizable=yes,scrollbars=yes,toolbar=yes,menubar=no,location=no,directories=no, status=yes'
      );
    ">
    <span class="txt-container">Testar Velocidade</span>
  </a>
</li>
```
