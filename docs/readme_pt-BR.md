
<h2 align='center'>
Olá! Bem vindos ao meu mundo :alien:
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
&nbsp;
<a href="https://open.spotify.com/user/adelbs?si=gHIlN5AlSMKLfs063DUjEQ"><img height="30" src="https://github.com/adelbs/adelbs/blob/main/icons/spotify.png?raw=true"></a>
&nbsp;
<a href="https://www.goodreads.com/user/show/59344121-felipe-jacob"><img height="30" src="https://github.com/adelbs/adelbs/blob/main/icons/goodreads.png?raw=true"></a>
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
        console.log('Definitivamente não é uma pessoa normal...');
    }

    this.name = 'Felipe';
    this.personality = [
        'Eu uso ponto e vírgula no JS', 
        'Snorkel virado sempre para frente', 
        'Café sem açucar, por favor',
        'Sonhador'];

    this.currentMission = 'Tentando refatorar o mundo';
} 

console.log(new Felipe());
