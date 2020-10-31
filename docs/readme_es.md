
<h2 align='center'>
Hola! Bienvenidos a mi mundo :alien:
</h2>
<p align="center">
  <p align="center">
    <a href="/docs/readme_fr.md">Français </a>
    ·
    <a href="/docs/readme_es.md">Español</a>
    ·
    <a href="/docs/readme_pt-BR.md">Português</a>
    ·
    <a href="/docs/readme_en.md">English</a>
  </p>
</p>

<p align='center'>
<a href="https://dev.to/adelbs"><img height="30" src="https://raw.githubusercontent.com/adelbs/adelbs/main/icons/dev.png"></a>&nbsp;&nbsp;
<a href="https://instagram.com/felipisses"><img height="30" src="https://github.com/adelbs/adelbs/blob/main/icons/instagram.png?raw=true"></a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/felipejacob/"><img height="30" src="https://github.com/adelbs/adelbs/blob/main/icons/linkedin.png?raw=true"></a>
</p>


``` javascript

const Nerd = _=> {};
const Overlander = _=> {};

function Felipe() {
    try {
        Nerd.call(this);
        Overlander.call(this);
        CommonPerson.call(this); 
    } 
    catch(x) {
        console.log('Definitivamente no es una persona normal ...');
    }

    this.name = 'Felipe';
    this.personality = [
        'Yo uso punto y coma en JS', 
        'Cabeza snorkel para adelante, siempre', 
        'Café sin azucar',
        'Soñador'];

    this.currentMission = 'Intentando refactorizar el mundo';
} 

console.log(new Felipe());
